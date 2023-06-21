# Object Oriented Design

**Procedure-oriented programming:** programs are designed as blocks of statements to manipulate data

**Object-oriented programming (OOP):** it organizes the program to combine *data* and *functionality*, wraps it inside an object



## 1. Basic Concepts

**Objects:** represent a real-world entity, the basic building block of OOP

**Class:** the prototype/blueprint of an object. It is a template definition of the *attributes* and *methods* of an object

**Attributes:** state/property of the object

**Methods:** functions that represent the behavior of the object

### Four Principles of OOP

+ **Encapsulation:** binding the data together, and hiding it from the outside world
    * internal states are private that other objects cannot access directly
    * internal states are accessible only through a set of public methods
    * advantages
        * easy to modify/maintain the class
        * ale to control the visibility of data member
        * flexible to make data member read-only or write-only

+ **Abstraction:** hiding internal implementation details of objects, and only revealing operations that are relevant to other objects
    * focus on simplification, a natural extension of encapsulation which focuses on accessibility
    * hide implementation using interface and abstract class
    * advantages
        * reducing the complexity of system into manageable smaller modules
        * making code extensible and reusable

+ **Inheritance:** creating new classes from existing ones
    * advantages
      * reusing code from base class
      * ensuring the code changes are localized and consistent
      * able to extend the base class as per the requirements
      * hiding data from base class

+ **Polymorphism:** an object can take different forms, respond differently to the same message depending on the context
  + Dynamic polymorphism
    + method overriding
  + Static polymorphism
    + method overloading
    + operator overloading



## 2. OO Analysis and Design

## General Process

1. identify the *objects* in the system
2. define *relationships/interactions* between objects
3. establish the *interface* of each object
4. make a design, which can be converted to executables using OOP

### General Guidelines

+ separate out parts of code that are reusable
+ always code to an interface and not against a concrete implementation
+ encapsulate behaviors as much as possible
+ favor composition over inheritance
  + Inheritance can result in explosion of classes and also sometimes the base class is fitted with new functionality that isn't applicable to some of its derived classes
+ interacting components within a system should be as loosely coupled as possible
+ ideally, class design should inhibit modification and encourage extension

### SOLID Design Principles for OOD

+ Single Responsibility Principle (SRP)
  + A class/component should have only one functionality

+ Open Closed Principle (OCP)
  + Software should be open for extension (easy to add new code) but closed for modification (change code core)

+ Liskov Substitution Principle (LSP)
  + A derived object should behave the same way as the base object
  + apply to abstraction like inheritance and polymorphism
  + thus, multiple specific interfaces are better than one general purpose interface

+ Interface Segregation Principle (ISP)
  + An interface should not have methods that it would not use and require

+ Dependency Inversion Principle (DIP)
  + A high-level module should not depend on low-level module, but rather both should depend on abstraction
  + thus, implement an interface whenever possible

### Two Additional Principles

+ Least Knowledge Principle / Law of Demeter
  + each unit should have only limited knowledge about other units that are closely related
  + each unit should only interact with its immediate friends
  + don't interact with strangers

+ Composite/Aggregate Reuse Principle
  + try to use composite/aggregate instead of inheriting to achieve the purpose of reuse
    + use some existing objects in a new object to make it a part of the new object
    + the new object reuses existing functions by delegating to these objects held internally



## 3. UML

Unified Modeling Language (UML) is way of visualizing and documenting a software system using a collection of diagrams.

+ Structural UML diagrams
    * [Class diagram](./class-diagram.md)
    * Object diagram
    * Package diagram
    * Component diagram
    * Composite structure diagram
    * Deployment diagram
    * Profile diagram

+ Behavioral UML diagrams
    * [Use case diagram](./use-case-diagram.md)
    * [Activity diagram](./activity-diagram.md)
    * [Sequence diagram](./sequence-diagram.md)
    * State diagram
    * Communication diagram
    * Interaction overview diagram
    * Timing diagram
