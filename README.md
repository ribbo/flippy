flippy
======

Simple rotating text jQuery plugin

Demo
----

I will upload a demo soon.


Installation
------------

Include <a href="http://ajax.googleapis.com/ajax/libs/jquery/1/jquery.min.js">jQuery</a> and the `flippy.js` script:

```
<script src="flippy.js" type="text/javascript"></script>
```

Include the `flippy.css` stylesheet:

```
<link href="flippy.css" media="screen" rel="stylesheet" type="text/css" />
```


Using flippy.js
-------------

Invoking the flippy plugin:

```
$('element').flippy();
```

Options
-------

Below are the supported options and their default values:

```
settings = {
  stop: false,        // stop after iteration through all items
  interval: 3,        // time (seconds) between flips
  speed: 1000,        // speed (ms) of animations
  distance: "150px"   // distance to fade out
}
```
