# pmca
Python Module Complexity Analyzer, lists and locates object data fields of a module and roughly crudely estimates the complexity of object methods

Have you ever wasted your time and mood going through some module and boring your eyes after just few method listings? This tool
is made to produce a simple analysis of methods and data fields so that you can skip the myriad of short helper methods and jump
right to the heavy-lifting method you need to study. Method details such as 

* length in code lines,
* a number of for/while loops (complexity +1) and recursive calls (complexity + inf , leave recursion to fortran) and even
* (advanced) the most probable type of its return value (=a major pain in weakly-typed Python) .

Object fields definitions are often all over the code, so cataloguing them and gathering information about their object type and possible object methods simply needs to be done. Recursive analysis of the field objects might have to be done.


Licensed under LGPLV3 -- commercial reuse allowed.
