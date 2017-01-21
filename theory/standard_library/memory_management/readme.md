
# Overview 

The Memory Management C API 

# Memory Management API Semantic 

The Memory Management API are related to dynamic memory management: allocation, copy, ... 

The Memory Management Semantic is type agnostic
- Comments
  - Elements are always treated as a sequence of bytes 
- Pro 
  - Maximum generality 
- Con 
  - No compile-time checks 
  - The compiler can't automatically infer the size for the allocation 
    - It means the programmer is fully responsibilized in defining the size 



## Memory Allocation 

- What the C StdLib provides is an API to perform the allocation of a Sequence of Bytes 
- It is programmer's responsibility 
  - 1) to specify the right amount of bytes 
  - 2) to explicitely cast (i.e. impose semantic) the result of the allocation 
  - 3) to manage errors (i.e. out of memory)
    



