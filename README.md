sassUtils
=========

Useful sass mixins for easy project use. Includes utils and functions from various sources in one place for quick project startup.

extended_normalize.scss
-----------------------

Document resetting and style consistency use one of the following
- reset.scss : A full reset of all styles
- normalize.scss : cross browser consistency
- extended_normalize.scss : above plus minor resets

Other utils include:
- Basic media queries
- Basic positioning and clears
- clearfix mixin
- rem units and fallback mixin


Example
-------

Import into your scss file as you normally would

File: style.scss

@import 'extended_normalize.scss'; // Extended version of normalize.css
@import 'utils.scss';
@include basicPositioningClasses;




Credits / Sources
-----------------

A big thanks to the hard work of all the people who have created the following sources that have been used. Other sources will be credited as the original sources are found.

normalize.css : 			https://github.com/necolas/normalize.css
Reset : 					http://meyerweb.com/eric/tools/css/reset/
rem mixin :					unknown - source needed
bulletproof clearfix :	 	https://github.com/adamstac/grid-coordinates/blob/master/stylesheets/modules/_bulletproof-clearfix.sass