Summary of Object-Oriented Programming (OOP) 
==============================================

Object-Oriented Programming (OOP) is a programming paradigm that uses "objects" to design software. 
These objects can contain data in the form of fields (often called attributes) and code in the form of procedures (often called methods). Python is an object-oriented programming language, which means it supports the principles of OOP.

Classes and Objects:
--------------------------

o	Class: A blueprint for creating objects. It defines a set of attributes and methods that the created objects will have.

o	Object: An instance of a class. It is created using the class blueprint and can have its own unique attributes and behaviors.

Attributes and Methods:
-------------------------

o	Attributes: Variables that belong to an object or class.

o	Methods: Functions that belong to an object or class.

Encapsulation:
---------------

o	The concept of bundling the data (attributes) and methods that operate on the data into a single unit, or class.

o	Access to the data can be restricted using access modifiers (e.g., private, protected, public).

 Inheritance:
 -------------
 
o	A mechanism to create a new class using the attributes and methods of an existing class.

o	Promotes code reuse and can simplify the software development process.


Method Overriding :
-------------------
Is a feature in object-oriented programming that allows a subclass to provide a specific implementation of a method that is already defined in its superclass. This mechanism is used to change or extend the behavior of the inherited methods.

•	Purpose: To allow a subclass to modify or extend the behavior of a method defined in a superclass.

•	How it works: The subclass redefines a method with the same name, parameters, and return type as a method in its superclass.

•	Benefits: It allows for dynamic behavior and polymorphism, enabling the same method to perform different tasks based on the object that calls it.

Overriding Default Methods:
------------------------------

In Python, classes can inherit from built-in types or classes that provide default methods. You can override these default methods to change the behavior of objects in your custom classes.

Common Default Methods to Override:
-----------------------------------
1.	__str__ and __repr__:
   
o	__str__: Returns a string representation of the object, used by the print function.

o	__repr__: Returns an unambiguous string representation of the object, used in debugging and by the repr function.

2.	__len__:
   
o	__len__: Returns the length of the object. Often used in custom container classes.

The constructor method:
------------------------
Is a special method used to initialize the attributes of an object when it is created. This method is named __init__ and is automatically called when a new instance of a class is instantiated. It allows for setting initial values for the object's attributes and executing any setup procedures necessary for the object.

Key Points about the Constructor Method (__init__):

- Special Method Name: The constructor method is always named __init__.
- Automatic Call: It is automatically called when a new object of the class is created.
- Self Parameter: The first parameter of __init__ is always self, which refers to the instance being created.
- Initialization: It is used to initialize the object's attributes with default or provided values.
