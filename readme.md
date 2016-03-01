# jQuery sendkeys

This is an NPM and browserify compatible version of [jQuery.sendkeys](http://bililite.com/blog/2011/01/23/improved-sendkeys/). It's very useful for testing HTML pages by simulating key presses on text inputs and textareas.

# how to use?

    var $ = require('jquery');
    require('jquery-sendkeys');

    $('input.search').sendkeys('something');

See full documentation [here](http://bililite.com/blog/2011/01/23/improved-sendkeys/). Original repo here: [https://github.com/dwachss/bililiteRange](https://github.com/dwachss/bililiteRange), v4 taken from commit [254894b971a73c80e12fab9be416c8ad1c689452](https://github.com/dwachss/bililiteRange/commit/254894b971a73c80e12fab9be416c8ad1c689452)
