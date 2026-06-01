# NumPy Program: Column-wise Sorting of a 2D Array

## 🎯 Aim
To write a **NumPy** program that sorts the elements in each column of a given 2D array in ascending order.

## 🧠 Algorithm

1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Accept a 2D NumPy array from the user.
3. **Sort Column-wise**: Use the `np.sort()` function with `axis=0` to sort each column in ascending order.
4. **Store Result**: Store the sorted result in a new array.
5. **Display Output**: Print the original array and the column-wise sorted array.

## 🧾 Program:

import numpy as np

# Input 2D array
arr = np.array([[9, 4, 7],
                [2, 8, 1],
                [6, 3, 5]])

print("Original Array:")
print(arr)

# Sort each column in ascending order
sorted_arr = np.sort(arr, axis=0)

print("\nArray after sorting each column in ascending order:")
print(sorted_arr)
<img width="1601" height="664" alt="image" src="https://github.com/user-attachments/assets/b6347c60-6a9b-4943-aec0-2f83657f2e87" />


## Output:
<img width="1601" height="664" alt="image" src="https://github.com/user-attachments/assets/8021b21b-547a-4bf5-87a0-0a7b4032f852" />


## Result:

The NumPy program successfully sorts each column of the given 2D array in ascending order using np.sort() with axis=0.
