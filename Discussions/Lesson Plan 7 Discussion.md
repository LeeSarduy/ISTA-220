Lee H. Sarduy                                                                                                                                         Chapter 7

8/16/2017                                                                                                                                              Pages 153-174

**Homework**

**Lesson Plan 7**

1. **What is a**  **class****? According to the book, what does a class &quot;arrange?&quot;**

A **class** is a construct that enables you to create your own custom types by grouping together variables of other types, methods and events. A **class** is like a blueprint. It defines the data and behavior of a type. ... Unlike structs, **classes** support inheritance, a fundamental characteristic of object-oriented programming.

1. **What are the two purposes of**  **encapsulation****?**



1. **How do you**  **instantiate**  **an instance of a class? How do you access that instance?**

1. **What is the default access of the fields and methods of a class? How do you change the default?**

By default, the field and method of a class are private



1. **What is the syntax for writing a**  **constructor****?**
2. publicclassPerson
3. {
4.    privatestring last;
5.    privatestring first;
6.
7.    publicPerson(string lastName, string firstName)
8.    {
9.       last = lastName;
10.       first = firstName;
11.    }
12.
13.    // Remaining implementation of Person class.
14. }



1. **What is the difference between class fields and methods, and instance fields ad methods? How do you create class fields and methods?**

Class field and methods provides a useful function that is independent of any class instance. If you declare a method or a field as static, you can call the method or access the field by using the name of the class. No instance is required.



1. **How do you bring a static class in scope? Why would you want to bring a static class in scope?**

Static using statements enable you to bring a class into scope and omit the class name when accessing static members. They operate

1. **Can you think of a good reason to create an**  **anonymous class****? What is it?**

An anonymous class is a class that does not have a name. Anonymous classes can be useful when using query expressions.

1. **What is**  **polymorphism**  **as this term is used in computer science? This is not in the book.**

In programming languages and type theory, **polymorphism** is the provision of a single interface to entities of different types. A **polymorphic** type is one whose operations can also be applied to values of some other type, or types

1. **What is** _message passing_ **as this term is used in computer science? This is not in the book.**

Message passing is a type of communication between processes. Message passing is a form of communication used in **parallel programming** and object-oriented **programming**. Communications are completed by the sending of messages (functions, signals and data packets) to recipients.

**      11. What was the first object-oriented programming language?**

1. **4.**** What happens in a program if an **_exception block_** fails to handle an particular error?**

If, after cascading back through the list of calling methods is unable to find matching catch handler, the program will determine with an unhandled exceptions.

1. **5.**** What is the parent class for all exceptions? How does this work?**

Exception is the parent class of all exceptions. If you catch exception, the hanlder traps every possible exception that can occur.

1. **6.**** How do you determine the type of an error?**

You can determine the type of error by examining the details in the message property of the thrown exception.

1. **7.**** What is the purpose of integer checking?**

**             ** It validates user inputs.

1. **8.**** What does the **_finally_** block do?**

It ensures that a statement is always running, whether or not an exception has been thrown