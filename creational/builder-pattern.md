# Builder Pattern

The exercise of creating a *composite* or an *aggregate* object can be simplified by using the builder pattern, i.e. **creating an object with lots of possible configuration options.**

> A builder pattern encapsulates or hides the process of building a complex object, and separates the representation of the object and its construction. The separation allows us to construct different representations using the same construction process.

## Problem

Creating a `House` object with many different configurations (garage, swimming pool, garden, etc.):

+ extend the base `House` class, create a set of subclasses to cover all configs
    * too many subclasses
    * any new parameter requires to grwo the subclass hierachy
+ create a giant constructor in the base `House` class
    * most of parameters will be unused, the constructor calls could be ugly with `null` or `false`, etc.

## Solution

+ Builder
+ Concrete Builder
+ Director
+ Product

## Caveats

Builder pattern seems similar to the abstract factory pattern, but:
+ builder pattern creates an object step by step
+ abstract factory pattern returns the object in one go
