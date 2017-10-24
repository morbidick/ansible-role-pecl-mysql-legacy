# Legacy MySQL functions for PHP7

[![Build Status](https://travis-ci.org/morbidick/ansible-role-pecl-mysql-legacy.svg?branch=master)](https://travis-ci.org/morbidick/ansible-role-pecl-mysql-legacy)

The mysql module is deprecated and should only be used if there is *really* no other way! For more infos on what this role does see [this blogpost](https://ckon.wordpress.com/2015/08/06/put-mysql-functions-back-into-php-7/). An installed webserver with php support is expected.

For all options see [defaults/main.yml](defaults/main.yml).

## Development

You can use the [Vagrantfile](Vagrantfile) for local testing, just install vagrant and virtualbox and execute the following commands.

````bash
vagrant up
vagrant provision
````

## License

MIT
