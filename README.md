# Marlen Cafe

**Author:** MARLEN\
**Language:** Java 17\
**Project:** Design Patterns

## Description

Marlen Cafe is a console-based Java application for managing cafe orders. The program allows users to select food and drinks, customize their orders, apply discounts, and manage order statuses.

The main purpose of this project is to demonstrate how different design patterns can work together in one application.

## Design Patterns

The project uses six design patterns:

1. **Factory Method** - Creates different menu items such as pizza, burgers, and drinks.
2. **Builder** - Creates orders with selected items, quantities, and customer information.
3. **Decorator** - Adds extra ingredients such as cheese and sauce.
4. **Strategy** - Handles regular prices, student discounts, and promotional discounts.
5. **Observer** - Notifies customers and kitchen staff when the order status changes.
6. **Facade** - Simplifies the process of checkout and order management.

## Technologies

- Java 17
- Maven
- Object-Oriented Programming
- Design Patterns

## How to Run

1. Open the project in IntelliJ IDEA.
2. Select JDK 17 or newer.
3. Open `src/main/java/kz/smartcafe/Main.java`.
4. Run the `Main` class.

You can also run the project using Maven:

```bash
mvn compile
java -cp target/classes kz.smartcafe.Main
```

## How It Works

When the program starts, the user can choose items from the cafe menu. The user can add extra ingredients, select quantities, and choose a discount.

After confirming the order, the program calculates the final price and registers the order.

The staff panel allows orders to be viewed and their statuses to be changed to ACCEPTED, PREPARING, or READY.

## Conclusion

This project shows how six design patterns can be combined in a Java application. Each pattern has its own responsibility and helps organize the code into separate components.

The application demonstrates basic order management using object-oriented programming principles.
# sdp_final_project
