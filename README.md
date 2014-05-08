# MemcacheSASL

A pure PHP Memcache client with [binary
protocol](http://code.google.com/p/memcached/wiki/BinaryProtocolRevamped),
[SASL](http://code.google.com/p/memcached/wiki/SASLAuthProtocol) &
[Doctrine Cache](http://docs.doctrine-project.org/en/2.0.x/reference/caching.html#memcache)
support.

It aims to be compatible with the PHP Memcached class. You can find
documentation on the PHP Memcached class
[here](http://php.net/manual/en/class.memcached.php). Not all features
are supported at this time.


## Changes vs. ronnywang Version

This is a fork of the original code base by [Ronny
Wang](https://github.com/ronnywang/PHPMemcacheSASL).

[MemCachier](https://github.com/memcachier) made the following improvements:

* Support for `flush`.
* Support for timeouts on operations (connections and requests).
* Fixed `increment` and `decrement` operations.
* Support for the PHP Composer package manager.

[treeskelt](https://github.com/treeskelt) made the following improvements:

* Support for Doctrine Memcache Cache Driver
* Support for the PHP Composer package manager.

## Licensing

This library is BSD-licensed.


## Authors

This library was written by
[Ronny
Wang](https://github.com/ronnywang), [MemCachier
](https://github.com/memcachier) & [treeskelt
](https://github.com/treeskelt).

Ronny Wang wrote the initial version and bulk of the code,
MemCachier & treeskelt later forked it to improve on the code base.

