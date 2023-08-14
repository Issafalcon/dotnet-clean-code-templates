# .NET Clean Code Templates

A set of fully featured .NET templates to quickly implement boilerplate code for a clean architecture setup. 

Basic example code is provided so the applications are buildable and runnable, and it is easier to see how everything fits together.

The applications, by default, all use an Onion style / Hexagonal Architecture, even when the template is for a simple CRUD application. This is because, even when building a straightforward CRUD application, 99% of the time, it will end up turning into something more complex, requiring some more advanced business logic. At least in some parts of domain.
