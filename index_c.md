## Comprehensive List of C Topics

**I. C Fundamentals**

1.  **Introduction:**
    *   History & evolution of C.
    *   Use-cases: Systems programming, embedded, compilers, tooling.
    *   Setting up the environment: Compilers (GCC, Clang, MSVC), IDEs, build tools (Make, CMake).
2.  **Basic Syntax:**
    *   Structure of a C program (`#include`, `int main(void)`, braces).
    *   Statements & expressions; semicolon terminator.
    *   Comments (`//`, `/* … */`).
3.  **Data Types & Variables:**
    *   Fundamental types: `char`, `short`, `int`, `long`, `float`, `double`, `_Bool`.
    *   Modifiers: `signed`, `unsigned`, `short`, `long long`.
    *   Qualifiers: `const`, `volatile`, `restrict`, `_Atomic`.
    *   Derived types: arrays, pointers, structures, unions, enumerations.
    *   Type conversions & promotions.
4.  **Operators:**
    *   Arithmetic, assignment, relational, logical, bitwise, conditional (`?:`), comma, `sizeof`.
    *   Operator precedence & associativity.
5.  **Input / Output:**
    *   Formatted I/O: `printf`, `scanf`, format specifiers.
    *   Character & string I/O (`getchar`, `putchar`, `fgets`, `puts`).

**II. Control Flow**

6.  **Selection Statements:** `if`, `else`, `switch`, `case`, `default`.
7.  **Iteration Statements:** `for`, `while`, `do-while`.
8.  **Jump Statements:** `break`, `continue`, `goto`, `return`.

**III. Functions**

9.  **Function Prototypes & Definitions.**
10. **Parameter Passing (by value) & Returning Values.**
11. **Variable Scope & Storage Classes:** `auto`, `static`, `extern`, `register`.
12. **Inline Functions (`inline`) & Macros (`#define`).**

**IV. Pointers & Memory Management**

13. **Pointer Basics, Pointer Arithmetic.**
14. **Arrays & Pointers Relationship.**
15. **Strings:** `char *` vs `char[]`, common string functions.
16. **Dynamic Memory Allocation:** `malloc`, `calloc`, `realloc`, `free`.
17. **Common Pitfalls:** Dangling pointers, memory leaks, double-free.
18. **Function Pointers & Callback Mechanisms.**

**V. Complex Data Types**

19. **Structures (`struct`):** Declaration, initialization, nested structs, bit-fields.
20. **Unions (`union`):** Memory overlay use-cases.
21. **Enumerations (`enum`).**
22. **Typedefs & Opaque Pointers.**

**VI. The Preprocessor**

23. **Header Files & Inclusion Guards (`#ifndef …`).**
24. **Macros with Parameters, Stringizing (`#`), Token Pasting (`##`).**
25. **Conditional Compilation:** `#if`, `#ifdef`, `#ifndef`, `#elif`, `#else`, `#endif`.
26. **Pragmas and Compiler-specific Extensions.**

**VII. File I/O & Streams**

27. **The `FILE` Structure, `fopen`, `fclose`.**
28. **Text vs. Binary Mode.**
29. **Random Access:** `fseek`, `ftell`, `rewind`.
30. **Error Handling:** `feof`, `ferror`, `perror`.

**VIII. Compilation & Build Process**

31. **Compilation Stages:** Preprocessing → Compilation → Assembly → Linking.
32. **Object Files & Libraries:** Static (`.a/.lib`), Shared (`.so/.dll`).
33. **Makefiles & Build Flags (`-Wall`, `-O`, `-std=c11`).**
34. **Debugging Symbols & Debuggers (`gdb`, `lldb`).**

**IX. Standard Library & Headers**

35. **Core Headers:** `stdio.h`, `stdlib.h`, `string.h`, `ctype.h`, `math.h`, `time.h`, `assert.h`, `errno.h`, `signal.h`, `setjmp.h`, `stdarg.h`.

**X. Error Handling & Diagnostics**

36. **Return Codes & `errno`.**
37. **Assertions.**
38. **Signals (`signal`, `sigaction`).**

**XI. Advanced Topics**

39. **Bitwise Operations & Bit Manipulation.**
40. **Memory Alignment & Padding.**
41. **Endianness Considerations.**
42. **Volatile & Memory-mapped I/O.**
43. **Concurrency Primitives:** POSIX threads basics (`pthread_create`, `pthread_join`).
44. **C11 Threads (`<threads.h>`), Atomics (`<stdatomic.h>`).**
45. **Generic Selections (`_Generic`) & Type-generic Macros.**
46. **Dynamic & Static Library Creation, Linker Scripts.**

**XII. Portability & Standards**

47. **ANSI C (C89/C90), C99, C11, C17 Differences.**
48. **Undefined & Implementation-defined Behavior.**
49. **Compiler-specific Attributes & Pragmas.**

**XIII. Best Practices**

50. **Coding Style Guides (K&R, GNU, Linux).**
51. **Commenting & Documentation (Doxygen).**
52. **Defensive Programming & Error Checking.**
53. **Unit Testing Frameworks (Unity, CMocka).**
54. **Static Analysis & Sanitizers (`valgrind`, ASan, UBSan, clang-tidy).**
55. **Continuous Integration & Code Review.**

**XIV. Common Application Areas**

56. **Embedded Systems & Microcontrollers.**
57. **Operating Systems & Kernel Development.**
58. **Compilers & Interpreters.**
59. **Networking & Sockets.**
60. **Scientific & High-performance Computing.**

**XV. Resources & Ecosystem**

61. **Key References:** "The C Programming Language" (K&R), C Standard drafts.
62. **Open-source Libraries:** libcurl, OpenSSL, zlib, GLib.
63. **Package Managers & Build Helpers:** Conan, vcpkg, cget.
