## Comprehensive List of C++ Topics

**I. C++ Fundamentals**

1.  **Introduction & History:**
    *   Evolution from C to C++.
    *   ISO Standards: C++98/03, C++11, C++14, C++17, C++20, C++23.
    *   Paradigms: Procedural, Object-Oriented, Generic, Functional.
2.  **Toolchain Setup:**
    *   Compilers (GCC, Clang, MSVC, ICC), Standard Library (libstdc++, libc++).
    *   Build systems (Make, CMake, Meson), Package managers (vcpkg, Conan).
    *   IDEs/Editors & Debuggers (GDB, LLDB).
3.  **Lexical Structure:**
    *   Tokens, identifiers, keywords, comments.
    *   Namespaces & `using` directive.
4.  **Basic Syntax & Types:**
    *   Fundamental types: `bool`, `char`, `int`, `float`, `double`, `wchar_t`, char8/16/32 (C++20).
    *   Type modifiers: `signed`, `unsigned`, `short`, `long`, `long long`.
    *   Aliases: `typedef`, `using`.
5.  **Operators & Expressions:**
    *   Arithmetic, relational, logical, bitwise, assignment, `sizeof`, `decltype`, `typeid`, `? :`.
    *   Operator precedence & overloading.
6.  **Input/Output:**
    *   Streams (`std::cin`, `std::cout`, `std::cerr`, `std::clog`).
    *   File streams (`std::ifstream`, `std::ofstream`, `std::fstream`).

**II. Control Flow**

7.  **Conditionals:** `if`, `switch`, `?:`.
8.  **Loops:** `for`, range-based `for` (C++11), `while`, `do-while`.
9.  **Jump:** `break`, `continue`, `return`, `goto`.

**III. Functions & Modules**

10. **Function Basics:** Declarations, definitions, default arguments, `inline`.
11. **Function Overloading & Name Mangling.**
12. **Templates (Generic Programming):**
    *   Function templates, class templates.
    *   Template specialization & partial specialization.
    *   Variadic templates, fold expressions (C++17).
13. **Lambda Expressions (C++11+):** Syntax, capture lists, mutable lambdas, generic lambdas (C++14).
14. **Modules (C++20).**

**IV. Object-Oriented Programming**

15. **Classes & Objects:** Members, methods, access specifiers.
16. **Constructors, Destructors & Rule of 0/3/5/0.**
17. **Copy/Move Semantics:** Copy/move constructor, assignment operator, Rvalue references.
18. **Inheritance:** Single, multiple, virtual inheritance.
19. **Polymorphism:** Virtual functions, dynamic dispatch, `override`, `final`.
20. **Interfaces & Abstract Classes.**
21. **Operator Overloading & Conversions.**
22. **Encapsulation, `friend`, `mutable`.**

**V. Memory Management**

23. **Fundamentals:** Stack vs. heap.
24. **Raw Pointers & `new`/`delete`, `new[]`/`delete[]`.**
25. **Smart Pointers:** `std::unique_ptr`, `std::shared_ptr`, `std::weak_ptr`, `std::make_unique`, `std::make_shared`.
26. **RAII (Resource Acquisition Is Initialization).**
27. **Move Semantics, Perfect Forwarding (`std::forward`, `std::move`).**
28. **Memory Alignment & Placement New.**

**VI. The Standard Library (STL)**

29. **Containers:** `vector`, `deque`, `list`, `forward_list`, `array`, `bitset`, `set`, `multiset`, `map`, `multimap`, `unordered_*`.
30. **Iterators & Algorithms:** iterator categories, `std::algorithm`, ranges (C++20) & views.
31. **Functional:** `std::function`, function objects, binders (`std::bind`), functors.
32. **Utility:** `std::pair`, `std::tuple`, `std::variant` (C++17), `std::optional` (C++17), `std::any` (C++17).
33. **Chrono, Ratio, Random, Regex, Numeric.**
34. **Concurrency:** `std::thread`, mutexes, condition variables, futures/promises, atomics (`std::atomic`), latches & barriers (C++20), `std::jthread` (C++20), coroutines (C++20).
35. **Filesystem (`<filesystem>` C++17).**

**VII. Advanced Language Features**

36. **SFINAE, Concepts (C++20), Enable_if, Type Traits.**
37. **Constexpr (Compile-time) & `consteval` (C++20).
38. **Inline Namespaces, ADL (Argument-dependent Lookup).**
39. **NRVO, copy elision, `std::move_if_noexcept`.**
40. **Metaprogramming & Template Metaprogramming (TMP).**
41. **Multithreading Memory Model & `std::memory_order`.**
42. **Modules vs Headers, PIMPL Idiom.**

**VIII. Error Handling & Diagnostics**

43. **Exceptions:** `try`, `catch`, `throw`, exception specifications (`noexcept`).
44. **Error Codes & Expected (`std::expected` C++23), `std::error_code`, `std::error_condition`.**
45. **Assertions (`assert`), Contracts (planned).**
46. **Logging & Diagnostics Libraries (spdlog, Boost.Log).**

**IX. Build & Tooling**

47. **Compilation model, header inclusion & ODR.**
48. **Linking, static & dynamic libraries, visibility (`-fvisibility=hidden`).**
49. **Precompiled Headers, Unity Builds.**
50. **Build Flags:** `-std=c++20`, `-Wall`, `-Wextra`, `-O2`, `-g`, `-fsanitize`.**
51. **Debugging & Profiling:** GDB, Valgrind, perf, gprof, Sanitizers.
52. **Package/Dependency Managers (Conan, vcpkg).**

**X. Best Practices & Guidelines**

53. **C++ Core Guidelines, Effective C++ items.**
54. **Modern C++ Principles: Prefer RAII, use smart pointers, avoid raw `new`.**
55. **Code Readability & Style (Google style, LLVM).**
56. **Unit Testing (Google Test, Catch2, doctest).**
57. **Static Analysis (clang-tidy, cppcheck, sanitizers), CI pipelines.**

**XI. Common Libraries & Ecosystem**

58. **Boost (selected libraries).**
59. **Qt (GUI, application framework).**
60. **Poco, Folly, Abseil, Protobuf, gRPC, OpenCV.**

**XII. Application Areas**

61. **Game Development (Unreal Engine, SDL).**
62. **High-performance Computing, Finance, Scientific Research.**
63. **Embedded & Automotive.**
64. **Cross-platform Desktop Applications.**

**XIII. Resources**

65. **Books:** "Effective Modern C++", "Accelerated C++", "C++ Primer", "The C++ Programming Language".
66. **Online References:** cppreference.com, ISO Drafts.**
