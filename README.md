hint.js
=======

hint.js is a command line tool wrapping JSHint.

Dependecies
-----------

To use hint.js you need to have [node.js][node] installed.

Usage
-----

    hint.js file1 file2 file3 ...

or

    node hint.js file1 file2 file3 ...

You can set your own options and globals by setting the keys on the 'options' and 'globals' objects in hint.js.

Attribution
-----------

Based heavily upon [Guy Halford-Thompson][guyht]'s [blog entry][cachme].

[node]: http://nodejs.org/
[cachme]: http://www.cach.me/blog/2011/06/jshint-and-nodejs/
[guyht]: https://github.com/guyht
