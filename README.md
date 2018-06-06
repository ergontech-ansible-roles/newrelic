New Relic Role
=========

Installs and configures New Relic's PHP Agent

> The package name for the New Relic for PHP agent is newrelic-php5. Although the name references PHP 5, this package works for all supported PHP versions, including PHP 7 versions.


Role Variables
--------------

```
# all
php_version: 5.6
newrelic_license_key: asdf

# staging
install_newrelic: true
newrelic_agent_appname: Staging App

# production
install_newrelic: true
newrelic_agent_appname: Production App
```

Dependencies
------------

PHP
PHP-FPM

Use Role
----------------

```
# requirments.yml

- src: https://github.com/ergontech-ansible-roles/newrelic
  version: master
  name: newrelic
```

License
-------

MIT
