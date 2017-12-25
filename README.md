# Drupal 8 Marionette JS

Provides the [Marionette J](https://marionettejs.com/) library to modules that require it.

Marionette simplifies your Backbone application code with robust views and architecture solutions.

## Why

[Backbone JS](http://backbonejs.org/) is an excellent javascript that is bundled with Drupal 8. It
is used by core and contrib modules, the most notable is probably the core toolbar module.

Marionete uses Backbones great pricibles and builds on that to provide cleaner and easier to write code.

Read all about what it does [here](https://marionettejs.com/)

## Note

This module does nothing by itself, it requires other modules to include it as a dependecy.

## Install

* Download Marionette from here: https://marionettejs.com/downloads/backbone.marionette.zip
* Extract the zip in the `/libraries` folder in the root of the Drupal site. The path should look like `/libraries/backbone.marionette/backbone.marionette.min.js`
* Install and enable this module

## Usage

Simply add the `marionettejs/marionettejs` library as a dependency in your module/theme:

```
  dependencies:
    - marionettejs/marionettejs
```

## Versions

The version of BackboneJS is now a bit dated and has some issues with the latest marionette. Due to
this, this module includes

## Author (of the drupal module)

Jeremy Graham
