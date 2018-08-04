# Local environment with Docker4PHP

Docker4PHP is an open-source project ([GitHub page](https://github.com/anaxexp/php4docker)) that provides pre-configured `docker-compose.yml` file from to spin up local environment on Linux, Mac OS X and Windows. 

## Requirements

* Install Docker ([Linux](https://docs.docker.com/engine/installation), [Docker for Mac](https://docs.docker.com/engine/installation/mac) or [Docker for Windows (10+ Pro)](https://docs.docker.com/engine/installation/windows))
* For Linux additionally install [docker compose](https://docs.docker.com/compose/install)

The `docker-compose.yml` file provides the following services:

| Container     | Versions           | Service name    | Image                              |
| ------------- | ------------------ | --------------- | ---------------------------------- |
| [Nginx]       | 1.15, 1.14, 1.13   | `nginx`         | [anaxexp/php-nginx]                  |
| [Apache]      | 2.4                | `apache`        | [anaxexp/php-apache]                 |
| [PHP]         | 7.x, 5.6           | `php`           | [anaxexp/php]                        |
| [MariaDB]     | 10.3, 10.2, 10.1   | `mariadb`       | [anaxexp/mariadb]                    |
| [PostgreSQL]  | 10, 9.x            | `postgres`      | [anaxexp/postgres]                   |
| [Redis]       | 4.0, 3.2           | `redis`         | [anaxexp/redis]                      |
| [Node.js]     | 9.11, 8.11, 6.14   | `node`          | [anaxexp/node]                       |
| [Varnish]     | 4.1                | `varnish`       | [anaxexp/varnish]                    |
| [Solr]        | 7.x, 6.6, 5.5, 5.4 | `solr`          | [anaxexp/solr]                       |
| Elasticsearch | 6.x, 5.6, 5.5, 5.4 | `elasticsearch` | [anaxexp/elasticsearch]              |
| Kibana        | 6.x, 5.6, 5.5, 5.4 | `kibana`        | [anaxexp/kibana]                     |
| [Memcached]   | 1.5                | `memcached`     | [anaxexp/memcached]                  |
| [Webgrind]    | 1.5                | `webgrind`      | [anaxexp/webgrind]                   |
| [Blackfire]   | latest             | `blackfire`     | [blackfire/blackfire]              |
| [Rsyslog]     | latest             | `rsyslog`       | [anaxexp/rsyslog]                    |
| [AthenaPDF]   | 2.10.0             | `athenapdf`     | [arachnysdocker/athenapdf-service] |
| [Mailhog]     | latest             | `mailhog`       | [mailhog/mailhog]                  |
| [OpenSMTPD]   | 6.0                | `opensmtpd`     | [anaxexp/opensmtpd]                  |
| Adminer       | 4.6                | `adminer`       | [anaxexp/adminer]                    |
| phpMyAdmin    | latest             | `pma`           | [phpmyadmin/phpmyadmin]            |
| Portainer     | latest             | `portainer`     | [portainer/portainer]              |
| Traefik       | latest             | `traefik`       | [_/traefik]                        |

[Apache]: ../containers/apache.md
[AthenaPDF]: ../containers/athenapdf.md
[Blackfire]: ../containers/blackfire.md
[Cron]: ../containers/cron.md
[Elasticsearch]: ../containers/elasticsearch.md
[Kibana]: ../containers/kibana.md
[Mailhog]: ../containers/mailhog.md
[MariaDB]: ../containers/mariadb.md
[Memcached]: ../containers/memcached.md
[Nginx]: ../containers/nginx.md
[Node.js]: ../containers/node.md
[OpenSMTPD]: ../containers/opensmtpd.md
[PHP]: ../containers/php.md
[PostgreSQL]: ../containers/postgres.md
[Redis]: ../containers/redis.md
[Rsyslog]: ../containers/rsyslog.md
[Solr]: ../containers/solr.md
[SSHD]: ../containers/ssh.md
[Varnish]: ../containers/varnish.md
[Webgrind]: ../containers/webgrind.md

[_/node]: https://hub.docker.com/_/node
[_/traefik]: https://hub.docker.com/_/traefik
[arachnysdocker/athenapdf-service]: https://hub.docker.com/r/arachnysdocker/athenapdf-service
[blackfire/blackfire]: https://hub.docker.com/r/blackfire/blackfire
[mailhog/mailhog]: https://hub.docker.com/r/mailhog/mailhog
[phpmyadmin/phpmyadmin]: https://hub.docker.com/r/phpmyadmin/phpmyadmin
[portainer/portainer]: https://hub.docker.com/portainer/portainer
[anaxexp/adminer]: https://hub.docker.com/r/anaxexp/adminer
[anaxexp/elasticsearch]: https://github.com/anaxexp/elasticsearch
[anaxexp/kibana]: https://github.com/anaxexp/kibana
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
