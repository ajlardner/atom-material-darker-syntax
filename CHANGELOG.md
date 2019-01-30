## 0.1.0 - Initial Release
* Created for HTML/CSS, JS, and Ruby but all languages supported

## 0.2.0 - Release 2
* Fixed issue where color CSS property values would be highlighted as constants

## 1.0.0 - Major Release 1 (Release 3)
* Added styles for YAML in yaml.less
* Broke out CSS styles to simplify some styles/make more CSS specific highlighting
  * Fixed issue caused in `0.2.0` with W3C Standard CSS colors
* Fixed issue causing JSON keys to be highlighted as strings
* Removed all highlighting from JSON Values
* Fixed issue causing numeric operators/units (%, #) to be highlighted as constants

* Removed coloring from JS object properties/variables
  * Added coloring to keys in object declarations
* Significant edits to markup highlighting
* Added highlighting to RegExp in strings
* Slight changes to color palette (function parameters, strings, symbols)
* Distinguished `HEREDOC` strings from quoted strings (ruby)
* Added highlighting to punctuation in string interpolation (ruby)
* Fixed some CSS that was too specific and confusing to override

## 1.1.0 - Release 4
* Fixed dumb mistake I made with `apm publish`. Don't @ me

## 1.1.1 - Patch 4.1
* Fixed issues with CSS styles not applying, more organization of styles
* Broke out JSON styles for organization

*TODO 1.2.0: Add markdown styles, improve css styles, fix any issues noticed
