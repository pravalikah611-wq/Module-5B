# NumPy Program: Replace the Second Column in a 2D Array

## 🎯 Aim
To write a **NumPy** program that deletes the second column from a given 2D array and inserts a new column at the same position.

## 🧠 Algorithm
1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Get a 2D NumPy array and a new column (as another array) from the user.
3. **Delete Column**: Use `np.delete()` to remove the second column (index 1) from the original array.
4. **Insert Column**: Use `np.insert()` to insert the new column at the second column's original position.
5. **Display Result**: Print the updated array with the replaced column.

## 🧾 Program:
import numpy as np

# Given 2D array
arr = np.array([[1, 2, 3],
                [4, 5, 6],
                [7, 8, 9]])

print("Original Array:")
print(arr)

# Delete second column (index 1)
arr_deleted = np.delete(arr, 1, axis=1)

print("\nAfter deleting second column:")
print(arr_deleted)

# New column to insert
new_col = np.array([[10],
                    [20],
                    [30]])

# Insert new column at position 1
arr_inserted = np.insert(arr_deleted, 1, new_col, axis=1)

print("\nAfter inserting new column:")
print(arr_inserted)

<img width="1658" height="791" alt="image" src="https://github.com/user-attachments/assets/c5fae0b1-d434-4cfe-bf7e-ac07d9ecee36" />



## Output:

<img width="1658" height="791" alt="image" src="https://github.com/user-attachments/assets/e3dbc331-6cda-4b07-9f2f-0c5cf8022787" />


## Result:

The program successfully deletes the second column of the given 2D array and inserts a new column at the same position using NumPy functions np.delete() and np.insert().
