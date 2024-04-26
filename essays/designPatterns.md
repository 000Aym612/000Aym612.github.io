---
layout: essay
type: essay
title: "Design patterns help your "
date: 2024-04-25
published: false
labels:
  - Design Patterns
  - Software Engineering
  - Object-Oriented Programming
---
### Overview
- [Functional Aspects of Design Patterns](#functional-aspects-of-design-patterns)
- [Design Patterns in Object-Oriented Programming](#design-patterns-in-object-oriented-programming)
- topic_3



### Functional Aspects of Design Patterns
### Creational Patterns:
**Creational patterns** deal with object creation mechanisms. 

**Singleton:** Ensures a class has only one instance and provides a global point of access to it.

**Factory Method:** Defines an interface for creating an object, but lets subclasses decide which class to instantiate.

**Builder:** Separates the construction of a complex object from its representation, allowing the same construction process to create different representations.

### Structural Patterns:
**Structural patterns** are concerned with how classes and objects are composed to form larger structures. Examples include:

**Adapter:** Allows interfaces of incompatible objects to work together.

**Decorator:** Adds new functionality to an object dynamically.

**Facade:** Provides a simplified interface to a complex subsystem.

### Behavioral Patterns:
**Behavioral patterns** are concerned with algorithms and the assignment of responsibilities between objects.

**Observer:** Defines a dependency between objects so that when one object changes state, all its dependents are notified.

**Strategy:** Enables an algorithm's behavior to be selected at runtime.

**Command:** Encapsulates a command request as an object, thereby letting you parameterize clients with different requests.

### Design Patterns in Object-Oriented Programming
```
public class House {
    // Attributes of the house
    private String color;
    private int numberOfRooms;
    private double squareFootage;
    private boolean hasGarage;

    // Constructor to initialize the House object
    public House(String color, int numberOfRooms, double squareFootage, boolean hasGarage) {
        this.color = color;
        this.numberOfRooms = numberOfRooms;
        this.squareFootage = squareFootage;
        this.hasGarage = hasGarage;
    }

    // Getter and Setter methods
    public String getColor() {
        return color;
    }

    public void setColor(String color) {
        this.color = color;
    }

    public int getNumberOfRooms() {
        return numberOfRooms;
    }

    public void setNumberOfRooms(int numberOfRooms) {
        this.numberOfRooms = numberOfRooms;
    }

    public double getSquareFootage() {
        return squareFootage;
    }

    public void setSquareFootage(double squareFootage) {
        this.squareFootage = squareFootage;
    }

    public boolean hasGarage() {
        return hasGarage;
    }

    public void setHasGarage(boolean hasGarage) {
        this.hasGarage = hasGarage;
    }

    // Method to display information about the house
    public void displayInfo() {
        System.out.println("House Details:");
        System.out.println("Color: " + color);
        System.out.println("Number of Rooms: " + numberOfRooms);
        System.out.println("Square Footage: " + squareFootage);
        System.out.println("Has Garage: " + (hasGarage ? "Yes" : "No"));
    }
```
