# NumPy

A quick revision of NumPy basics.

## Topics Covered

- Creating and reshaping arrays
- Array slicing and indexing
- Mathematical operations (element-wise and broadcasting)
- Aggregations (mean, sum, standard deviation)
- Linear algebra operations (`dot`, transpose)
- Random number generation

## Example Usage

```python
import numpy as np

# Create a 2D array
arr = np.array([[1, 2, 3], [4, 5, 6]])

# Perform basic operations
print("Original Array:")
print(arr)

# Transpose
print("\nTransposed Array:")
print(arr.T)

# Element-wise multiplication
print("\nElement-wise Multiplication:")
print(arr * 2)

# Mean and sum
print("\nMean:", np.mean(arr))
print("Sum:", np.sum(arr))
```
