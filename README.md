# apache-php-mono

This image is based on php:apache (see https://hub.docker.com/_/php/), with the addition of mono-devel.
It was created to support a PHP app that needs to call a .NET program.

Usage is the same as for the original php:apache image.

This images does **not** support running ASP.NET apps (i.e. it does not include mod_mono). 
