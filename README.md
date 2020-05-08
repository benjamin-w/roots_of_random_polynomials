# roots_of_random_polynomials
Monte Carlo Samples of Algebraic Integers with fixed degree and height

Consider the roots of a polynomial

x^n + a_{n-1} x^{n-1} + a_{n-2} x^{n-2} + ... + a_1 x + a_0 = 0

where a_0, ..., a_{n-1} are integers with |a_i| <= H for all i = 0, ..., n-1

Such a polynomial is said to be of degree "n" and height "H".

Its roots are called algebraic integers.

This Julia notebook randomly samples such algebraic integers and plots some histograms.
