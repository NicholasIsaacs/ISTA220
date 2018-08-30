# ISTA220 CH8 HW

1. What is the difference between deep copy and shallow copy?  
A: Deep copy copies all fields, while shallow copy is like a clone. 
2. What is the value of a reference after you declare and initialize it?  
A: A memory address.
3. How do you declare a value type?  
A: int i; State type then variable.
4. How do you declare a reference type?  
A: Cow Elsie = new Cow(); Class, name (assignment operator) new(keyword) constructor;
5. Does C# allow you to assign NULL to a value type?  
A: Yes, type followed by ?. int? i =null;
6. Can you assign a nullable value type to a non-nullable variable of the same type? Why or why not?  
A: No, because you don't know, nor does the machine if it has a null type. 
7. What is the difference between the stack and the heap?  
A: Stack is used for static memory allocation and Heap for dynamic memory allocation. Variables allocated on the stack are stored directly to the memory and access to this memory is very fast, and it's allocation is dealt with when the program is compiled. Variables allocated on the heap have their memory allocated at run time and accessing this memory is a bit slower, but the heap size is only limited by the size of virtual memory. 
8. What does it mean when we say that all classes are specialized types?  
A: It refers to the idea that classes are specialized types of data capable of catering to more specific circumstances. 
9. What does ref do?  
A: It passes a reference rather than making a copy.
10. What does out do?  
A: Requires a method assign a value to the parameter before it returns it. 
11. Describe boxing and unboxing in your own words.  
A:  Takes value type stored on the stack and takes it to the heap. Reference type to value type.  
12. What does cast do?  
A:  Checks if the value type is available before calling a variable to that value type.