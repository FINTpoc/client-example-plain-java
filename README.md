# client-example-plain-java
FINT Example Client using plain Java

This is an example client demonstrating how to access FINT APIs using Java and Google's libraries for OAuth 2.0 and HTTP, 
and Jackson for parsing the resulting JSON.

## OAuth Configuration

The properties for OAuth configuration is read from Java System properties,
or the file `oauth.properties` if it exists.

## HATEOAS JSON handling

Handling of JSON and the HATEOAS structure is manual, and the example
contains code for getting the data as text, `GenericJson`, or marshalled
into custom data objects.
