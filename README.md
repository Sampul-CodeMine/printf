# `printf` PROJECT &copy; ALX SE PROGRAMME

In the early days of computer programming, developers/software programmers wrote their our modules and functions to perform certain tasks. This made them honoured and fit to be exteemed programmers.

In our journey through **ALX**, we would be designing a customed made `printf` function, not to re-invent the wheels in programming , but to test our capabilties as Software Developers or Engineers.

Before we dive deep into the project, we would love to look at `printf` and some concepts behind how it works.

## What is the `printf` function?

`printf` is a very powerful function designed to send **formatted strings as output to the standard output device - The monitor or rather the display unit.** The `printf` function does not just function on its own, rather its definitiion is prototyped in the `stdio.h` **"Standard Input/Output header file".** This is the reason why you have to include it in the file or project from which you would like to use the `printf` function.

## How does the `printf` function work?

The `printf` function works in different ways which will be highlighted briefly. But foremost to note, is that the `printf` function iterates through the parameters passed. If there are no format specifiers or special escape characters, it will print the characters one at a time and at the end returns the length of the characters printed.

If there were escape characters or format specifiers passed to the printf function, the compiler look out for the type of format and then look out for the data passed for that format type.


- Simple Printing
- Printing Special Characters
- Printing with Format Specifiers
- Printing with Width option
- Printing Percent
- Printing Floats
- Printing Strings
- Printing Integers etc.
- 
### [Simple Printing](#simple)

In the most simple case, the `printf` function can be used to print strings without passing parameters. An example is thus:

```c
#include <stdio.h>

int main(void)
{
        printf("Hello World!");
        return (0);
}
// this will print Hello World! after compilation.
```

**Some Escape Characters**
| Format | What they Do |
| :----- | :------------|
| \a | produces an audible bell alert |
| \b | This creates a backspace (delete backwards) |
| \f | form feeds |
| \n | creates a new line |
| \n | carriage return |
| \t | vertical tab |
| \v | horizontal tab |
| \  | single backslash escapes the next character |
| \\\ | this prints a backslash |
| "  | single double quotation starts or ends a string datatype |
| \\" | this prints a double quotation mark |
| '  | single quotation mark starts or ends a character datatype |
| \\' | this prints a single quotation mark |
| %  | this starts a definition of a format specification |
| \\% | this prints a percentage sign |

