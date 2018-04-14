## About
Template files and custom `monitrc` configuration file.

## Usage

Copy the `monitrc` configuration file to `/etc/monit` and the .conf files that you need to `/etc/monit/conf.d`. Only use the templates that you need. Installing the Redis template without having Redis installed will result in an error.

Restart Monit: `monit reload`

## Author
Created by [Patrick H. Mullins](http://www.pmullins.net). You can find me on  [Twitter](https://twitter.com/phmullins) and on [Telegram](https://telegram.org/) as @pmullins.

## License
Source is released under the FreeBSD (BSD-2-Clause) License [license](license.md).
