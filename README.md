# Factory Design Pattern

In class-based programming, the factory method pattern is a creational pattern that uses factory methods to deal with the problem of creating objects without having to specify the exact class of the object that will be created. This is done by creating objects by calling a factory method—either specified in an interface and implemented by child classes, or implemented in a base class and optionally overridden by derived classes—rather than by calling a constructor.

Overview
The Factory Method design pattern is one of the twenty-three well-known design patterns that describe how to solve recurring design problems to design flexible and reusable object-oriented software, that is, objects that are easier to implement, change, test, and reuse.

The Factory Method design pattern solves problems like:
  - How can an object be created so that subclasses can redefine which class to instantiate?
  - How can a class defer instantiation to subclasses?
  

The Factory Method design pattern describes how to solve such problems:

  - Define a separate operation (factory method) for creating an object.
  - Create an object by calling a factory method.
This enables writing of subclasses to change the way an object is created (to redefine which class to instantiate).
