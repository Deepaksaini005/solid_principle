# SOLID Principles Implementation in Java

This repository demonstrates the implementation of SOLID principles in Java with practical examples.

## SOLID Principles Covered

1. **Single Responsibility Principle (SRP)**
   - Separate classes for Invoice and InvoicePrinter
   - Each class has only one reason to change

2. **Open/Closed Principle (OCP)**
   - Discount interface with implementations
   - New discount types can be added without modifying existing code

3. **Liskov Substitution Principle (LSP)**
   - Bird and Sparrow classes
   - Subtypes can be substituted for their base types

4. **Interface Segregation Principle (ISP)**
   - Separate Printer and Scanner interfaces
   - AllInOnePrinter implements only the interfaces it needs

5. **Dependency Inversion Principle (DIP)**
   - Database interface with MySQL implementation
   - High-level modules depend on abstractions

## Project Structure

```
src/
└── main/
    └── java/
        └── demo/
            └── Solid.java
```

## How to Run

1. Compile the Java file:
   ```bash
   javac src/main/java/demo/Solid.java
   ```

2. Run the program:
   ```bash
   java -cp src/main/java demo.Solid
   ```

## Requirements

- Java 8 or higher 