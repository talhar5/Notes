# Samar ky Notes
## OOP Monday
06/11/2023 (week-2 day-1)
### Why?
- Provides clear structure for the program. For instance, in a bank application, all the methods related to saving accounts can be found in the saving account class.
- Easier to maintain, modify and debug.
### Class:
- class is a template for an object. "Car" is a class. "Volvo" "Honda" etc are the objects.
- When individual objects are created, they inherit all the variables and methods from the class.
## OOP & UML Tuesday 07/11/2023 (week-2 day-2)
### Polymorphism: 
- Static Polymorphism: Overloading
- Dynamic Polymorphism: Overriding
- To override a method in a derived class, it must be declared in the base class as an abstract or virtual method.
- Overloading does not happen on changing the return type, because if the program does not consume the returned value, the compiler would be confused about which method to call.
- Abstract method can only be in an abstract class.
- An abstract class can contain abstract methods and non-abstract methods.

### Abstract Class:
- Cannot be used to create classes.

### Interface: (another way to achieve abstraction)
- Interface can only contain signatures of the methods and properties.
- The keyword 'override' is not used while overriding methods of interfaces.
- All the methods are abstract and public in an abstract class.
