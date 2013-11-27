# Landing page generator

Fork of default Yeoman generator, with optional landing page features such as social buttons and email signup.

## Features

* CSS Autoprefixing (new)
* Built-in preview server with LiveReload
* Automagically compile CoffeeScript & Compass
* Automagically lint your scripts
* Automagically wire up your Bower components with [bower-install](https://github.com/stephenplusplus/grunt-bower-install).
* Awesome Image Optimization (via OptiPNG, pngquant, jpegtran and gifsicle)
* Mocha Unit Testing with PhantomJS
* Optional - Twitter Bootstrap for SASS
* Optional - Leaner Modernizr builds (new)

For more information on what `generator-webapp` can do for you, take a look at the [Grunt tasks](https://github.com/yeoman/generator-webapp/blob/master/app/templates/_package.json) used in our `package.json`.

## Getting Started

- Make sure you have [yo](https://github.com/yeoman/yo) installed: `npm install -g yo`
- Install the generator: `npm install -g generator-landing-page`
- Run: `yo landing-page`
- Run `grunt` for building and `grunt serve` for preview


## Options

* `--skip-install`

  Skips the automatic execution of `bower` and `npm` after scaffolding has finished.

* `--test-framework=<framework>`

  Defaults to `mocha`. Can be switched for another supported testing framework like `jasmine`.

* `--coffee`

  Add support for [CoffeeScript](http://coffeescript.org/).


