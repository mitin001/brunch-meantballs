# Long polling chat

This is a modern long polling chat web application built with [Brunch](http://brunch.io) (based off of [brunch/es6](https://github.com/brunch/with-es6)) and Angular.js.

## Getting started

* Install (if you don't have them):
    * [Node.js](http://nodejs.org): `brew install node` on OS X
    * [Brunch](http://brunch.io): `npm install -g brunch`
    * Brunch plugins and app dependencies: `npm install`
* Run:
    * `npm start` - Runs `brunch watch` (to watch & rebuild your files)
    * `npm run prod` - builds minified project for production
* Learn:
    * `public/` dir is fully auto-generated. Write your code in `app/` dir.
    * Place static files you want to be copied from `app/assets/` to `public/`.
    * [Brunch site](http://brunch.io), [Getting started guide](https://github.com/brunch/brunch-guide#readme)

## ES7

To use proposed JS features not included into ES6, do this:

* `npm install --save-dev babel-preset-stage-0`
* in `brunch-config.js`, add the preset: `presets: ['es2015', 'stage-0']`
