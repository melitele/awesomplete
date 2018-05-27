
2.0.1 / 2018-05-26
==================

 * container function to generate container element

2.0.0 / 2018-05-26
==================

 * limit package content
 * rename package to @melitele/awesomplete
 * Autofocus support (#17138)
 * Added an installation section (#17129)
 * Ensure global Awesomplete on self is defined before any possible call to init(). (#17131)
 * Fix undefined error in evaluate function (#17128)
 * fix: allow selection on mobile ios (#17006)
 * Fix for #17113 (#17118)
 * Fix mixed content Github buttons (#17072)
 * trying to meet a11y criteria (#17068)

# 1.1.1 (2016-06-25)

## Fixes

* Improved docs
* Emit close reason with `awesomplete-close` events ([8c0ff62](https://github.com/LeaVerou/awesomplete/commit/8c0ff6225c96af2f5f3b7312d7ba7b69f71be575)). See [Events](http://leaverou.github.io/awesomplete/#events).
* Fire `awesomplete-close` event only if open ([2cef2c2](https://github.com/LeaVerou/awesomplete/commit/2cef2c28a6f74ee5c0b294d2c3c7d2bad72bd466))

# 1.1.0 (2016-03-16)

## Features

* Separate label/value for each suggestion on the list 
* New `suggestions` property with suggestion items only (to be rendered in completer)
* New `data` method to convert/change suggestion item data and corresponding `Awesomplete.DATA`
* The `item` and `replace` methods have a corresponding `Awesomplete.ITEM` and `Awesomplete.REPLACE` defaults now
* Ajax and Combobox examples
* Nearly 100% test coverage with Travis CI and Code Climate

# 1.0.0 (2015-04-23)

## First release
