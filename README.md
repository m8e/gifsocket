# React/Gifsocket

"Real Time communication library using Animated Gifs as a transport™" - Alvaro
Videla.

![React](https://raw.github.com/reactphp/gifsocket/master/doc/react.png)
![Mind Blown](https://raw.github.com/reactphp/gifsocket/master/doc/mybrain.gif)

This is a PHP port of the very awesome
[gifsockets](https://github.com/videlalvaro/gifsockets) by Alvaro Videla. It
is using `React/Http` for delivery.

## Installation

Through [composer](http://getcomposer.org).

## Usage

First, start the example server:

    $ php examples/stdin.php

Next, open up a browser and point it to `localhost:8080`. Now you can start
typing stuff into the server window. Each line captured by STDIN will be
converted to a GIF frame and streamed to the browser in Real Time (tm), also
known as Netscape Time (tm).

## Browser support

Good:

* IE6
* Safari
* Firefox

Bad:

* Opera

Non-existent:

* Chrome

## License

MIT, see LICENSE.

## Credits

* Alvaro Videla, for [gifsockets](https://github.com/videlalvaro/gifsockets)
* László Zsidi, for the [GifEncoder](http://www.phpclasses.org/package/3163-PHP-Generate-GIF-animations-from-a-set-of-GIF-images.html)
