# SOLID Principles
## Single Responsibility Principle
Every code unit should have precisily single responsibility or the code unit should be handling the single functionality.

The SRP is violated in the case of having multiple if-else statements, monster methods and different utilities(date,string,etc) combined in a single file.

## Open for Extension and Closed for Modification 
The code unit should be written in such a way that it should be easy to add the new features to the existing one but it should not modify the existing features as we can avoid regression testing.


## Liskov's Substition Principle
Any object of the super-class type, if replaced with the object of the sub-class type it should not drastically change the behaviour.


## Interface Segregation Principle 
Interface should be as light as possible that is as less methods may be even single method. It should only contain the methods of specific functionality. Example File Interface can contain open() and close() methods as both are related.



## Dependency Inversion
No two concrete class should directly depend on each other as it results in tight coupling. It should be loosely coupled with the help of interfaces and abstract classes. This will result in easier extensibility of the codebase.

# Design Patterns
Design Patterns are the well established solutions that can be used for the commonly occuring problems to make the codebase readable, extensible and maintainable.

