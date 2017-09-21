Course: ISTA-220
Lesson Plan: 22
Lee H. Sarduy
12 September 2017

1. What is a type parameter?
-A type parameter is a generic type that can be used in place of a real type.

2. What does a type parameter do?
-Acts as a placeholder.

3. How many type parameters can a generic class have?
-A generic class does not have any limit on the number of type parameters it can have.

4. What is the difference between a generic class and a generalized class?
-A generic class has its type parameters converted to real types and a generalized class can hold any object, so the data being used can be cast to the correct type anytime the programmer.

5. What is a constraint? How do you specify a constraint?
-By using a constraint, you can limit the type parameters of a generic class to those 
that implement a particular set of interfaces and therefore provide the methods defined 
by those interfaces. For example, if the IEdible interface implemented the Eat method, 
you could create the EdibleCollection like this: public class EdibleCollection<T> where T : IEdible.

6. What is a generic method? How do you define a generic method?
-A generic method specifies the types of the parameters and the return type by using a type parameter in a manner similar to that used when you define a generic class./By using the same type parameter syntax you use when you create generic classes.

7. What do we mean when we say that a generic type interface is invariant?
-You cannot assign an IWrapper<A> object to a reference of type IWrapper<B>, 
even if type A is derived from type B. By default, C# implements this restriction to ensure the type safety of your code.

8. What do we mean when we say that a generic type interface is covariant?
-You can inform the compiler that some implicit conversions are legal and that it does not have to enforce strict type safety.

9. Does covariance work with value types? Does it work with reference types?
-Covariance works only with reference types. This is because value types cannot form inheritance hierarchies.

10. What do we mean when we say that a generic type interface is contravariant?
-Enables you to use a generic interface to reference an object of type B through a reference to type A as long as type B derives from type A.