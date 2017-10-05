Lee H. Sarduy  
MSSA - C#                                                                                                                                                          
Lesson Plan 34

1. Explain the di?erence between the concepts of associativity and precedence.
-Each operator has an assosiativity, it evaluates right to left.


2. Explain the di?erence between the concepts of binary and unary operators.
-Cannot change the presedence, meaning,dominion of the operator.

3. List four constraints imposed by C# with respect to operator overloading.
-All unary and binary operators have pre-defined implementations, that are automatically 
available in any expressions. In addition to this pre-defined implementations, user 
defined implementations can also be introduced in C#. 

4. What is the syntax for overloading operators? Discuss access, scope, 
return value types, and parameter types and multiplicity.
-All unary and binary operators have pre-defined implementations, that 
are automatically available in any expressions. In addition to this pre-defined implementations, 
user defined implementations can also be introduced in C#. 

5. What are symetric overloaded binary operators and how do they differ from non-symmetric overloaded binary operators?
-Whenever an unary operator is used, it works with one operand, therefore with the user 
defined data types, the operand becomes the caller and hence no arguments are required.

6. Can you overload compound assignment operators? If so, please state how you do so. If not, explain why not.
-You can not specificly overload a compound operater if you have overloaded the simple one.

Num& operator+=(const Num& rhs){

  this->m_iNumber += rhs.m_iNumber;

  return *this;

}

7. What is the di?erence between overloading increment and decrement operators for value types and reference types?
-Value types can easily be written to increment the value, but care must be taken with reference types to avoid copying the reference. Instead, a new object must be created based on the data in the original. 
This can become costly in terms of memory and garbage-collection overhead.

8. Why do we overload some operators in pairs?
-With C#, you can also overload many of the existing operator symbols for your own types,
although the syntax is slightly different.

9. What is the di?erence between widening conversion and narrowing conversion?
-An explicit conversion requires explicit notation (a cast) and can through an verflowException exception if 
the resulting value is out of the range of the target type. An implicit conversion requires no special syntax 
and never throws an exception.