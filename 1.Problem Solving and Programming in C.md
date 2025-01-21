# Problem Solving and Programming in C

## Topics:

1. Basics of Programming
2. Data Types and Operators
3. Control Structures
4. Functions
5. Arrays and Strings
6. Pointers
7. Structures and Unions
8. File Handling

## Questions and Answers:

### 1. Basics of Programming

#### Question: What is a program?

    A program is a sequence of instructions executed by a computer to perform a specific task.

#### Question: What is a compiler?

    A compiler is a program that translates source code into machine language that the computer can execute.

### 2. Data Types and Operators

#### Question: What are primitive data types in C?

    Primitive data types in C are `int`, `char`, `float`, and `double`.

#### Question: What is the difference between `=` and `==` operators?

    `=` is an assignment operator that assigns a value to a variable, while `==` is a comparison operator that checks if two values are equal.

### 3. Control Structures

#### Question: What is an `if` statement?

    An `if` statement is used to check a condition and execute instructions if the condition is true.

#### Question: What is a `for` loop?

    A `for` loop is used to execute a statement or a block of statements a specific number of times.

### 4. Functions

#### Question: What is a function in C?

    A function is a block of code that performs a specific task and can be called when needed.

#### Question: How do you define a function in C?

    A function is defined with the return type, function name, and parameters, e.g., `int add(int a, int b) { return a + b; }`.

### 5. Arrays and Strings

#### Question: What is an array?

    An array is a collection of elements of the same data type stored in contiguous memory locations.

#### Question: How do you define a string in C?

    A string in C is an array of `char` elements that ends with a null character (`\0`).

### 6. Pointers

#### Question: What is a pointer?

    A pointer is a variable that stores the address of another variable.

#### Question: How do you declare a pointer in C?

    A pointer is declared with the `*` operator, e.g., `int *ptr;`.

### 7. Structures and Unions

#### Question: What is a structure in C?

    A structure is a user-defined data type that groups different data types.

#### Question: What is the difference between a structure and a union?

    In a structure, all members have different memory locations, while in a union, all members share the same memory location.

### 8. File Handling

#### Question: How do you open a file in C?

    A file is opened with the `fopen` function, e.g., `FILE *fp = fopen("file.txt", "r");`.

#### Question: How do you read data from a file in C?

    Data is read from a file using the `fscanf` or `fgets` function.

### 9. Additional Questions

#### Question: What is the difference between `malloc` and `calloc`?

    `malloc` allocates a block of memory and returns a pointer to it, while `calloc` allocates memory for an array of elements and initializes the memory to zero.

#### Question: What is a header file in C?

    A header file contains declarations of functions and macros that can be used in multiple source files.

#### Question: What is a recursive function?

    A recursive function is a function that calls itself to solve a problem.

#### Question: What is the difference between `break` and `continue`?

    `break` terminates the loop entirely, while `continue` skips the current iteration and proceeds with the next iteration.

#### Question: What is a null pointer?

    A null pointer is a pointer that does not point to any valid memory address.

#### Question: What is the difference between `struct` and `typedef struct`?

    `struct` defines a structure, while `typedef struct` defines a new data type name for the structure.

#### Question: How do you free memory allocated with `malloc`?

    Memory allocated with `malloc` is freed using the `free` function.

#### Question: What is a macro in C?

    A macro is a pre-defined instruction that is replaced by the preprocessor before the actual compilation begins.

#### Question: What is the difference between `#include <filename>` and `#include "filename"`?

    `#include <filename>` is used for system headers, while `#include "filename"` is used for user-defined header files.

#### Question: What is a union in C?

    A union is a data type that can store different data types at the same memory location.

#### Question: What is the difference between `++i` and `i++`?

    `++i` increments the value of `i` and returns the new value, while `i++` returns the current value of `i` and then increments `i`.

#### Question: What is a bitmask?

    A bitmask is a sequence of bits used to isolate or manipulate specific bits in a bit sequence.

