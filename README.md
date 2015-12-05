# phalcon-mamp
Phalcon is a web framework implemented as a C extension offering high performance and lower resource consumption http://phalconphp.com/

*Currently there is only one version that support php5.6.16*

For other versions, please check this repository: https://github.com/majksner/php-phalcon-mamp

- phalcon 2.08 build for php-5.6.16

# Installation
1. Copy phalcon.so to `/Applications/mampstack-5.6.16-0/php/lib/php/extensions`
2. Add extension=phalcon.so to the end of php.ini (`/Applications/mampstack-5.6.16-0/php/etc/php.ini`)
3. Restart MAMP.

# Result
If everything is fine `phpinfo();` should look like this.
![phalcon for mamp php 5.6.16](https://i.imgur.com/JdFq9ZR.png)
