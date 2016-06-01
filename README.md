PHP5-Xdebug Ansible Role
==========================

Installs the latest PHP Xdebug on an Ubuntu host. This enables you to hook your PHP application to IDEs of your choice that has facilities for remote debugging your source code.

## Role Variables

##### Defaults

- `php_xdebug_extension` - 'xdebug.so'
- `php_xdebug_remote_enable` - on
- `php_xdebug_remote_connect_back` - on
- `php_xdebug_remote_autostart` - on
- `php_xdebug_remote_host` - 'localhost'
- `php_xdebug_remote_port` - 9000
- `php_xdebug_idekey` - 'vagrant'

Usage
-----

```yaml
roles:
    - { role: webhop.php5-xdebug }
```

Author Information
-------------------

* Luis Ramos - luis@beamly.com
