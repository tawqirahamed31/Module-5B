# NumPy Program: Column-wise Sorting of a 2D Array

## 🎯 Aim
To write a **NumPy** program that sorts the elements in each column of a given 2D array in ascending order.

## 🧠 Algorithm

1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Accept a 2D NumPy array from the user.
3. **Sort Column-wise**: Use the `np.sort()` function with `axis=0` to sort each column in ascending order.
4. **Store Result**: Store the sorted result in a new array.
5. **Display Output**: Print the original array and the column-wise sorted array.

## 🧾 Program
```

import numpy as np

arr = np.array([[3, 2, 1],
                [6, 5, 4],
                [9, 8, 7]])

sorted_arr = np.sort(arr, axis=0)

# Display results
print("Original Array:\n", arr)
print("Column-wise Sorted Array:\n", sorted_arr)
```
## Output
<img width="645" height="416" alt="image" src="https://github.com/user-attachments/assets/a08de3e7-4918-4d0c-bebc-7333b6ae7886" />

## Result
Thus, the Python program using NumPy to sort a 2D array column-wise was successfully executed.
