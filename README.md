# Subject

Write a program that solves a polynomial second or lower degree equation. You will have
to show at least:
- The equation in its reduced form.
- The degree of the equation.
- It’s solution(s) and the polarity of the discriminant if it makes sens.
Ex examples:

We will always expect the entry to have the right format, ie. every term respect the
form a ∗ x
p
. Exponents are organized and present. Beware, it doesn’t mean the equation
has a solution! If so, your program should detect it and specify it. You should also think
of zero, negative or non whole coefficients...
There might be exceptions you will have to manage. In the equation 42∗X0 = 42∗X0
,
for instance, each real number is a solution...

# Computorv1
Polynomial equation solver, coded in Python.

![image](https://github.com/revolveR99/Computor-v1/blob/main/153571769-3f15bf46-30c1-44f3-8824-3b32385a99d2.png)

### The project:

- Solves polynomial equations given as program's argument
- Balances the equation and displays the reduced form
- Displays the degree of the equation
- Computes and display the discriminant's sign when it applies
- Computes and displays the equation's solutions

### Try it:
- The Makefile present in this repository provides multiple tests
- These tests can be launched with **make testN** ('N' replaced with the number of the test)
- Example: "make test4"
- Alternatively the program accepts one string as an argument and it must be formatted in the following way:
  - "N1 * X^0 + N2 * X^1 ... Nn * X^t = M1 * X^0 + M2 * X^1 ... Mn * X^t"
  - N1 ... Nn and M1 ... Mn are the coefficients of every X
  - t is the maximum exponent of x (also the degree of the polynome)
- The program solves the equations of degrees up to 2
- The equation must be well formatted

### Useful links that helped me with this project:
- [**Regex in Python explained with examples**](https://www.w3schools.com/python/python_regex.asp)
- [**Discriminant and 2nd degree equations solving**](https://www.geeksforgeeks.org/solving-2nd-degree-quadratic-equations/)
  
