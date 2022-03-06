# Abstract Factory Pattern

> Define an interface to create families of related or dependent objects without specifying their concrete classes.

## Problem

## Solution

#### Abstract Factory
#### Concrete Factory

Can be best represented as a **singleton** object.

#### Abstract Product
#### Concrete Product
#### Client

## Caveats

Factory method pattern and abstract factory pattern look similar, but:
+ Factory method pattern
    * is usually responsible for creating a *single product*
    * uses inheritance to create more specialized products
+ Abstract factory pattern
    * creates *entire families of related products*
    * composes object by passing in factories that are consumed to create the desired products
