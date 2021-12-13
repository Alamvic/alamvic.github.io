##Jit Compilation

### Dynamic Compilation, PICs and Speculative Optimisations

#### Efficient implementation of the smalltalk-80 system

One of the foundational works on how VMs are built today: dynamic translation to machine code, inline caches.

https://www.semanticscholar.org/paper/Efficient-implementation-of-the-smalltalk-80-system-Deutsch-Schiffman/2f4002755b309cdb91e18116b8028005497d8400

#### Optimizing Dynamically-Typed Object-Oriented Languages with Polymorphic Inline Caches

Another foundational article that has a lot of repercutions nowadays, presenting how inline caches are extended to manage polymorphic call-sites.

https://bibliography.selflanguage.org/_static/pics.pdf

#### Optimizing Dynamically-Dispatched Calls with Run-Time Type Feedback

Polymorphic inline caches track types found at run-time! Runtime compilers do speculative inlinings, aggressive optimisations, and modern VMs are born! 

https://bibliography.selflanguage.org/_static/type-feedback.pdf