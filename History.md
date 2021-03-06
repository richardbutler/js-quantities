1.4.0 / 2014-04-10
------------------

* Directly convert array of values when using swiftConverter
* Add support for bushel units

1.3.0 / 2014-03-05
------------------

* Add Qty#format and accept custom formatters
* Allow to call Qty() without new to create Qty instances (Qty could be used
  both as a constructor or as a factory)
* Qty#toString only supports to be passed output units as single parameter.
  Former parameters are now deprecated but still supported to not introduce
  a breaking change
* Add mc as alternate definition for prefix "micro"
* Throw error with mmm as unit
* Add rounding optimization

1.2.0 / 2013-12-17
------------------

* Throw QtyError instead of plain string
* Cache conversion results from Qty#to instead of Qty#toString
* Fix point and pica unit definitions
* Fix error when initializing a quantity with an empty string

1.1.2 / 2013-11-04
------------------

* Fix rounding issue when converting 1 cm3 to mm3
* Do some code cleaning (it should not break public API)

1.1.1 / 2013-10-01
------------------

* Fix Qty#toPrec() returning wrong result with some precision

1.1.0 / 2013-09-20
------------------

* Add array converting method
* Major speedup by means of some optimizations and refactoring

1.0.0 / 2013-07-30
------------------

* First stable version
