
# Overview 

The Memory Management C API 

# Memory Management API Semantic 

In C, the Memory Management Semantic is type agnostic 
- Elements are always treated as a sequence of bytes 


## Memory Allocation 

- What the C StdLib provides is an API to perform the allocation of a Sequence of Bytes 
- It is programmer's responsibility 
  - 1) to specify the right amount of bytes 
  - 2) to explicitely cast (i.e. impose semantic) the result of the allocation 
  - 3) to manage errors (i.e. out of memory)
    



