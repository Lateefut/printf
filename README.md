This is the Repository descriptive of the Project contains incrementation of our printf function.

For this project we wrote own `printf` function. It is the first group project for ALX Software Engineering program @Holberton School. Our version of `printf` currently handles the following conversion specifiers:

| Symbol | Operation |
|--|--|
| `c` | Prints character |
| `s` | Prints string |
| `%` | Prints modulus operator |
| `d` | Prints integer |
| `i` | Also prints integer |
| `h` | Converts from decimal and prints lowercase hexadecimal |
| `H` | Converts from decimal and prints lowercase hexadecimal |
| `r` | Reverses and prints string |
| `R` | Encodes and prints string using `rot13` |

 
*Bring your own main file.* To use our `printf` you will need a `main.c` file to compile it with. Go ahead and try the following:
```
int main(void)
{
	_printf("%c\n", 'H');
	_printf("%s\n", "Hello");
	_printf("%d\n", 42);
	_printf("%i\n", -42);
	_printf("%r\n", "Hello");
	_printf("%R\n", "Hello");
	return (0);
}


# Tasks

* 0 Write a function that produces output according to format.
    converts input into a character: - c
    converts input into a string: - s

* 1 Handle the following conversion specifiers
    converts input into a base 10 integer: - d
    converts input into an integer: - i

* 2 Create a man page for your function

* 3 Handle the following conversion specifiers
    The unsigned int argument is converted to binary: - b

* 4 Handle the following conversion specifiers
    converts the input into an unsigned integer: - u
    converts the input into an octal number: - o
    converts the input into a hexadecimal number: - x
    converts the input into a hexadecimal number with capital letters: - x

* 5 Use a local buffer of 1024 chars in order to call write as little as possible.

* 6 Handle the following custom conversion specifier
    prints the string: - s
    Non printable characters (0 < ASCII value < 32 or >= 127) are printed this way: \x, followed by the ASCII code value in hexadecimal (upper case - always 2 characters)

* 7 Handle the following conversion specifier
  int input is converted to a pointer address: - p

* 8 Handle the following flag characters for non-custom conversion specifiers
  - \+ : adds a \+ in front of signed positive numbers and a \- in front of signed negative numbers
  - space : same as \+, but adds a space (is overwritten by \+)
  - \# : adds a 0 in front of octal conversions that don't begin with one, and a 0x or 0X for x or X conversions

* 9 Handle the following length modifiers for non-custom conversion specifiers
    converts d, i, u, o, x, X conversions in short signed or unsigned ints: l
    converts d, i, u, o, x, X conversions in long signed or unsigned ints: h

* 10 Handle the field width for non-custom conversion specifiers.

* 11 Handle the precision for non-custom conversion specifiers.

* 12 Handle the 0 flag character for non-custom conversion specifiers.

* 13 Handle the - flag character for non-custom conversion specifiers.

* 14 Handle the following custom conversion specifier
  prints the reversed string: - r

* 15 Handle the following custom conversion specifier:
     prints the rot13'ed string: - R

* 16 All the above options work well together.
