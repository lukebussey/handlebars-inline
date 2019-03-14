# handlebars-inline

A simple Handlebars helper for inlining the contents of files.

## Install

Install with [npm](https://www.npmjs.com/):

    $ npm install --save handlebars-inline

## Registering the helper

    const Handlebars = require('handlebars')
    require('handlebars-inline').register(Handlebars)

## Usage

    {{{inline 'path/to/file.svg'}}}

Note: Handlebars helper output is HTML escaped by default. To skip escaping use the "triple-stash": `{{{`
