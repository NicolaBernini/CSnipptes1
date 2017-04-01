
# Overview 

The Linux Elements for Time 

# Monotonic Time Getter 

The "Monotonic Time Getter" is in charge of providing a Monotonic Time : a time which increases without jumps, independently of the Wall Clock. 

It is provided by the Standard Posix API 

```
clock_gettime(CLOCK_MONOTONIC, time);
```

See [clock_gettime](https://linux.die.net/man/3/clock_gettime)