#### Question: What is the difference between `fgets` and `gets`?

    `fgets` reads a line from a stream and checks the buffer boundary, while `gets` reads a line from `stdin` without checking the buffer boundary (unsafe).

#### Question: What is a preprocessor in C?

    A preprocessor is a program that processes macros and directives before the actual compilation.

#### Question: What is the difference between `sizeof` and `strlen`?

    `sizeof` returns the size of a data type or variable in bytes, while `strlen` returns the length of a string in characters.

#### Question: What is a function pointer?

    A function pointer is a pointer that points to a function and can be used to call the function.

#### Question: What is the difference between `exit` and `_exit`?

    `exit` performs cleanup operations and terminates the program, while `_exit` terminates the program immediately without cleanup.

#### Question: What is an enumeration data type?

    An enumeration data type is a user-defined data type that defines a set of named integer constants.

#### Question: What is the difference between `memcpy` and `memmove`?

    `memcpy` copies memory blocks without considering overlaps, while `memmove` copies memory blocks and handles overlaps.

#### Question: What is a static array?

    A static array has a fixed size determined at compile time.

#### Question: What is a dynamic array?

    A dynamic array has a size determined at runtime and can be allocated with `malloc` or `calloc`.

#### Question: What is the difference between `printf` and `sprintf`?

    `printf` outputs formatted data to the screen, while `sprintf` stores formatted data in a string.

#### Question: What is a segmentation fault?

    A segmentation fault occurs when a program tries to access an invalid memory area.

#### Question: What is the difference between `fork` and `exec`?

    `fork` creates a new process, while `exec` executes a new program in the current process.

#### Question: What is a deadlock?

    A deadlock occurs when two or more processes wait for resources held by the other processes, preventing any of them from proceeding.

#### Question: What is the difference between `malloc` and `realloc`?

    `malloc` allocates memory, while `realloc` changes the size of an already allocated memory block.

#### Question: What is a stack overflow?

    A stack overflow occurs when a program's stack memory is exhausted, usually due to too many nested function calls.

#### Question: What is the difference between local and global variables?

    Local variables are defined within a function and are only visible there, while global variables are defined outside all functions and are visible throughout the program.

#### Question: What is an inline function?

    An inline function is a function that the compiler embeds directly into the code instead of making a function call, reducing call overhead.

#### Question: What is the difference between `volatile` and `const`?

    `volatile` tells the compiler not to optimize a variable because it can change outside the program, while `const` declares a variable as immutable.

#### Question: What is a macro with arguments?

    A macro with arguments is a macro that accepts parameters and can be used like a function, e.g., `#define SQUARE(x) ((x) * (x))`.

#### Question: What is the difference between `union` and `struct`?

    In a `union`, all members share the same memory space, while in a `struct`, each member has its own memory space.

#### Question: What is a pointer to a function?

    A pointer to a function is a pointer that points to the memory location of a function and can be used to call the function.

#### Question: What is the difference between `static` and `extern`?

    `static` restricts the scope of a variable or function to the file in which it is defined, while `extern` declares a variable or function in another file.

#### Question: What is a preprocessor directive?

    A preprocessor directive is an instruction processed by the preprocessor before the actual compilation, e.g., `#define`, `#include`.

#### Question: What is the difference between `fopen` and `freopen`?

    `fopen` opens a file, while `freopen` opens a file and redirects an existing stream.

#### Question: What is a pointer to an array?

    A pointer to an array is a pointer that points to the first memory location of an array.

#### Question: What is the difference between `strcpy` and `strncpy`?

    `strcpy` copies a string without checking the buffer boundary, while `strncpy` copies a string and considers the buffer boundary.

#### Question: What is a function prototype?

    A function prototype is a declaration of a function that specifies the return type and parameters of the function.

#### Question: What is the difference between `fprintf` and `fscanf`?

    `fprintf` writes formatted data to a stream, while `fscanf` reads formatted data from a stream.

#### Question: What is a pointer to a structure?

    A pointer to a structure is a pointer that points to the memory location of a structure and can be used to access the members of the structure.
