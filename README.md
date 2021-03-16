# Printf
> _printf is a custom implementation of the native C printf function. This version of printf prints strings, characters, numbers and It will print a reversed string.

## Environment
Printf was developed and tested with `Ubuntu 14.04 LTS`

## Installing/ Getting Started
Clone the repository, and create a main.c file, compile, and run the executable.
```
$ git clone https://github.com/Tayeb95/printf.git
```
#### Example main.c and output
```
#include "holberton.h"

int main(void)
{
	_printf("Hello %s\n", "World");
	return (0);
}
=========================================
$ gcc -Wall -Wextra -Werror -pedantic -Wno-format *.c *.h -o printf
$ ./printf
$ Hello World
$
```

#### Key:

% +

- c - char
- d - digit
- i - integers
- s - string
- r - reverse string

## File Contents

|   **File**   |   **Description**   |
| -------------|---------------------|
| \_printf.c |  printf function |
| holberton.h   | Header file containing all function prototypes and struct declarations |
| functionsofprintf.c  | File containing main print functions |

## Function Descriptions
| **Function** | **Description** |
| -------------- | ----------------- |
|int print(char c)| Writes a character to stdout|
|int printstring(va_list list)|Prints strings|
|int printchar(va_list list)|Prints a character|
|int printint(va_list list)|Prints integers|
|int printbinary(va_list)|Prints numbers in binary|
|int printrev(va_list list)|Prints a reverse string|

### Done by

* [**Mohammed Jbeli**](https://github.com/medjbelii)
* [**Altayeb Elzowawi**](https://github.com/Tayeb95)
