# Java Programming

- [Java](#java)
- [Properties](#properties)
- [Concepts](#concepts)
  - [Inheritance](#inheritance)
  - [Polymorphism](#polymorphism)
  - [Abstraction](#abstraction)
  - [Encapsulation](#encapsulation)
  - [Class](#class)
  - [Object](#object)
  - [Methods](#methods)
  - [Instance Variables](#instance-variables)
  - [History](#history)
  - [Package](#package)

## Java

Java is a high-level programming language originally developed by Sun Microsystems and released in 1995. Java runs on a variety of platforms, such as Windows, Mac OS, and the various versions of UNIX.

Java is guaranteed to be **Write Once**, **Run Anywhere**

## Properties

**Object Oriented** - In Java, everything is an Object. Java can be easily extended since it is based on the Object model.

**Platform Independent** - Unlike many other programming languages including C and C++, when Java is compiled, it is not compiled into platform specific machine, rather into platform independent byte code. This byte code is distributed over the web and interpreted by the Virtual Machine (JVM) on whichever platform it is being run on.

**Simple** - Java is designed to be easy to learn. If you understand the basic concept of OOP Java, it would be easy to master.

**Secure** - With Java’s secure feature it enables to develop virus-free, tamper-free systems. Authentication techniques are based on public key encryption.

**Multithreaded** - With Java's multithreaded feature it is possible to write programs that can perform many tasks simultaneously. This design feature allows the developers to construct interactive applications that can run smoothly.

**High Performance** - With the use of Just-In-Time compilers, Java enables high performance.

**Dynamic** - Java is considered to be more dynamic than C or C++ since it is designed to adapt to an evolving environment.

## Concepts

Java is an Object-Oriented Language. As a language that has the Object-Oriented feature, Java supports the following fundamental concepts:
- **Polymorphism**
- **Inheritance** (+ Overriding)
- **Encapsulation**
- **Abstraction**
- Classes
- Objects
- Instance
- Method
- Interface
- Package

### Inheritance

Inheritance can be defined as the process where one class acquires the properties (methods and fields) of another. With the use of inheritance the information is made manageable in a hierarchical order.

The class which inherits the properties of other is known as subclass and the class whose properties are inherited is known as superclass.

In object-oriented terms, overriding means to override the functionality of an existing method.

### Polymorphism

Polymorphism is the ability of an object to take on many forms. The most common use of polymorphism in OOP occurs when a parent class reference is used to refer to a child class object.
It is important to know that the only possible way to access an object is through a reference variable. A reference variable can be of only one type. Once declared, the type of a reference variable cannot be changed.

```java
public interface Vegetarian {}
public class Animal {}
public class Deer extends Animal implements Vegetarian {}

Deer d = new Deer();
Animal a = d;
Vegetarian v = d;
```

### Abstraction

In Object-Oriented Programming, abstraction is a process of hiding the implementation details from the user, only the functionality will be provided to the user. In other words, the user will have the information on what the object does instead of how it does it.
In Java, abstraction is achieved using **abstract classes** and **interfaces**.
A class which contains the **abstract** keyword in its declaration is known as abstract class.

### Encapsulation

Encapsulation is one of the four fundamental OOP concepts. The other three are inheritance, polymorphism and abstraction.
Encapsulation in Java is a mechanism of wrapping the data (variables) and code acting on the data (methods) together as a single unit. In encapsulation, the variables of a class will be hidden from other classes, and can be accessed only through the methods of their current class. Therefore, it is also known as **data hiding**.

### Class

A class can be defined as a template/blueprint that describes the behavior/state that the object of its type supports.

### Object

Objects have states and behaviors. An object is an instance of a class

### Methods

A method is basically a behavior. A class can contain many methods. It is in methods where the logics are written, data is manipulated and all the actions are executed.

### Instance Variables

Each object has its unique set of instance variables. An object’s state is created by the vales assigned to these instance variables.

### History

An interfaces is a reference type in Java. It is similar to class. It is a collection of abstract methods. A class implements an interface, thereby inheriting the abstract methods of the interface.

### Package

Pages are used in Java in order to prevent naming conflicts, to control access, to make searching/locating and usage of classes, interfaces, enumerations and annotations easier, etc.

A Package can be defined as a grouping of related types (classes, interfaces, enumerations and annotations) providing access protection and namespace management.