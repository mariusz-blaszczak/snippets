#### Wymuszenie pełnych zapytań SQL, żeby można je było sobie kopiować do tableplus
```
# config/database.yml
prepared_statements: false
```

List all rake tasks with source path
```
rake -W
```


Enable sql logs in rails console or runner
```
ActiveRecord::Base.logger = Logger.new(STDOUT)
```

Refer url helper in rails console
```
app.delete_all_merchants_promo_path
```

Make hash accepting keys as string or symbols:
```
result.with_indifferent_access
```
https://api.rubyonrails.org/v4.2/classes/ActiveSupport/HashWithIndifferentAccess.html
