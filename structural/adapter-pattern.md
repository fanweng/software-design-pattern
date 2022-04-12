# Adapter Design Pattern

> Adapter pattern allows incompatible classes to work together by converting the interface of one class into another expected by the clients.

## Problem

## Solution

#### Object Adapter

![Object Adapter Structure](../res/adapter-for-obj-pattern-class-diagram.png)

+ Client
Contains business logic of the program.

+ Client Interface

Describes a protocol that other classes must follow to collaborate with the client code.

+ Adaptee (Service)

The useful 3rd-party/legacy class. Client code cannot use this directly because of incompatible interface.

+ Adapter
    - implements the client interface
    - wraps the service object

#### Class Adapter

![Class Adapter Structure](../res/adapter-for-class-pattern-class-diagram.png)

+ Adapter

Inherits behaviors from both the client and the service.

## Caveats
