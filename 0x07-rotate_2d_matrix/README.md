# Rotate 2D Matrix

Rotating a 2D matrix is a common algorithmic problem where a square matrix (rows and columns are of the same length) is given and are required to rotate its elements by 90 degrees in a clockwise or counterclockwise direction.

**How to approach rotating a 2D matrix:**

*Clockwise Rotation:*
Transpose the matrix: Swap elements at matrix[i][j] with matrix[j][i] for all i and j, where i is less than j.
Reverse each row: For each row, reverse the order of elements.

*Counterclockwise Rotation:*
Transpose the matrix: Swap elements at matrix[i][j] with matrix[j][i] for all i and j, where i is less than j.
Reverse each column: For each column, reverse the order of elements.

**Example of a clockwise rotation:**

Original Matrix:

```bash
1  2  3
4  5  6
7  8  9
```

After Transpose:

```bash
1  4  7
2  5  8
3  6  9
```

After Reversing Each Row:

```bash
7  4  1
8  5  2
9  6  3
```

The rotated matrix after a clockwise rotation would be:

```bash
7  4  1
8  5  2
9  6  3
```

This operation is frequently encountered in coding interviews and algorithm challenges, to test one's ability to manipulate and reorganize data efficiently. Implementing the rotation algorithm involves nested loops and swapping elements in a systematic way.
