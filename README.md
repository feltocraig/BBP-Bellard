BBP-Bellard
===========

An implementation of [BBP](http://en.wikipedia.org/wiki/Bailey%E2%80%93Borwein%E2%80%93Plouffe_formula) through [Bellard's formula](http://bellard.org/pi/). 
This program extracts the nth digit of Pi without calculating the digits before it.
It will print out the nth number followed by the next 9 numbers in base 10. 

Example: _1 - 141592653_ 

Example: _990 - 921642019_ 

The digit-extraction algorithm uses Bellard's modifications to get a running time of _O(n^2)_. Note large numbers.

##Algorithm Used
![Algorithm](http://i.imgur.com/6wuHrsF.png)
