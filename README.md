# Software-Princibles

 Contents of SOLID;

 S-Single-responsibility principle: SRP
 It states that a function should have only one job. In other words, only one responsibility is given to the function. If more than one responsibility is given, it does not fit the purpose of the function. In such cases we need to break down the function. When we impose more than one responsibilities, we may encounter more errors in the sections we want to change and it becomes difficult to make changes. Therefore, when defining a function, we need to understand its purpose well and design accordingly. For example, when there is a function containing user information and address information, there is no need for user information when we want to make changes in the address. Two separate functions can be created for user information and address information.

O- -Open-closed principle

It is a principle that preserves the properties of the function and does not allow change. It does not allow changes to an existing func, but a new feature can be added. In other words, it is the principle that offers the opportunity to be changed flexibly in the future without changing the existing code without breaking its structure.

L-Liskov substitution principle: 
 It's a principle where subclasses replace superclasses without making any changes to the code. That is, subclasses can use all the functions of superclasses. Following the open closed principle will make it easier to follow the liskov principle. For example, the square is a subclass of the rectangle because mathematically it derives from the rectangle, but from a software point of view, the two are different things. If one side is requested to be changed, both will have different changes. They should both be called the same classes and be asked to operate. 

I-Interface segregation principle: 
Instead of collecting all the responsibilities in a single interface, it is the principle of creating the same interface for all of them. The person using the interface only reaches the interface he needs. In this sense, it is similar to srp. The difference is that while srp deals with objects, interface deals with the interface. 

D-Dependency Inversion Principle: 
A class's method or property is unique to its own class. Minimize affiliation with other classes aims to download. That is, the change in the subclasses should not affect the superclasses. The way to do this is every both of them are managed with abstract concepts
