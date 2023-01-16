# Architectural Views

## Module structures

### Decomposition structure

Decomposes a system into units of implementation.

Describes the organization of code as modules and sub-modules.

It shows how system responsibilities are divided among the modules.

##### Side notes

Module can not be a parent and a child to another module at the same time.

e.g. If A contains B, B can not contain A.

In other words, no loops are allowed in the system decomposition diagram.

## Component-connector structures

The units are compoenents, and the connectors just their communication
mechanisims and interfaces.

This opens the door for thinking about parallelism and what components
can be running/doing their jobs simulaneously.

## Allocation structures

They are all about how the system will relate to the non-software structures
in the environment (like the hardware, the filesystem, the network, stuff that are
important for the software to operate but they themselves are not software).

It describes the mapping between the software architecture and the environment.

e.g. A software element is mapped to/allocated to an environmental element.
(annotated with <<deploy>> in the deployment diagram)

The software element can be either from the module view or the component-connector view

i.e. the software element can be a static module or a dynamic component.

##### Notes about the deployment diagram

Artifacts (annotated with <<artifact>>) represent physical
implementation units, such as executable files, libraries,
 software components, documents, and databases.

