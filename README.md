# DCIT 318: Programming II Assignment 2

This repository contains three C# console applications demonstrating different aspects of object-oriented programming:

## 1. Inheritance and Method Overriding
**Location:** `dcit318-assignment2-11012985/InheritanceAndOverriding`

- Defines a base class `Animal` with a virtual method `MakeSound()`.
- Derived classes `Dog` and `Cat` override `MakeSound()` to print specific sounds.
- The `Main` method demonstrates polymorphism by calling `MakeSound()` on each instance.

## 2. Abstract Classes and Methods
**Location:** `dcit318-assignment2-11012985/AbstractClasses`

- Defines an abstract class `Shape` with an abstract method `GetArea()`.
- Derived classes `Circle` and `Rectangle` implement `GetArea()` to calculate their respective areas.
- The `Main` method creates instances and displays their areas.

## 3. Interfaces
**Location:** `dcit318-assignment2-11012985/Interfaces`

- Defines an interface `IMovable` with a method `Move()`.
- Classes `Car` and `Bicycle` implement `IMovable` and provide their own `Move()` implementations.
- The `Main` method demonstrates interface usage.

## How to Run
Each application is a separate C# console project. To run any of them, use:

```bash
dotnet run --project dcit318-assignment2-11012985/<ProjectFolder>
```
Replace `<ProjectFolder>` with `InheritanceAndOverriding`, `AbstractClasses`, or `Interfaces`.