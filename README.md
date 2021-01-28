# simplify-phpstan-rules-broken-example

To reproduce the error:

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
