# NumPy Matrix Operations

## 📌 Overview

This project demonstrates basic matrix operations using Python and NumPy. It was completed as **Task 14** of the AI & ML Internship at **Veda Technology**.

The project focuses on understanding matrix arithmetic and operations commonly used in data science, numerical computing, and machine learning.

## 🎯 Objective

To understand and perform basic matrix operations using NumPy, including addition, subtraction, matrix multiplication, and transpose operations.

## 🛠️ Tools and Technologies

- **Python**
- **NumPy**
- **Google Colab**

## 📊 Project Tasks

The following operations are implemented:

1. Create two matrices using `np.array()`.
2. Perform matrix addition.
3. Perform matrix subtraction.
4. Perform element-wise multiplication.
5. Perform matrix multiplication.
6. Calculate the transpose of both matrices.
7. Display the results of each operation.

## 💻 Implementation

Two NumPy matrices are created for the operations:

```python
import numpy as np

A = np.array([
    [1, 2, 3],
    [4, 5, 6]
])

B = np.array([
    [7, 8, 9],
    [2, 3, 4]
])
```

### Matrix Addition

Adds corresponding elements of both matrices.

```python
A + B
```

### Matrix Subtraction

Subtracts corresponding elements of matrix B from matrix A.

```python
A - B
```

### Element-wise Multiplication

Multiplies corresponding elements of the matrices.

```python
A * B
```

### Matrix Multiplication

Multiplies rows of the first matrix by columns of the second matrix. The dimensions must be compatible.

```python
A @ B.T
```

### Matrix Transpose

Converts rows into columns and columns into rows.

```python
A.T
B.T
```

## ▶️ How to Run

1. Open [Google Colab](https://colab.research.google.com/).
2. Create a new notebook.
3. Copy the Python code into a code cell.
4. Run the cell to display the matrix operations and their results.
5. Save the notebook as `NumPy_Matrix_Operations.ipynb`.

## 📚 Learning Outcomes

- Learned how to create matrices using NumPy.
- Practiced matrix addition and subtraction.
- Understood the difference between element-wise multiplication and matrix multiplication.
- Learned to use the `@` operator for matrix multiplication.
- Practiced matrix transpose using `.T`.
- Improved understanding of mathematical operations used in machine learning.

## 🏁 Conclusion

This task provided practical experience with NumPy matrix operations and strengthened my understanding of matrix arithmetic. These concepts form an important foundation for further learning in data analysis, linear algebra, and machine learning.

## 👨‍💻 Internship Details

- **Organization:** Veda Technology
- **Track:** AI & ML
- **Task:** 14 — NumPy Matrix Operations
- **Platform:** Google Colab
