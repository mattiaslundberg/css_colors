Changelog
=========

Version 0.2.2
-------------

Fixes:

* Remove compiler warnings for unused variables. Thanks to @rodrigues.

  
Version 0.2.1
-------------

Bug fixes:

* Correctly output RGB colors with values between 0x0A and 0x0F.
  They were missing the leading zero. Thanks to @andrebnf.

Version 0.2.0
-------------

New features:

* Custom Ecto type
* Make parser use tagged return values

Backward incompatible changes:

* `CssColors.parse/1` now returns tagged values. `CssColors.parse!/1`
  implements the old behaviour (returning the bar value or crash).

Version 0.1.1
-------------
Minor fix in documentation

Version 0.1.0
-------------
Initial beta release


