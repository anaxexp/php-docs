# Containers 

The PHP stack consist of the following containers:

| Container    | Versions           | Image                              |
| ------------ | ------------------ | ---------------------------------- |
| [Apache]     | 2.4                | [anaxexp/php-apache]                 |
| [AthenaPDF]  | 2.10.0             | [arachnysdocker/athenapdf-service] |
| [Blackfire]  | latest             | [blackfire/blackfire]              |
| [Crond]      | -                  | [anaxexp/php]                        |
| [Mailhog]    | latest             | [mailhog/mailhog]                  |
| [MariaDB]    | 10.3, 10.2, 10.1   | [anaxexp/mariadb]                    |
| [Memcached]  | 1.5                | [anaxexp/memcached]                  |
| [Nginx]      | 1.15, 1.14, 1.13   | [anaxexp/php-nginx]                  |
| [Node.js]    | 9.11, 8.11, 6.14   | [anaxexp/node]                       |
| [OpenSMTPD]  | 6.0                | [anaxexp/opensmtpd]                  |
| [PHP]        | 7.x, 5.6, 5.3      | [anaxexp/php]                        |
| [PostgreSQL] | 10, 9.x            | [anaxexp/postgres]                   |
| [Redis]      | 4.0, 3.2           | [anaxexp/redis]                      |
| [Rsyslog]    | latest             | [anaxexp/rsyslog]                    |
| [Solr]       | 7.x, 6.6, 5.5, 5.4 | [anaxexp/solr]                       |
| [SSHD]       | -                  | [anaxexp/php]                        |
| [Varnish]    | 4.1                | [anaxexp/varnish]                    |
| [Webgrind]   | 1.5                | [anaxexp/webgrind]                   |
| Adminer      | 4.6                | [anaxexp/adminer]                    |
| phpMyAdmin   | latest             | [phpmyadmin/phpmyadmin]            |

!!! note "SSHD and Cron"
    For AnaxExp environments we additionally spin up copies of PHP services with overridden commands to run cron and ssh daemons. All environment variables added to PHP service will be automatically passed to [SSHD] and [Cron] services.

[Apache]:  ../containers/apache.md
[AthenaPDF]:  ../containers/athenapdf.md
[Blackfire]:  ../containers/blackfire.md
[Crond]:  ../containers/cron.md
[Mailhog]:  ../containers/mailhog.md
[MariaDB]:  ../containers/mariadb.md
[Memcached]:  ../containers/memcached.md
[Nginx]:  ../containers/nginx.md
[Node.js]:  ../containers/node.md
[OpenSMTPD]:  ../containers/opensmtpd.md
[PHP]:  ../containers/php.md
[PostgreSQL]:  ../containers/postgres.md
[Redis]:  ../containers/redis.md
[Rsyslog]:  ../containers/rsyslog.md
[Solr]:  ../containers/solr.md
[SSHD]:  ../containers/ssh.md
[Varnish]:  ../containers/varnish.md
[Webgrind]:  ../containers/webgrind.md

[arachnysdocker/athenapdf-service]: https://hub.docker.com/r/arachnysdocker/athenapdf-service
[blackfire/blackfire]: https://hub.docker.com/r/blackfire/blackfire
[mailhog/mailhog]: https://hub.docker.com/r/mailhog/mailhog
[phpmyadmin/phpmyadmin]: https://hub.docker.com/r/phpmyadmin/phpmyadmin
[anaxexp/adminer]: https://hub.docker.com/r/anaxexp/adminer
[anaxexp/mariadb]: https://github.com/anaxexp/mariadb
[anaxexp/memcached]: https://github.com/anaxexp/memcached
[anaxexp/node]: https://github.com/anaxexp/node
[anaxexp/opensmtpd]: https://github.com/anaxexp/opensmtpd
[anaxexp/php-apache]: https://github.com/anaxexp/php-apache
[anaxexp/php-nginx]: https://github.com/anaxexp/php-nginx
[anaxexp/php]: https://github.com/anaxexp/php
[anaxexp/postgres]: https://github.com/anaxexp/postgres
[anaxexp/redis]: https://github.com/anaxexp/redis
[anaxexp/rsyslog]: https://hub.docker.com/r/anaxexp/rsyslog
[anaxexp/solr]: https://github.com/anaxexp/solr
[anaxexp/varnish]: https://github.com/anaxexp/varnish
[anaxexp/webgrind]: https://hub.docker.com/r/anaxexp/webgrind
