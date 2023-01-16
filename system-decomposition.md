## Typical design trade-offs

### Functionality VS Usability

The more the functions a system can provide, the less usable it is going to be.
Too much functionality can be overwhelming. At the same time, if the
functionality of a system is limited and well defined, then it is pretty usable
because it has well defind use cases.

### Cost VS Robustness

A robust system is a system that can handle errors and invalid user inputs.  To
make one it is going to cost you time and effort, and possibly even money.

### Efficiency VS Portability

To make an efficient system, you are probably going to rely more on the
platform's APIs since they are usually the most optimal solution
(performance-wise), which is going to make your system not so portable, you
will have to change all the calls to the current platform APIs to the new
platform's APIs.

## Services and subsystem interfaces

The term API should not be used during system design and object design, but
only during implementation. That is the difference between an API in a specific
programming language, and a subsystem interface, that just defines a contract.

The subsystem interface object should define/describe all the
functions/services that the subsystem provides.

## Coupling and coherence of subsystems

Coherence is a way of measuring the dependency among classes of the same
subsystem, while coupling is a way of measuring dependency among subsystems.

High coherence in a subsystem means that it's classes together perform similar
related tasks, and that they are related to each other via differenet
associations.

Low coherence in a subsystem means that it contains lots of miscallaneous
classes and auxiliary classes with almost no meaningful associations.

High coupling between subsystems means that a change in one subsystem can cause
a huge impact on the dependant subsystems.

Low coupling between subsystems means that one can change without affecting the others.
