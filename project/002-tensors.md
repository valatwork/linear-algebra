# Tensors

Tensors are a generalization of vectors and matrices to any nuber of dimensions.

There are four main types of tensors:

1. **Scalar**: A single number, represented as a 0-dimensional tensor. For example, $x$ is a scalar.

2. **Vector**: A 1-dimensional tensor, which can be thought of as an array of numbers. For example, $[x_1, x_2, x_3]$ is a vector with three elements.

3. **Matrix**: A 2-dimensional tensor, which can be thought of as a table of numbers with rows and columns. For example, $\begin{bmatrix} x_1 & x_2 \\ x_3 & x_4 \end{bmatrix}$ is a matrix with two rows and two columns.

   - A 2D tensor can be represented as a list of lists, e.g., `[[1, 2], [3, 4]]`.

4. **Higher-dimensional tensors**: Tensors with three or more dimensions. For example, a 3-dimensional tensor can be thought of as a cube of numbers, and a 4-dimensional tensor can be thought of as a hypercube.
 - A 3D tensor $\begin{bmatrix} x_{111} & x_{112} \\ x_{121} & x_{122} \end{bmatrix}$ is a 3D tensor with two rows and two columns.
 - A 3D tensor can be represented as a list of lists of lists, e.g., `[[[1, 2], [3, 4]], [[5, 6], [7, 8]]]`.


Summarized in a table:

| Type         | Dimensions | Description        |
|--------------|------------|--------------------|
| Scalar       | 0          | magnitude only     |
| Vector       | 1          | array              |
| Matrix       | 2          | flat table         |
| 3-tensor     | 3          | 3D table           |
| n-tensor     | $n$        | higher dimensional |