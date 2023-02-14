# Builder-sandwich

Builder design pattern example

What is the builder design pattern?

The Builder design pattern is a creational design pattern that allows the construction of complex objects step by step. The pattern separates the construction of a complex object from its representation, allowing the same construction process to create different representations. The Builder pattern allows the client code to construct objects efficiently, as it is not required to know the details of the objects being constructed.

In object-oriented programming, the Builder pattern is used to create complex objects that have multiple components. For example, consider a scenario where you are building a car. A car has many parts, such as wheels, engine, doors, etc. The Builder pattern can be used to construct a car object, piece by piece, without the client code having to know the details of how each part is constructed.

The Builder pattern consists of four main components:

The Builder abstract class or interface, which defines the methods for constructing the parts of the object.

Concrete Builder classes, which implement the Builder class or interface and construct the parts of the object.

The Director class, which is responsible for coordinating the construction process.

The Product class, which represents the complex object being constructed.

Example: Building a Sandwich

Let's consider an example of building a sandwich. The Builder pattern can be used to construct a sandwich object, step by step, without the client code having to know the details of how each part is constructed.
