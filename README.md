# nginx-varnish-wordpress

Nginx tuning for best performance.

## Configurations

* [nginx](https://github.com/alxshelepenok/nginx-varnish-wordpress/tree/master/nginx)
* [varnish 4](https://github.com/alxshelepenok/nginx-varnish-wordpress/tree/master/varnish)
* [php-fpm](https://github.com/alxshelepenok/nginx-varnish-wordpress/tree/master/php5-fpm)
* [ubuntu sysctl.conf](https://github.com/alxshelepenok/nginx-varnish-wordpress/tree/master/ubuntu)

Purge Varnish WordPress-cache: [Varnish HTTP Purge](https://wordpress.org/plugins/varnish-http-purge/)

Varnish 4 restart using service wrapper script: `service varnish restart`

Nginx 4 restart using service wrapper script: `service nginx restart`

php-fpm 4 restart using service wrapper script: `service php5-fpm restart`

## License
The MIT license.

Copyright (c) 2016-2022 Alexander Shelepenok

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies
of the Software, and to permit persons to whom the Software is furnished to do
so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
