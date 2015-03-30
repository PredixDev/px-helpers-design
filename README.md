# Helpers

A series of helper classes to use arbitrarily in Predix Experience.

## Dependencies

Px's Helpers module depends on three other Px and inuitcss modules:

* [tools.responsive](https://github.com/inuitcss/tools.responsive)
* [px-functions-design](https://github.sw.ge.com/PXd/px-functions-design)

## Installation

Install this module and its dependencies using bower:

    bower install --save https://github.sw.ge.com/PXd/px-helpers-design.git

Once installed, `@import` into your project's Sass file in its Generic layer:

    @import "../px-helpers-design/generic.helpers";

See [px-getting-started](https://github.sw.ge.com/PXd/px-getting-started#a-note-about-relative-import-paths) for an explanation of the `../`

## Import once

All rulesets are wrapped in the following `@if` statement:

    @if import-once('generic.helpers') { ... }

## Usage

Only use a helper class if an element/component doesn’t already have a class to which you could apply this styling, e.g. if you need to float `.main-nav` left then add `float:left;` to that ruleset as opposed to adding the `.float--left` class to the markup.

A lot of these classes carry `!important` as you will always want them to win out over other selectors.
