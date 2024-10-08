# 42Ft_printf
My project Ft_printf from School 42</br>
Final grade: 100/100

![42Ft_printf-cover](cover-ft_printf-bonus.png)

<table>
  <tr><td>Program name</td><td>libftprintf.a</td></tr>
  <tr><td>Turn in files</td><td>Makefile, *.h, */*.h, *.c, */*.c</td></tr>
  <tr><td>Makefile</td><td>NAME, all, clean, fclean, re</td></tr>
  <tr><td>External functions</td><td>malloc, free, write, va_start, va_arg, va_copy, va_end</td></tr>
  <tr><td>Libft authorized</td><td>Yes</td></tr>
  <tr><td>Description</td><td>Write a library that contains ft_printf(), a function that will mimic the original printf()</td></tr>
</table>

## Mandatory Part

You have to recode the printf() function from libc.
The prototype of ft_printf() is:
int ft_printf(const char *, ...);
Here are the requirements:
* Don’t implement the buffer management of the original printf().
* Your function has to handle the following conversions: cspdiuxX%
* Your function will be compared against the original printf().
* You must use the command ar to create your library. Using the libtool command is forbidden.
* Your libftprintf.a has to be created at the root of your repository.

You have to implement the following conversions:
* %c Prints a single character.
* %s Prints a string (as defined by the common C convention).
* %p The void * pointer argument has to be printed in hexadecimal format.
* %d Prints a decimal (base 10) number.
* %i Prints an integer in base 10.
* %u Prints an unsigned decimal (base 10) number.
* %x Prints a number in hexadecimal (base 16) lowercase format.
* %X Prints a number in hexadecimal (base 16) uppercase format.
* %% Prints a percent sign.

## Bonus Part

You don’t have to do all the bonuses.

Bonus list:
* Manage any combination of the following flags: ’-0.’ and the field minimum width under all conversions.
* Manage all the following flags: ’# +’ (Yes, one of them is a space)

<img align="right" src="ft_printfe.png">
