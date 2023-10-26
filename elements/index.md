> [home](../)

![banner](/cpp/photos/banner.png)

## Elements
> Education is what remains after one has forgotten what one learns in school.    
> **Albert Einstein**

A computer, at its very essence, is able take inputs in pre-determined formats and perform pre-determined operations in a consistent and predictable fashion.  It would perform exactly the same in exactly the same context.  More interestingly, when you have more than one identical computers they also will also behave exactly the same in exactly the same context.

The more general term for the inputs is data and the general term for the operations is function.  A given computer has hardware that supports a set of given data types (integers, floats, etc.) and there are sets of operations for each such data type supported.  It is possible to arbitrarily clump together data elements and move them together as a group (a struct), but operations are per data element.  It is also possible to arbitrarily clump together operations as a group (a function) and have the operations executed in sequence.

The heart of C is providing keywords for data types and notation for the operations and allowing for the combination of data types and combination of operations.  C also provides niceties such as enums and macros and complete the machine abstraction.  A struct was the most flexible way of defining new types and functions were stand-alone.  This facilitated procedural programming.

C++ changed the game by making it possible to define a new user type together with the functions that operated on it.  This was achieved with the concept of the class, borrowed by Stroustrup from Simula.  Object-oriented programming was the result.

The realization that you need to call the same function on different types — sort() for example — resulted in generic programming techniques being incorporated.  You wrote one definition that operated on a generic type T and the compiler generated the individual implementations for each of the specific types.

This is the essential ideological core of C++.  The rest is design — syntactical choices with a keen eye on completeness and performance.
