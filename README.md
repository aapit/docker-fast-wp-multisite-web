# docker-fast-wp-multisite-web
[![](https://images.microbadger.com/badges/image/aapit/fast-wp-multisite-web.svg)](https://microbadger.com/images/aapit/fast-wp-multisite-web)

The Docker image for the nginx server in my fast WordPress cluster.
Multisite version.

## Requirements
* An attached php-fpm server (f.i. Docker container) at:
  `php:9000`, where `php` is the hostname provided in `docker-compose.yml`
* Redirects expect you to have a WordPress structure according to [Bedrock from Roots](https://roots.io/bedrock/).
* An `nginx.conf` file in your webroot. You can leave this empty or use it for configuration that overrides the default, but it needs to be present.
