Serializer
==========

Official [documentation](http://jmsyst.com/libs/serializer).

This fork is used to fix a bug in a legacy project which still has a PHP 5.3.x requirement but needs to work with PHP 5.6.
The issue was fixed in official 1.0 release (https://github.com/schmittjoh/serializer/pull/431).

## Composer configuration

composer.json
```    "repositories": [
        {
            "type": "vcs",
            "url": "https://github.com/julienverrecchia/serializer"
        }
    ],```

```    "require": {
            ...
            "jms/serializer": "dev-php56fix as 0.16.0",
            ...
        }
    },```

Tag : 0.17