# Bashforth
This Forth interpreter, entirely written as bash script, is an F³ (Fully Functional Forth), albeit a tad slow.
Some would call it "sluggish". As rough indication, an ARM SBC which I'm running Bashforth on takes about 15 second
for an empty loop of 100,000 iterations. It has built-in _doc_ and _see_ facilities, simplifying exploration of Bashforth.
Bashforth lacks floating point support and vocabularies, but comes with essentials like defining word builder,
exception handling. It also provides an extra string stack, along with a set of words, operating on string stack. 
