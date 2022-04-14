laravel-simple-html-dom
==========================

Version 1.9.1(291) - Update 18/4/2021

Adaptation for Composer and PSR-0 of:

A HTML DOM parser written in PHP5+ let you manipulate HTML in a very easy way!
Require PHP 5+.
Supports invalid HTML.
Find tags on an HTML page with selectors just like jQuery.
Extract contents from HTML in a single line.

http://simplehtmldom.sourceforge.net/


Install
-------

 composer.phar
```json
 composer require drnxloc/laravel-simple-html-dom
```

Usage
-----

```php
use Drnxloc\LaravelHtmlDom\HtmlDomParser;

...
$dom = HtmlDomParser::str_get_html( $str );
or 
$dom = HtmlDomParser::file_get_html( $file_name );

$elems = $dom->find($elem_name);
...

```
