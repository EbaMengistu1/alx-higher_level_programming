0x08. Python - More Classes and Objects
 

By Guillaume
 

Resources


Read or watch:



Object Oriented Programming (Read everything until the paragraph “Inheritance” (excluded))

Object-Oriented Programming (Please be careful: in most of the following paragraphs, the author shows the way you should not use or write a class, in order to help you better understand some concepts and how everything works in Python 3. Make sure you read only the following paragraphs: “General Introduction,” “First-class Everything,” “A Minimal Class in Python,” “Attributes,” “Methods,” “The __init__ Method,” “Data Abstraction, Data Encapsulation, and Information Hiding,” “__str__- and __repr__-Methods,” “Public- Protected- and Private Attributes,” & “Destructor”)

Class and Instance Attributes

classmethods and staticmethods

Properties vs. Getters and Setters (Mainly the last part “Public instead of Private Attributes”)

str vs repr

Learning Objectives

At the end of this project, you are expected to be able to explain to anyone, without the help of Google:



General

Why Python programming is awesome

What is OOP

“first-class everything”

What is a class

What is an object and an instance

What is the difference between a class and an object or instance

What is an attribute

What are and how to use public, protected and private attributes

What is self

What is a method

What is the special __init__ method and how to use it

What is Data Abstraction, Data Encapsulation, and Information Hiding

What is a property

What is the difference between an attribute and a property in Python

What is the Pythonic way to write getters and setters in Python

What are the special __str__ and __repr__ methods and how to use them

What is the difference between __str__ and __repr__

What is a class attribute

What is the difference between a object attribute and a class attribute

What is a class method

What is a static method

How to dynamically create arbitrary new attributes for existing instances of a class

How to bind attributes to object and classes

What is and what does contain __dict__ of a class and of an instance of a class

How does Python find the attributes of an object or class

How to use the getattr function

Requirements

General

Allowed editors: vi, vim, emacs

All your files will be interpreted/compiled on Ubuntu 20.04 LTS using python3 (version 3.8.5)

All your files should end with a new line

The first line of all your files should be exactly #!/usr/bin/python3

A README.md file, at the root of the folder of the project, is mandatory

Your code should use the pycodestyle (version 2.7.*)

All your files must be executable

The length of your files will be tested using wc

Quiz questions

Hide



Question #0

What is __init__?





A class attribute





A class method





The instance method called when a new object is created




The instance method called when a class is called for the first time

Question #1
What is __str__?


Instance method that returns an “informal” and nicely printable string representation of an instance


Instance method that returns the dictionary representation of an instance


Instance method that prints an “informal” and nicely printable string representation of an instance

Question #2
What is __repr__?


Instance method that prints an “official” string representation of an instance


Instance method that returns an “official” string representation of an instance


Instance method that returns the dictionary representation of an instance

Question #3
What is __del__?


Instance method that removes the last character of an instance


Instance method that prints the memory address of an instance


Instance method called when an instance is deleted

Question #4
What is __doc__?


The string documentation of an object (based on docstring)


Prints the documentation of an object


Creates man file

Question #5
What do these lines print?

class User:
    id = 1

print(User.id)

None


1


89


98

Question #6
What do these lines print?

class User:
    id = 1

u = User()
print(u.id)

None


1


89


98

Question #7
What do these lines print?

class User:
    id = 1

u = User()
u.id = 89
print(u.id)

None


1


89


98

Question #8
What do these lines print?

class User:
    id = 1

User.id = 98
u = User()
print(u.id)

None


1


89


98

Question #9
What do these lines print?

class User:
    id = 1

u = User()
User.id = 98
print(u.id)

None


1


89


98

Question #10
What do these lines print?

class User:
    id = 1

User.id = 98
u = User()
u.id = 89
print(u.id)

None


1


89


98

Question #11
What do these lines print?

class User:
    id = 1

User.id = 98
u = User()
u.id = 89
print(User.id)

None


1


89


98

Question #12
What do these lines print?

class User:
    id = 1

u = User()
u.id = 89
User.id = 98
print(User.id)

None


1


89


98

Question #13
What do these lines print?

class User:
    id = 1

u = User()
u.id = 89
User.id = 98
print(u.id)

None


1


89


98
