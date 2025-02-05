---
Title: "cbrt()"
Subjects:
  - "Computer Science"
Tags:
  - "Functions"
  - "Arithmetic"
Catalog Content:
  - "https://www.codecademy.com/learn/learn-c-plus-plus"
  - "https://www.codecademy.com/learn/paths/computer-science"
---

## Definition

Returns the cube root of the argument.

## Syntax

```cpp
std::cbrt(n)
```

## Example 1

Use `cbrt()` to return the cube root of `27`:

```cpp
#include <iostream>
#include <cmath>

int main() {
  double x = 27;
  double result;

  result = std::cbrt(x);

  std::cout << "The cube root of " << x << " is " << result << "\n";
  // Output: The cube root of 27 is 3
}
```
