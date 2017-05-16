Varnish HTTP Purge
==================

This is a fork of [Ipstenu/varnish-http-purge](https://github.com/Ipstenu/varnish-http-purge) which supports multiple Varnish backend servers, because the original does not.  In wp-config.php:

```
define( 'VHP_VARNISH_IP', 'varnish-0.example.com:6081,varnish-1.example.com:6081');
```
