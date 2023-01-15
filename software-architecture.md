# Software Architecture

Software architecture is a subset of software design.
However, it is not concerned with design details,
but with failure risks.

So, if a design desicion can be traced back to a failure
risk (i.e. the decision was made with the goal to prevent
a failure) then it is an architectural decision.

Different architecture decisions lead to the gain of
different quality attributes as well suffering
different drawbacks.

An architect will pay more attention to the qualities
gained and the drawbacks suffered arising from architecture choices/decisions. 

Something a software architect would say is:

Because **in this system**,
_Quality atrribute A_ is more important
than _Quality atrribute B_ , 
we choose  _Techincal design/architecture option_, 
accepting _Drawback_.

For example:

Because **when it comes to making phone calls**,
_power outage tolerance_ is more important
than _scalablility_ , 
we choose  _using landline phones_, 
accepting _a higher cost of adding new subscribers_.

The architecture of a software system is just a bunch of models used to reason about the system, focusing on the
system failures. These models consists of the different software elements, and the relations among them, and their properties.

