# phpmig-bitrix

This is an adaptor to use [phpmig](https://github.com/davedevelopment/phpmig) with [bitrix framework](http://bitrix.ru).

## How to

```bash
$ composer require antonlee/phpmig-bitrix
$ vendor/bin/phpmig-bitrix
```

Simply run `vendor/bin/phpmig-bitrix` to bootstrap phpmig config files.

Make sure `$_SERVER['DOCUMENT_ROOT']` is set properly in `phpmig.php`.
