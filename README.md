<long-tail>
===========

A Spotify widget playing an artist's least popular tracks - built with polymer

Demo and background
-------------------

* Web-app using the widget: http://longtail.mdg.io
* Background reading: http://apassant.net/2014/07/05/long-tail-spotify-polymer


Install
-------

The easiest way is to install via Bower:

    bower install long-tail

Usage
-----

Import polyfill

    <head>
      <script src="bower_components/platform/platform.js"></script>
    </head>

Import custom element
    
    <head>
      <script src="bower_components/platform/platform.js"></script>
      <link rel="import" href="bower_components/long-tail/long-tail.html">
    </head>

Load element

    <body>
      <long-tail artist="4tZwfgrHOc3mvqYlEYSvVi" size="25"></long-tail>
    </body>

Arguments
---------

* artist: A spotify artist ID
* size: Number of tracks (max/default = 50)

License
-------

MIT

Contact
-------

Alexandre Passant [http://apassant.net] + [http://mdg.io]

