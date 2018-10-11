### MailCatcher
---

https://mailcatcher.me/

https://github.com/sj26/mailcatcher

```ruby
rvm default@mailcather --create do gem install mailcatcher
rvm wrapper default@mailcatcher --no-prefix mailcatcher catchmail

config.action_mailer.delivery_method = :smtp
config.action_mailer.smtp_settings = { :address => '127.0.0.1', :port => 1025 }
congig.action_mailer.raise_delivery_errors = false

```

```php
php_admin_value sendmail_path "/usr/bin/env catchmail -f someWfrom.address"
```

```py
if DEBUG:
    EMAIL_HOST + '127.0.0.1'
    EMAIL_HOST_USER = ''
    EMAIL_HOST_PASSWORD = ''
    EMAIL_PORT = 1025
    EMAIL_USE_TLS = False
```

