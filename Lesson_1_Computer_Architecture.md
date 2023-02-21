# Lesson 1 Computer Architecture


## Introduction

Watch the following video to get a general idea of computer architecture.
https://youtu.be/vgPFzblBh7w
https://youtu.be/o_WXTRS2qTY

Answer the following questions:
- Question

## Common questions that might be asked in interviews

1. What is the difference between von Neumann and Harvard architectures?
2. How do cache memories work? What is the principle behind cache hits and misses?
3. What is pipelining and how does it improve the performance of a processor?
4. What is the difference between RISC and CISC architectures?
5. Explain the concept of instruction-level parallelism (ILP) and how it is exploited in modern processors.
6. What is the role of a branch predictor in a processor, and how does it help in reducing pipeline stalls?
7. How do out-of-order execution and speculation help in improving the performance of a processor?
8. What is the difference between symmetric multiprocessing (SMP) and asymmetric multiprocessing (AMP) architectures?
9. What is the role of DMA (Direct Memory Access) in a computer system?
10. How do virtual memory and paging work in a computer system?


#### CPU architecture graph

```
                        Computer Architectures
                                |
                +---------------+----------------+
                |                                |
          Von Neumann                 Harvard Architecture
                |
         +------+-------+
         |              |
    RISC Architecture   CISC Architecture
         |                |
         |          +-----+-----+
         |          |           |
   ARM Architecture   x86        Power Architecture
         |                          |
  +------+-----+               +----+-----+
  |            |               |          |
MIPS     SPARC Architecture   IBM      Motorola
```

### Builtin data types in different programming languages

| Language | Data Type | Description | Memory Footprint |
| --- | --- | --- | --- |
| C | char | Character | 1 byte |
|  | signed char | Signed character | 1 byte |
|  | unsigned char | Unsigned character | 1 byte |
|  | int | Integer | 4 bytes |
|  | signed int | Signed integer | 4 bytes |
|  | unsigned int | Unsigned integer | 4 bytes |
|  | short | Short integer | 2 bytes |
|  | signed short | Signed short integer | 2 bytes |
|  | unsigned short | Unsigned short integer | 2 bytes |
|  | long | Long integer | 8 bytes |
|  | signed long | Signed long integer | 8 bytes |
|  | unsigned long | Unsigned long integer | 8 bytes |
|  | long long | Long long integer | 8 bytes |
|  | signed long long | Signed long long integer | 8 bytes |
|  | unsigned long long | Unsigned long long integer | 8 bytes |
|  | float | Floating-point number | 4 bytes |
|  | double | Double-precision floating-point number | 8 bytes |
|  | long double | Extended precision floating-point number | 16 bytes |
|  | void | Represents the absence of type | N/A |
|  | _Bool | Boolean | 1 byte |
| C++ | char | Character | 1 byte |
|  | signed char | Signed character | 1 byte |
|  | unsigned char | Unsigned character | 1 byte |
|  | int | Integer | 4 bytes |
|  | signed int | Signed integer | 4 bytes |
|  | unsigned int | Unsigned integer | 4 bytes |
|  | short | Short integer | 2 bytes |
|  | signed short | Signed short integer | 2 bytes |
|  | unsigned short | Unsigned short integer | 2 bytes |
|  | long | Long integer | 8 bytes |
|  | signed long | Signed long integer | 8 bytes |
|  | unsigned long | Unsigned long integer | 8 bytes |
|  | long long | Long long integer | 8 bytes |
|  | signed long long | Signed long long integer | 8 bytes |
|  | unsigned long long | Unsigned long long integer | 8 bytes |
|  | float | Floating-point number | 4 bytes |
|  | double | Double-precision floating-point number | 8 bytes |
|  | long double | Extended precision floating-point number | 16 bytes |
|  | void | Represents the absence of type | N/A |
|  | bool | Boolean | 1 byte |
|  | wchar_t | Wide character | 2 or 4 bytes |
|  | char16_t | UTF-16 character | 2 bytes |
|  | char32_t | UTF-32 character | 4 bytes |
|  | string | String | Implementation dependent |
|  | wstring | Wide string | Implementation dependent  |
| Python | bool | Boolean | 1 byte |
|  | int | Integer | Implementation dependent |
|  | float | Floating-point number | Implementation dependent |
|  | complex | Complex number | Implementation dependent |
|  | str | String | Implementation dependent |
|  | bytes | Bytes | Implementation dependent |
|  | bytearray | Mutable bytes | Implementation dependent |
|  | list | List | Implementation dependent |
|  | tuple | Tuple | Implementation dependent |
|  | set | Set | Implementation dependent |
|  | frozenset | Frozen set | Implementation dependent |
|  | dict | Dictionary | Implementation dependent |
|  | NoneType | Represents the absence of a value | N/A |
| C# | sbyte | Signed 8-bit integer | 1 byte |
|  | byte | Unsigned 8-bit integer | 1 byte |
|  | short | Signed 16-bit integer | 2 bytes |
|  | ushort | Unsigned 16-bit integer | 2 bytes |
|  | int | Signed 32-bit integer | 4 bytes |
|  | uint | Unsigned 32-bit integer | 4 bytes |
|  | long | Signed 64-bit integer | 8 bytes |
|  | ulong | Unsigned 64-bit integer | 8 bytes |
|  | float | Floating-point number | 4 bytes |
|  | double | Double-precision floating-point number | 8 bytes |
|  | decimal | Decimal number | 16 bytes |
|  | bool | Boolean | 1 byte |
|  | object | Base class for all other types | Implementation dependent |
|  | string | String | Implementation dependent |
|  | dynamic | Represents an object whose operations will be resolved at runtime | Implementation dependent |
|  | var | Implicitly-typed local variable | Implementation dependent |
|  | void | Represents the absence of type | N/A |