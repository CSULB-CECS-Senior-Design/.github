# Coding Style Guide

## General Guidelines

### Indentations
- Use 1 tab for indentation.

### Variable Names
- Use Camel Case.
  - C/C++/Swift: `int totalCount;`
  - Python: `totalCount = 0`

### Functions
- Use Snake Case.
  - C/C++: `void calculate_total()`
  - Python/Swift: `def calculate_total()`

### Classes
- Use Pascal Case.
  - C/C++/Swift: `class Car { ... }`
  - Python: `class Car: ...`

### Preprocessor Directives (C/C++ only)
- Use All Caps.
  - `#define MAX_COUNT 100`

### Header Guards (C/C++ only)
- Use All Caps.
  - `#ifndef HEADER_H`
  - `#define HEADER_H`
  - `#endif`

### Import Statements
- Do not simplify imported modules.
  - C/C++: Avoid `using namespace std;`
  - Python: Prefer `import math` over `from math import *`
  - Swift: Use explicit module names.

## Conditional Statements

### Sequential 1-Liner If-Else
- Write single operation if-else statements on separate lines without braces.
```c++
if (condition)
    doSomething();
else if (anotherCondition)
    doAnotherThing();
else
    doElseThing();
```
### Multi-Operation If-Else
- Use braces for if-else statements with more than one operation.
```cpp
if (condition) {
    doFirstThing();
} else if (anotherCondition) {
    doSecondThing();
    doThirdThing();
} else {
    doFourthThing();
    doFifthThing();
}
```


This guide should provide a clear and unified coding style for your projects in C/C++, Python, and Swift. It emphasizes readability and consistency across different languages, which is particularly beneficial in a multi-language environment.
