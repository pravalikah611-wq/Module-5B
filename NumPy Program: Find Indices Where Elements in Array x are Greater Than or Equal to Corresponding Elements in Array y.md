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

## 🧾 Program:

import numpy as np

# Input arrays
x = np.array([10, 25, 15, 40, 5])
y = np.array([8, 30, 10, 20, 5])

print("Array x:", x)
print("Array y:", y)

# Find indices where x >= y
indices = np.where(x >= y)

print("\nIndices where x >= y:", indices[0])

<img width="1564" height="800" alt="image" src="https://github.com/user-attachments/assets/1f06989b-acd6-4af7-b60c-07749085513c" />


## Output:

<img width="1564" height="800" alt="image" src="https://github.com/user-attachments/assets/975d73ad-6bd0-4e61-aef2-75c2d596e530" />


## Result:

The program successfully identifies and displays the indices where elements of array x are greater than or equal to the corresponding elements of array y using np.where().
