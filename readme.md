# jQuery sendkeys

This is an NPM and browserify compatible version of [jQuery.sendkeys](http://bililite.com/blog/2011/01/23/improved-sendkeys/). It's very useful for testing HTML pages by simulating key presses on text inputs and textareas.

# how to use?

    var $ = require('jquery');
    require('jquery-sendkeys');

    $('input.search').sendkeys('something');

See full documentation [here](http://bililite.com/blog/2011/01/23/improved-sendkeys/).
