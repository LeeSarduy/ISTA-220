Lee H. Sarduy                                                                                                                                               Chapter 8 – C#

8/22/2017                                                                                                                                                    Pages 177-199

**Homework**

**(Lesson Plan 9)**



1. **What is the difference between deep copy and shallow copy?**

A Shallow Copy is about copying an object&#39;s value type fields into the target object and the object&#39;s reference types are copied as references into the target object but not the referenced object itself. And Deep Copy is used to make a complete deep copy of the internal reference types, for this we need to configure the object returned by MemberwiseClone().

1. **What is the value of a reference after you declare and initialize it?**

Whatever value you give it.

1. **How do you declare a value type?**



1. **How do you declare a reference type?**



1. **Does C# allow you to assign NULL to a value type?**

It depends.

1. **Can you assign a nullable value type to a non-nullable variable of the same type? Why or why not?**

No.

1. **What is the difference between the stack and the heap?**

Stack is allocated memory and heap is unallocated memory. The Stack is more or less responsible for keeping track of what&#39;s executing in our code (or what&#39;s been &quot;called&quot;).  The Heap is more or less responsible for keeping track of our objects (our data, well... most of it; we&#39;ll get to that later).

1. **What does it mean when we say that all classes are specialized types?**



1. **What does ref do?**

It pass value types by reference.

1. **What does out do?**

You can use the out contextual keyword in two contexts:+

- As a parameter modifier, which lets pass an argument to a method by reference rather than by value.
- In generic type parameter declarations for interfaces and delegates, which specifies that a type parameter is covariant.





1. **Describe boxing and unboxing in your own words.**

Boxing is the process of converting a [value type](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/value-types) to the type object or to any interface type implemented by this value type. When the CLR boxes a value type, it wraps the value inside a System.Object and stores it on the managed heap. Unboxing extracts the value type from the object. Boxing is implicit; unboxing is explicit.

1. **What does cast do?**

It changes the value of the type.

A **cast** is a way of explicitly informing the compiler that you intend to make the conversion and that you are aware that data loss might occur.
