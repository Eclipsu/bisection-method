# Quadratic Equation Solver using Bisection Method

This is a C program that solves quadratic equations using the Bisection Method. It takes the coefficients of a quadratic equation in the form `px^2 + qx + c = 0` as input, and then finds the root of the equation within a user-specified interval using the Bisection Method.

## Usage

To use the program, simply compile the source code and run the executable. You will be prompted to enter the coefficients `p`, `q`, and `c` of the quadratic equation, as well as the interval `[a, b]` within which to search for the root.

The program will then use Bolzano's Theorem to check if a root exists within the interval. If a root is found, the program will apply the Bisection Method to find the root to a certain degree of accuracy.

## How it works

The program works by first checking if there is a root within the specified interval using Bolzano's Theorem. If a root exists, the program uses the Bisection Method to find the root to a certain degree of accuracy.

The Bisection Method works by repeatedly dividing the interval `[a, b]` in half and then checking which half the root lies in. This process is repeated until the desired degree of accuracy is achieved.

## Conclusion

This program is a simple demonstration of how the Bisection Method can be used to solve quadratic equations. It can be useful for students who are learning about numerical methods in their high school or undergraduate studies.
