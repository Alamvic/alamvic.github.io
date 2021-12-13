## Ranger: Automatic VM Testing

Modern language implementations using Virtual Machines feature diverse execution engines such as byte-code interpreters and machine-code dynamic translators, a.k.a. JIT compilers.
Validating such engines requires not only validating each in isolation, but also that they are functionally equivalent.
Tests should be duplicated for each execution engine exercising the same execution paths on each of them. 

In this project we explore automated testing approaches for virtual machines.
This project explores topics such as symbolic execution, fuzzing and differential testing to generate virtual machine tests.