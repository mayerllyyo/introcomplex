# Complex Vector and Matrix Operations in Python

This repository contains Python code and exercises related to complex vector spaces and matrices. The code demonstrates the manipulation of complex column vectors and square matrices using the NumPy library. Additionally, it includes exercises with concrete cases for further practice.

## Getting Started

To run the provided code and exercises, you will need to have Python installed on your machine. It is recommended to use PyCharm Professional for full support of local notebooks, but PyCharm Community edition is also supported in read-only mode. Alternatively, you can explore DataSpell, a dedicated IDE for data science, or use Datalore, an online environment for Jupyter notebooks in the browser.

## Code Overview

### Complex Column Vectors

The code showcases operations on complex column vectors, including:
- Sum
- Negation
- Multiplication by a scalar
- Transpose
- Adjunct (Conjugate Transpose)
- Conjugate

```python
import numpy as np

# Define two complex column vectors
v1 = np.array([[2+3j], [5-4j], [1+1j]])
v2 = np.array([[1-1j], [3+2j], [4-4j]])

# Perform operations
sum_v = v1 + v2
neg_v1 = -v1
mult_v1 = v1 * (2 + 1j)
transpose_v1 = v1.T
adjunct_v1 = v1.T.conj()
conjugate_v1 = np.conjugate(v1)

# Display results
print("Sum:", sum_v)
print("Negation:", neg_v1)
print("Scalar Multiplication:", mult_v1)
print("Transpose:", transpose_v1)
print("Adjunct:", adjunct_v1)
print("Conjugate:", conjugate_v1)
