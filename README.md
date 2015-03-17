Demo NPM
========

A small library providing utility methods to `escape` and `unescape` HTML
entities

## Installation
    npm install --save ronfedemo

## Usage
    var demo = require('ronfedemo'),
        escape = demo.escape,
        unescape = demo.unescape;

    var html = '<h1>Hello World</h1>',
        escaped = escape(html),
        unescaped = unescape(html);

    console.log('html', html, 'escaped', escaped, 'unescaped', unescaped);

## Tests
    npm test

## Release History

* 0.1.0 Initial release
