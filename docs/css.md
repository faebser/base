# CSS
Basic resets, fundamental styling for common HTML elements and a powerful grid system.

* * *

## Overview
Base includes a precompiled stylesheet which includes all the core ingredients to get you started, from typography to the mobile-first grid system.

** So what is exactly in the core ingredients?! ** <br>
The super slim, sexy CSS includes the following:
* [Basic resets](#basic-resets)
* [Micro clearfix](#micro-clearfix)
* [Typography](#typography)
* [Lists](#lists)
* [Blockquotes](#blockquotes)
* [Tables](#tables)
* [Code and pre blocks](#code-and-pre-blocks)
* [Forms and buttons](#forms-and-buttons)
* [Grid](#grid)
* [General helpers](#general-helpers)
* [Mixins](#mixins)

## Basic resets
The basic resets include a customised version of <code>normalise.css</code> to ensure all elements behave correctly across all browsers supported.

## Micro clearfix
The clearfix hack, by [@necolas](http://nicolasgallagher.com/micro-clearfix-hack/), is a quick and easy way to contain floats without resorting to using presentational markup.

## Typography
A basic set of styles are applied to general body copy, headings (h1 - h6) and links. Typography can easily be modified by tweaking the appropriate variables such as: @base-font-family, @base-font-size, @base-line-height and @link-color. These variables can be found within <code>_variables.less</code> or <code>_variables.sass</code>.

The base font size is set at 16 pixels (using rem units) and the default line height is set to 22 pixels (using rem units).


## Lists
Styles for unordered lists, ordered lists and definition lists.

## Blockquotes
Basic styling for highlighting testimonials or quotes.

## Tables
There are 2 sets of styles for tables – stripped pattern and line spearated for presenting your data in the most simplistic manner.

## Code and pre blocks
Core styling for code and pre block elements.

## Forms and buttons
Includes minimal styles for labels, input fields, select boxes and form buttons.

## Grid
A powerful and responsive grid to easily create your page layout.

Make sure to check out the [grid's full documentation](grid.md).


## General helpers
A set of utility helpers which can be used on the fly to save you tons of time.

## Mixins
A set of helpful mixins to easily create SVG fallbacks, apply border radius, opacity, animations and much more!

Check out the [full list of Mixins](mixins.md) currently available.
