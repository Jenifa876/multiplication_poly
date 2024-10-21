# Polynomial Multiplication in C++

This project implements polynomial multiplication using a linked list representation of polynomials in C++. The code allows users to input two polynomials, multiplies them, and simplifies the result.

## Features

- Input two polynomials of any degree.
- Multiply the polynomials.
- Simplify the result by combining like terms.
- Display the resulting polynomial.

## Data Structure

The polynomial is represented using a singly linked list where each node contains:
- `coeff`: Coefficient of the term.
- `expo`: Exponent of the term.
- `next`: Pointer to the next node in the list.

## Functions

- **`Node` class**: Represents a term in the polynomial.
- **`mulpoly(Node* poly1, Node* poly2)`**: Multiplies two polynomials and returns the resulting polynomial.
- **`simply(Node* result)`**: Simplifies the resulting polynomial by combining like terms.
- **`print(Node* poly)`**: Prints the polynomial in a human-readable format.
