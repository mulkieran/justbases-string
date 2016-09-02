justbases-string
================

Purpose
-------
A small library for generating a human readable string value from a number
with an arbitrary base. The number is represented by five elements:

* a base
  the base of the number, must be an integer greater than 1.

* a sign
  -1, 1, or 0 as appropriate

* an integer part
  a list of non-negative ints, where each element is less than the base value

* a non repeating fractional part
  a list of non-negative ints, where each element is less than the base value

* a repeating fractional part
  a list of non-negative ints, where each element is less than the base value

