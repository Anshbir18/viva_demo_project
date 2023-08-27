# CUtilLib: Efficient String and Integer Manipulation

[![Version](https://img.shields.io/badge/version-1.0.0-blue)](https://github.com/yourusername/cutillib/releases)


CUtilLib is a powerful static library written in C, designed to simplify string and integer manipulation tasks. With a focus on efficiency and simplicity, this library equips developers with essential tools for performing common operations involving strings and integers. From substring searches to palindrome detection, CUtilLib offers a comprehensive suite of functionalities.

## Features

### String Operations

- **Search**: Locate substrings within strings efficiently.
- **Sort**: Arrange characters in strings in lexicographical order.
- **Anagram Detection**: Identify anagrams among strings.
- **Palindrome Detection**: Detect palindromes within strings.
- **Frequency Count**: Count character occurrences in strings.

### Integer Operations

- **Addition**: Easily perform integer addition for arithmetic calculations.

- **Subtraction**: Execute integer subtraction for various mathematical computations.

- **Multiplication**: Utilize fast multiplication algorithms to efficiently multiply integers, ensuring optimal usage.

- **Division**: Perform division operations on integers, providing accurate results for mathematical operations.

- **Even/Odd Check**: Determine whether an integer is even or odd, assisting in various logic and program flow.

- **Power of 2 Check**: Quickly determine if an integer is a power of 2, a critical analysis for memory and performance evaluations.


### Integer Array Operations

- **Find Middle**: Quickly discover the middle element of integer arrays, an essential step in various algorithms involving data partitioning.

- **Sort**: Effortlessly organize integer arrays in ascending order using the most optimal algorithm, ensuring efficient searching and organized data presentation.

- **Search**: Efficiently search for specific elements within integer arrays, employing well-optimized search techniques for rapid data retrieval.

## Installation

To include CUtilLib in your project, follow these steps:

1. Clone the repository: `git clone https://github.com/yourusername/cutillib.git`
2. Navigate to the library directory: `cd cutillib`
3. Compile the library: `gcc -c cutil.c -o cutil.o`
4. Create the static library: `ar rcs libcutil.a cutil.o`

## Usage

1. Include the library header in your C code: `#include "cutil.h"`
2. Link your program with the static library: `-L/path/to/library -lcutil`

## Examples

Here are some simple examples showcasing CUtilLib's capabilities:

```c
#include <stdio.h>
#include "cutil.h"

int main() {
    // String operations
    char str[] = "radar";
    if (isPalindrome(str)) {
        printf("The string is a palindrome.\\n");
    } else {
        printf("The string is not a palindrome.\\n");
    }

    // Integer operations
    int num = 8;
    if (isPowerOf2(num)) {
        printf("%d is a power of 2.\\n", num);
    } else {
        printf("%d is not a power of 2.\\n", num);
    }

    return 0;
}
```
## Contributing

Contributions to CUtilLib are welcome! Whether you've found a bug or have an idea for a new feature, we encourage you to get involved. Here's how you can contribute:

- **Bug Reports**: If you encounter any issues with CUtilLib, please [open an issue](https://github.com/yourusername/cutillib/issues) on GitHub. Provide as much detail as possible to help us understand and address the problem.

- **Feature Requests**: If you have an idea for a new feature or enhancement, feel free to share it by [opening an issue](https://github.com/yourusername/cutillib/issues). We value your input and will consider your suggestions.

- **Pull Requests**: If you're technically inclined, you can submit a pull request to improve CUtilLib. Fork the repository, make your changes, and then create a pull request. We'll review your contribution and work together to integrate it.



