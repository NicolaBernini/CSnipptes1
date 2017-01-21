
# Overview 

Some example of C common idioms for Memory Management 

## Memory Allocation Idioms 

### Dynamic Allocation 

Common Idiom 

```cpp
TestType* m_test = malloc(sizeof(TestType)); 
```
- Con 
  - Double type dependency (pointer type and `sizeof` argument)

Improvement 

```cpp
TestType* m_test = malloc(sizeof(*m_test)); 
```

- Pro 
  - Single type dependency 
  - **Note** The `sizeof` is an operator, not a function, hence its evaluation happens at compile-time 
    - It means no invalid pointer dereferencing 


