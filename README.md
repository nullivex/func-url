func-url
========

URL related functions (shortname, urlname, etc)

Usage
----
```php
$name = 'This Page';
$urlname = urlname($name); //returns this-page
$shortname = shortname($name); //returns thispage
```

Reference
----

### (string) urlname($name)
Equivalent of strtolower and replace all spaces with -

### (string) shortname($name)
Strips all non alpha-numeric characters

