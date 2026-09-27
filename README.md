## SHASWANTH MATHAV S (212224050046)
## 1. Python OOP: Abstract Class & Method Example

## 🎯 AIM

To create an abstract class named Shape with an abstract method calculate_area, and implement this method in two subclasses: Rectangle and Circle.

## 🧠 ALGORITHM

Import ABC module:

Use from abc import ABC, abstractmethod to define abstract classes and methods.

Create Abstract Class Shape:

Define an abstract method calculate_area() with @abstractmethod.

Create Subclass Rectangle:

Set default values for length and breadth.

Override calculate_area() to compute the rectangle area.

Create Subclass Circle:

Set default value for radius.

Override calculate_area() to compute the circle area.

Create Objects & Call Methods:

## Program

<img width="800" height="676" alt="Screenshot 2026-07-20 183625" src="https://github.com/user-attachments/assets/27ca779f-7bbf-48bb-8d6e-bab73b615ba8" />

## output

<img width="632" height="232" alt="Screenshot 2026-07-20 183630" src="https://github.com/user-attachments/assets/b651480e-fe40-47bb-8ec4-bb52e7986bf5" />

## Result

The execution of the program was successfully done.

## 2. Python OOP: Encapsulation with Private Members

## 🎯 AIM

To implement Encapsulation in Python by defining a class Rectangle with private member variables __length and __breadth.

## 🧠 ALGORITHM

Define the Class:

Create a class Rectangle with two private attributes: __length and __breadth.

Initialize Variables:

Use the __init__() constructor to set initial values for __length and __breadth.

Print Values:

Display the private variables from within the class to demonstrate access.

Instantiate the Object:

Create an object of the Rectangle class to trigger the constructor.

💻 ProgramInstantiate Rectangle and Circle.

Call their calculate_area() methods.

## 💻 Program

<img width="812" height="352" alt="Screenshot 2026-07-20 183819" src="https://github.com/user-attachments/assets/7c838778-69e7-4db2-9e53-dd272abdf318" />

## output

<img width="653" height="248" alt="Screenshot 2026-07-20 183823" src="https://github.com/user-attachments/assets/6087f0c6-0b70-4417-a8fa-78a669ef4e0b" />

## Result
The execution of the program was successfully done.

## 3. Method Overriding-Fish and Shark Class Inheritance in Python

## 🧠 AIM:

To write a Python program that demonstrates class inheritance by creating a parent class Fish with a method type, and a child class Shark that overrides the type method.

## 📋 ALGORITHM:

Define the Fish class with a method named type() that prints "fish".

Define the Shark class as a subclass of Fish, and override the type() method to print "shark".

Create an instance of the Fish class named obj_goldfish.

Create an instance of the Shark class named obj_hammerhead.

Use a for loop to iterate over both objects.

Within the loop, call the type() method using the loop variable.

Output will demonstrate method overriding: printing "fish" and "shark" accordingly.

## 💻 PROGRAM:

<img width="637" height="422" alt="Screenshot 2026-07-20 183947" src="https://github.com/user-attachments/assets/7a636eb3-6d4b-4790-ad26-29f4b4708f97" />

## output

<img width="647" height="246" alt="Screenshot 2026-07-20 183950" src="https://github.com/user-attachments/assets/a12d49e5-a927-40cb-b7e6-b3156399885f" />

## RESULT

The execution of the program was successfully done.

## 4. Python OOP: Operator Overloading (Less Than <)

## 🎯 AIM

To write a Python program that demonstrates operator overloading by overloading the less than (<) operator using a custom class.

## 🧠 ALGORITHM

Create Class A:

Define the __init__() method to initialize the object with a value a.

Overload the < Operator:

Define the __lt__() method with logic:

If self.a < o.a, return "ob1 is less than ob2"

Else, return "ob2 is less than ob1"

Create Objects:

Instantiate two objects ob1 and ob2 with values.

Use < Operator:

Use print(ob1 < ob2) to trigger the overloaded behavior.

## 💻 Program

<img width="842" height="477" alt="Screenshot 2026-07-20 184207" src="https://github.com/user-attachments/assets/7c313634-783d-44b4-802e-d19b6676d036" />

## output

<img width="916" height="300" alt="Screenshot 2026-07-20 184211" src="https://github.com/user-attachments/assets/025668c1-d171-4dea-aed0-563e908c964a" />

## Result

The execution of the program was successfully done.

## 5. Python OOP: Polymorphism with Classes

## 🎯 AIM

To create two specific classes — Beans and Mango. Then, create a generic function that can accept any object and determine its type (Fruit or Vegetable) and color, using polymorphism.

## 🧠 ALGORITHM

Create Class Beans:

Define type() method that prints "Vegetable".

Define color() method that prints "Green".

Create Class Mango:

Define type() method that prints "Fruit".

Define color() method that prints "Yellow".

Define Generic Function func(obj):

Call obj.type() and obj.color() — this works with both Beans and Mango objects, showcasing polymorphism.

Create Objects:

Instantiate Beans and Mango.

Pass them to func() and execute the program.

## 💻 Program

<img width="815" height="620" alt="Screenshot 2026-07-20 184354" src="https://github.com/user-attachments/assets/89a87043-04aa-4a4b-a5d4-447c44021a7f" />

## output



<img width="685" height="297" alt="Screenshot 2026-07-20 184358" src="https://github.com/user-attachments/assets/dd2f81d7-257e-4e90-bb86-bcf72dac7b45" />

## Result

The execution of the program was successfully done.
