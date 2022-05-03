# Software Design Pattern

Tech problems sometimes have well-defined solutions, they are flexible, modular and more understandable. Design patterns are abstracted solutions which ignore the technical details.

![Design Patter Relationships](./res/design-pattern-relationships.png)

### Types of Design Patterns

+ [Creational](./creational/README.md)
    * [**Builder**](./creational/builder-pattern.md)
    * [**Prototype**](./creational/prototype-pattern.md)
    * [**Singleton**](./creational/singleton-pattern.md)
    * [**Factory**](./creational/factory-pattern.md)
    * [**Abstract Factory**](./creational/abstract-factory-pattern.md)

+ [Structural](./structural/README.md)
    * [Adapter](./structural/adapter-pattern.md)
    * [Bridge](./structural/bridge-pattern.md)
    * [Composite](./structural/composite-pattern.md)
    * [**Decorator**](./structural/decorator-pattern.md)
    * [Facade](./structural/facade-pattern.md)
    * [Flyweight](./structural/flyweight-pattern.md)
    * [**Proxy**](./structural/proxy-pattern.md)

+ [Behavioral](./behavioral/README.md)
    * [Interpreter](./behavioral/interpreter-pattern.md)
    * [Template](./behavioral/template-pattern.md)
    * [Chain of Responsibility](./behavioral/chain-of-responsibility-pattern.md)
    * [Command](./behavioral/command-pattern.md)
    * [**Iterator**](./behavioral/iterator-pattern.md)
    * [Mediator](./behavioral/mediator-pattern.md)
    * [Memento](./behavioral/memento-pattern.md)
    * [**Observer**](./behavioral/observer-pattern.md)
    * State
    * [Strategy](./behavioral/strategy-pattern.md)
    * [**Visitor**](./behavioral/visitor-pattern.md)

### General Guidelines for OOD

+ Separate out parts of code that are reusable

+ Always code to an interface and not against a concrete implementation

+ Encapsulate behaviors as much as possible

+ Favor composition over inheritance. *Inheritance can result in explosion of classes and also sometimes the base class is fitted with new functionality that isn't applicable to some of its derived classes*

+ Interacting components within a system should be as loosely coupled as possible

+ Ideally, class design should inhibit modification and encourage extension

+ Using patterns in daily work, allows exchanging entire implementation concepts with other developers via shared pattern vocabulary

# Reference

[1] "Software Design Pattern: Best Practices for Software Developer" by educative.io

[2] Design Patterns by refactoring.guru
