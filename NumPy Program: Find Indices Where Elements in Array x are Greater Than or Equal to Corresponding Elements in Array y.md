# # NumPy Program: Find Indices Where Elements in Array x are Greater Than or Equal to Corresponding Elements in Array y

## 🎯 Aim
To write a Python program using **NumPy** that finds the indices where elements in array `x` are greater than or equal to their corresponding elements in array `y`.

## 🧠 Algorithm
1. **Import NumPy**: Import the NumPy library.
2. **Define Arrays**: Define two NumPy arrays, `x` and `y`, with the same shape (i.e., same number of elements).
3. **Use Boolean Indexing**: 
   - `x > y` gives a boolean array where elements of `x` are greater than `y`.
   - `x == y` gives a boolean array where elements of `x` are equal to `y`.
4. **Find Indices**: Use `np.where()` to get the indices where the conditions `x >= y` are satisfied.
5. **Print Indices**: Print the indices where the condition holds true.

## 🧾 Program
```
import numpy as np

# Define arrays
x = np.array([1, 4, 3, 8, 5])
y = np.array([2, 3, 3, 6, 7])

# Find indices
indices = np.where(x >= y)

# Display result
print("Array x:", x)
print("Array y:", y)
print("Indices where x >= y:", indices)
```
## Output
<img width="645" height="342" alt="image" src="https://github.com/user-attachments/assets/161f93f7-4e9e-46d0-88a9-18429dd19bfd" />

## Result
Thus, the Python program using NumPy to find indices where elements of array x are greater than or equal to array y was successfully executed.
