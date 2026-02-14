Numerical Computing with NumPy
Mathematical Operations on Scalars, Arrays, and Matrices
1. Introduction

This project demonstrates the implementation of various mathematical operations using the NumPy library in Python. The objective is to understand vectorized computations and apply mathematical, trigonometric, statistical, and matrix-based operations on different data structures including scalars, one-dimensional arrays, and multi-dimensional matrices.

NumPy provides efficient numerical computation capabilities and allows element-wise operations without explicit loops.

2. Objectives

The primary objectives of this project are:

To perform scalar and array-based mathematical operations

To apply trigonometric and inverse trigonometric functions

To perform exponential and logarithmic transformations

To apply rounding and modulus operations

To compute statistical measures on matrices

To understand NumPy vectorization and matrix manipulation

3. Tools and Technologies Used

Python 3.x

NumPy

SymPy

Matplotlib

Seaborn

4. Methodology

The project is divided into three sections:

Section 1: Scalar and 1D Array Operations

A scalar value and a one-dimensional NumPy array were defined:

scalar = 3.7
arr = np.array([1, 2, 3, 4, 5, 6])


The following trigonometric functions were applied:

Sine

Cosine

Tangent

These operations were executed element-wise using NumPy’s vectorized functions.

Section 2: 3×2 Matrix Operations

A 3×2 matrix containing both positive and negative floating-point values was created:

matrix = np.array([
    [-1, 2.16],
    [3.4, -4],
    [5.845757, -6.5678]
])


The following operations were performed:

1. Trigonometric Functions

sin

cos

tan

arcsin

arccos

arctan

2. Exponential and Logarithmic Functions

Exponential function (exp)

Natural logarithm (log)

Note: Logarithmic operations on negative numbers produce NaN values.

3. Absolute Value and Square Root

Absolute value

Square root

Note: Square root of negative numbers produces NaN values.

4. Remainder Operation

Remainder when divided by 2

5. Rounding Functions

Round

Floor

Ceil

Section 3: 2×3 Matrix Statistical Analysis

A 2×3 matrix with floating-point values was defined:

vec = np.array([
    [1, 2.1, 4],
    [3.4, 4.7, 8]
])


The following statistical and analytical operations were performed:

1. Maximum and Minimum

Maximum value and index

Minimum value and index

2. Sorting

Row-wise sorting in ascending order

Descending sorting using slicing

3. Aggregate Functions

Sum

Product

Median

Mean

Standard Deviation

5. Results and Observations

NumPy performs efficient vectorized operations across arrays and matrices.

Mathematical domain restrictions (such as logarithm and square root of negative numbers) result in NaN values.

The argmax() and argmin() functions return flattened indices.

Sorting multi-dimensional arrays is performed row-wise by default.

The len() function returns the number of rows in a matrix.

6. Learning Outcomes

Through this project, the following concepts were understood:

Vectorized numerical computation

Matrix manipulation using NumPy

Application of trigonometric and logarithmic functions

Statistical analysis on multi-dimensional arrays

Handling invalid mathematical operations

Interpretation of NumPy warnings

7. Conclusion

This project successfully demonstrates the use of NumPy for performing mathematical and statistical operations on scalars, arrays, and matrices. It highlights the efficiency of vectorized operations and reinforces foundational concepts in numerical computing.

The implementation provides practical understanding of matrix transformations, domain errors, and statistical computation using Python.
