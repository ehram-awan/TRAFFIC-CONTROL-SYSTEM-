# SmartTraffic: Object-Oriented Traffic Control System

**SmartTraffic** is an object-oriented traffic control center system developed in C++. It allows the registration of different vehicle types (Car, Motorcycle, Truck), monitors traffic speed, and detects speed violations. The system demonstrates core OOP concepts including inheritance, polymorphism, encapsulation, and operator overloading.

---

## Features

- **Vehicle Registration:** Register cars, motorcycles, and trucks with details like registration number, brand, speed, and type-specific attributes.
- **Traffic Speed Monitoring:** Display details of all registered vehicles.
- **Violation Detection:** Identify vehicles exceeding a specified speed limit.
- **OOP Principles:** 
  - **Inheritance:** Derived classes (Car, Motorcycle, Truck) inherit from a base Vehicle class.
  - **Polymorphism:** Vehicle-specific `show()` function called dynamically.
  - **Encapsulation:** Private attributes with getters to ensure data integrity.
  - **Operator Overloading:** Compare vehicles based on registration numbers.
- **Dynamic Memory Management:** Vehicles are dynamically allocated and safely deallocated.

---

## Installation

1. Clone the repository:  
   git clone https://github.com/yourusername/smarttraffic.git

Navigate to the project directory:

cd smarttraffic

Compile the code using a C++ compiler:

g++ main.cpp -o SmartTraffic

Run the executable:

./SmartTraffic   # Linux/Mac
SmartTraffic.exe # Windows

---

## Usage

Launch the program.

Choose from the menu options:

Register a new vehicle

Monitor traffic speed

Detect speed violations

Exit the program

Enter vehicle details as prompted for registration.

Set speed limits to check for violations.

View registered vehicle details anytime via the menu.


---

## Methodologies

Object-Oriented Programming: Structured code with base and derived classes.

Encapsulation: Private member variables with public getter methods.

Polymorphism: Virtual show() function overridden in derived classes.

Dynamic Memory Allocation: Handles vehicle objects dynamically using pointers.

Menu-Driven Interaction: Uses loops and switch-case for user interaction.

Challenges

Correctly handling dynamic memory and preventing memory leaks.

Ensuring polymorphic behavior works correctly for all vehicle types.

Validating input for registration and speed limits.


---

## Limitations

No exception handling for invalid inputs.

Only supports command-line interface.

Limited to registered vehicle types (Car, Motorcycle, Truck).


---

## Future Enhancements

Add GUI for better user experience.

Implement file/database storage for persistent vehicle records.

Include more vehicle types and traffic rules.

Generate reports and statistics on traffic violations.

Integrate with real-time traffic sensors or IoT devices.


---

## Conclusion

SmartTraffic demonstrates an object-oriented approach to traffic management, showcasing OOP principles such as inheritance, polymorphism, and operator overloading. It efficiently manages vehicle registration, monitors speeds, and detects violations. The system is modular, extensible, and provides a foundation for advanced traffic control solutions.
