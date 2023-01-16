# Quality Attributes

## Types of requirements

### Functional requirements

e.g. The system should allow <User> to do <Something>

Functional requirements should be independant of implementation.

### Non-functional requirements

e.g. The respose time should be X.

Not directly related to functional requirements, they are more about how to
achieve them.

Fucntional requirements are stated as actions.

Non-functional requirements are stated as constraints or negative assertions.

### Constraints (pseudorequirements)

Imposed by the client or the environment.

e.g. Implementation must be in Java.

## FURPS+

**F** for functional requirements

The rest are all non-functional, quality attributes.

**U** for usability

**R** for reliability

**P** for performance

**S** for supportability

#### Note about scalability in the **P**erformance quality attribute

Scalability is all about how the system behaves when the size of the problem it solves grows.

Things that can grow in size:

- Request load
- Data size
- User base (Deployment)

Scaling-up means running the application instance on a multiprocessor machine.

Scaling-out means replicating the applcaition on multiple machines.

#### Note about security

Non-repudiation is basically a way the sender knowing that the message is
delivered successfully to the receiver, and a way for the receiver to verify
the identity of the sender.
