# Bashforth
This Forth interpreter, entirely written as bash script, is a F³ (Fully Functional Forth), albeit a tad slow.
Some would call it "sluggish". As rough indication, an ARM SBC which I'm running Bashforth on takes about 15 second
for an empty loop of 100,000 iterations. It has built-in _doc_ and _see_ facilities, simplifying exploration of Bashforth.
Bashforth lacks floating point support and vocabularies, but comes with essentials like defining word builder,
exception handling. It also provides an extra string stack, along with a set of words, operating on string stack.

Those interested in bashforth might like [yoda](https://github.com/Bushmills/yoda) which does away with the virtual machine
and compiles directly to bash functions. As consequence can a substantial performance difference be realised (yoda is faster by a factor of somewhere between 30 and 50 times).  
At this point yoda has progressed enough that I can say that now yoda is the better bashforth.


