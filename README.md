# Samar ky Notes
## OOP
*Monday 06/11/2023 (week-2 day-1)*

### Why?
- Provides clear structure for the program. For instance, in a bank application, all the methods related to saving accounts can be found in the saving account class.
- Easier to maintain, modify and debug.
### Class:
- class is a template for an object. "Car" is a class. "Volvo" "Honda" etc are the objects.
- When individual objects are created, they inherit all the variables and methods from the class.
- **Static method** can be accessed without creating an object/instance.
### Constructors:
- A constructor is called when an object/instance is created.
- It cannot have any return type. Not even 'void'.
- Constructor name must match the class name.
- It can be used to set the initial values.
- Constructors can be overloaded.  
---
## OOP & UML 
*Tuesday 07/11/2023 (week-2 day-2)*

### Encapsulation: 
- to make sure that sensitive data is hidden from users.
**Property** It's like a combination of a variable and a method.
#### get & set
```
class Person
{
  private string name; // field

  public string Name   // property
  {
    get { return name; }   // get method
    set { name = value; }  // set method
  }
}
```
for automatic: `public string name {get; set;}`
### Access Modifiers: (Encapsulation)
- **public**: Accessible for all classes.
- **private**: Accessible within the same class.
- **protected**: Accessible within the same class and derived classes.
By default, all members of a class are private, if you do not specify.
### Polymorphism: 
- Static Polymorphism: Overloading: same function with different type or number of parameters
- Dynamic Polymorphism: Overriding
- To override a method in a derived class, it must be declared in the base class as an abstract or virtual method.
- Overloading does not happen on changing the return type, because if the program does not consume the returned value, the compiler would be confused about which method to call.

### Abstraction:
- to hide certain details from the user.
- can be achieved by abstract classes and interfaces.

### Abstract Class:
- Cannot be used to create classes.
- Abstract method can only be in an abstract class.
- An abstract class can contain abstract methods and non-abstract methods.

### Interface: (another way to achieve abstraction)
- Interface can only contain signatures of the methods and properties.
- The keyword 'override' is not used while overriding methods of interfaces.
- All the methods are abstract and public in an abstract class.


