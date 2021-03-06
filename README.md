# px-helpers-design

The Predix UI Helpers module consists of a variety of helper classes to use where needed in your Predix app.

## Dependencies

The `px-helpers-design` module depends on one other Px module and one other inuitcss module:

* [tools.responsive](https://github.com/inuitcss/tools.responsive)
* [px-functions-design](https://github.com/PredixDev/px-functions-design)

## Upstream dependency

The `px-helpers-design` module is also an upstream dependency in this meta kit:

* [px-starter-kit-design](https://github.com/PredixDev/px-starter-kit-design)

## Installation

Install this module and its dependencies using bower:

    bower install --save https://github.com/PredixDev/px-helpers-design.git

Once installed, `@import` into your project's Sass file in its Generic layer:

    @import "px-helpers-design/_generic.helpers.scss";

## Usage

Only use a helper class if an element/component doesn’t already have a class to which you could apply this styling, e.g. if you need to float `.main-nav` left then add `float:left;` to that ruleset as opposed to adding the `.float--left` class to the markup.

A lot of these classes carry `!important` as you will always want them to win out over other selectors.

View the full API [here](http://predixdev.github.io/px-helpers-design/).
