# ft_putnbr

# FT_PUTNBR Function

This repository hosts the implementation of the `ft_putnbr` function, a custom utility designed for displaying numbers by printing each digit as a character to the standard output. Accompanied by the `ft_putchar` function, which writes a single character to the standard output, `ft_putnbr` provides a basic but essential functionality for numeric output without relying on higher-level standard library functions like `printf`.

## Overview

The `ft_putnbr` function takes an integer `nb` as its parameter and recursively breaks it down into individual digits. These digits are then converted to their ASCII character equivalents and outputted using the `ft_putchar` function. This method allows for the representation of any 32-bit signed integer, handling edge cases like the minimum representable value (`-2147483648`) explicitly.

## Usage
The ft_putnbr function is particularly useful in environments where the standard output functions like printf are not available or when trying to minimize dependencies on standard libraries for educational or constrained projects. It demonstrates fundamental programming concepts such as recursion and conditional logic.
