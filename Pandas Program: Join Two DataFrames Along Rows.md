# 🧪 Pandas Program: Join Two DataFrames Along Rows

## 🎯 AIM

To write a Python program using Pandas to **join two DataFrames along rows** (row-wise concatenation) and assign all data to a new DataFrame.

---

## 🧠 ALGORITHM

1. **Import Libraries**: Import the `pandas` library.
2. **Create First DataFrame**: Use a dictionary to create `student_data1`.
3. **Create Second DataFrame**: Use another dictionary to create `student_data2`.
4. **Concatenate DataFrames**: Use `pd.concat()` with `axis=0` to concatenate both DataFrames row-wise.
5. **Display Result**: Print the new combined DataFrame.

---

## 💻 Program:

import pandas as pd

# First DataFrame
df1 = pd.DataFrame({
    "Name": ["Arun", "Meena"],
    "Age": [21, 22]
})

# Second DataFrame
df2 = pd.DataFrame({
    "Name": ["Ravi", "Divya"],
    "Age": [20, 23]
})

print("DataFrame 1:")
print(df1)

print("\nDataFrame 2:")
print(df2)

# Concatenate row-wise
result_df = pd.concat([df1, df2], axis=0, ignore_index=True)

print("\nAfter Row-wise Concatenation:")
print(result_df)

<img width="1716" height="762" alt="image" src="https://github.com/user-attachments/assets/643625dc-77e6-4934-bdcc-dea694f20f31" />





## Output:
<img width="1716" height="762" alt="image" src="https://github.com/user-attachments/assets/9f42c6e4-39f8-4ef5-83cc-a17a503b5456" />


## Result:
The program successfully concatenates two Pandas DataFrames row-wise using pd.concat() and stores the combined data in a new DataFrame.
