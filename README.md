# HeapImplementation
Max and Min Heap Implementation also covers OOP concepts and access specifiers. 

## OOP Concepts Covered
* Ineheritance
* Virtual Keyword - Virtual is used in a base class for the deconstructor as well as any function definitions that may be overriden in the child/derived classes. If used and the derived class redefines function then this will cause the child classes function to execute.

https://www.geeksforgeeks.org/virtual-function-cpp/#:~:text=A%20virtual%20function%20is%20a,Overriden)%20by%20a%20derived%20class.&text=Virtual%20functions%20ensure%20that%20the,pointer)%20used%20for%20function%20call.

* Access Specifiers
  * Public - Members are accessible from outside the class.
  * Private - Members cannot be accessed or viewed from outside the class.
  * Protected - Members cannot be accessed from outside the class, however, they can be accessed from inherited classes.
* Friend Class/Function - A friend class can access private or protected elements of a class.
* Operator Overloading - Overload standard library C++ operators with the operator keyword. An example would be for <<, <, or ++ operators.
* Copy Constructor - A constructor that is created to handle copying of an object when another object of the same type is assigned to it. This is done by default by the compiler, but can be done explicitly.

## Heap Run Complexity

* Delete element:
#### O(Log n)

* Insert Element:
#### O(Log n)

* Get Min. or Max. value:
#### O(1)

## STL Implementation
* STL Implementation can of heaps is with the priority_queue container.

https://www.geeksforgeeks.org/implement-min-heap-using-stl/

## Heap General Implementation Notes
* Heaps are implemented in arrays/vectors much more easily thank link list implementations.

* The array/vector implementation allows for easire memory management with only 1 container created vs. N nodes.

* Less memory is needed due to not needing to store pointers.

* The memory is more tightly coupled and not stored in fragmented memory space.

* Iterating through an array is simpler to manage vs. refernce poitners to next nodes. (My Opinion)
