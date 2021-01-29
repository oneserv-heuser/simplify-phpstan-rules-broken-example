# simplify-phpstan-rules-broken-example

To reproduce the error:

You need either PHP 7.3 or 7.4.

```
composer i
vendor/bin/phpstan analyse -c phpstan.neon Test/DataObject.php
```

The following error should occur:
```
------ --------------------------------------------------------------------------------
  Line   DataObject.php
 ------ --------------------------------------------------------------------------------
         Syntax error, unexpected '{', expecting T_VARIABLE on line 818 on unknown line
 ------ --------------------------------------------------------------------------------

```
