Roman Numeral Kata
==================
Convert Arabic numbers (1, 5, 100, etc.) into Roman Numerals (I, V, C, etc.).

Rules that numerals follow which should be observed.
----------------------------------------------------
The Romans wrote their numbers using letters; specifically the letters 'I'
meaning '1', 'V' meaning '5', 'X' meaning '10', 'L' meaning '50', 'C' meaning
'100', 'D' meaning '500', and 'M' meaning '1000'. There were certain 

The symbols 'I', 'X', 'C', and 'M' can be repeated at most 3 times in a row. The
symbols 'V', 'L', and 'D' can never be repeated. The '1' symbols ('I', 'X', and
'C') can only be subtracted from the 2 next highest values ('IV' and 'IX', 'XL'
and 'XC', 'CD' and 'CM'). Only one subtraction can be made per numeral ('XC' is
allowed, 'XXC' is not). The '5' symbols ('V', 'L', and 'D') can never be
subtracted.

TL,DR: Larger numbers like 3999 should return "MMMCMXCIX" rather than other values,
such as MMMXMIX, MMMVMIV or MMMIM.


Number to Roman Numeral translation
-----------------------------------
- 1 => I
- 2 => II
- 3 => III
- 4 => IV
- 5 => V
- 6 => VI
- 7 => VII
- 8 => VIII
- 9 => IX
- 10 => X
- 11 => XI
- 12 => XII
- 15 => XV
- 20 => XX
- 30 => XXX
- 40 => XL
- 41 => XLI
- 44 => XLIV
- 50 => L
- 100 => C
- 500 => D
- 900 => CM
- 1000 => M
