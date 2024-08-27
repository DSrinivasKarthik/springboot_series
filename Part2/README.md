## Part 02: Dependency Injection and Bean Configuration


Dependency Injection:
    - It is a **Structural Design Pattern** 
        - Why a Structural DP? ~ 
            - Object Composition: DI involves assembling objects (dependencies) into a larger system. It determines how different objects are composed and interact with each other within the application.
            
            - Decoupling: DI is primarily used to decouple classes from their dependencies, which is a key concern of structural design patterns. This decoupling enhances flexibility and maintainability.

    - promotes Loose Coupling (A design approach that reduces the dependency between components in the system , network or software application)


IOC (Inversion of Control) - It is a Principle
    - A technique / Implementation of IOC is Dependecy injection [ someone else is injecting objects in our application (that someone else here is Spring framework)]

    Constructor Injection, Setter injection, Field Injection (loose coupling)



What is Bean?
- Objects that form the backbone of spring application that are managed by  the Spring IoC container are called beans.

