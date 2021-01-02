# HeapImplementation
Max and Min Heap Implementation also covers OOP concepts and access specifiers. 

## OOP Concepts Covered
* Ineheritance
* Access Specifiers
  * Public - Members are accessible from outside the class.
  * Private - Members cannot be accessed or viewed from outside the class.
  * Protected - Members cannot be accessed from outside the class, however, they can be accessed from inherited classes.

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
