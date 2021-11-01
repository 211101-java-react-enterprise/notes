# Object-Oriented Programming

Object-oriented programming (**OOP**) is a subparadigm belonging to the [imperative programming paradigm](./imperative-programming.md), and is based on the concept of "objects". Objects are instances of type definitions, or *classes*, that can contain **state** and **behavior**: state in the form of *fields* (also known as *attributes* or *properties*), and behavior, in the form of *procedures* (also known as *methods*).

## Pillars of OOP

- **Abstraction** By simplifying objects to a set of useful features, we hide irrelevant details, reduce complexity, and increase efficiency. Abstraction is important at all levels of software and computer engineering, but essential to designing useful objects. Complicated real-world objects are reduced to simple representations.

- **Encapsulation** Objects should group together related variables and functions and be in complete control over them. So the state of an object should only change, if ever, through the object itself. Also known as data hiding, because the object has sole responsibility for its fields, and no outside object or function should interfere.

- **Inheritance** Code reuse is an important principle of programming (DRY - Don't Repeat Yourself), and new classes can reuse code from existing ones. This establishes a superclass-subclass (or parent-child) relationship where the derived classes inherit (and sometimes change) fields and methods from its parent.

- **Polymorphism** With inheritance, an object of a derived class can be referenced as instances of its parent class. This provides flexibility when invoking inherited methods with varying implementations in derived classes.