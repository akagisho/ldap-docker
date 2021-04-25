FROM php:7-fpm

COPY php.ini /usr/local/etc/php/

COPY --from=mlocati/php-extension-installer /usr/bin/install-php-extensions /usr/bin/

RUN install-php-extensions ldap
