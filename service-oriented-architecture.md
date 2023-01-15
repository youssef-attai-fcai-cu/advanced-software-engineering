# Service-Oriented Architecture

## What is a service?

A service is a functionality exposed by a system via an interface to be used by other processes/service requestors.

## What is a web service?

A web service is a service (exactly like explained above) that is exposed via an interface available through the internet.
So it can be accessed through web technologies.


Service-oriented architecture is all about desiging a system that makes use of different services, rather than 
having it all in a large software suite.

In SOA, since the software becomes very dependent on the interent, two main non-functional requirements become
more important than ever:

- Response time, and
- Availability

## SOAP vs ReST APIs

SOAP is a protocol, the way it works is simple.

Requests and reponeses are passed between the client and the server in XML files. The protocol is as follows:

- The client makes a POST request with the XML,
specifying what function they are trying to invoke.
- The server handles the request, invokes the function and responds with XML.


ReST however is an architectural style, not a protocol.

The server is designed in a way, such that every function
is exposed via a URL, that when requested, a certain function is invoked.

SOAP is focused more on the functions, while ReST is focused more on the resources.

For example:

To expose the functionality of creating a user account, SOAP would have a "CreateUser" function (that will be specified in the XML body), While a ReST API will expose a URL like https://api.dummy.com/user that when a POST request is sent to, user creation will happen.
