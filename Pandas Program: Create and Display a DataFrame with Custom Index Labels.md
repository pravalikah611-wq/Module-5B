# Pandas Program: Create and Display a DataFrame with Custom Index Labels

## 🎯 Aim

To create and display a **DataFrame** using the **Pandas** library in Python from a given dictionary, and apply specific index labels to the rows.

---

## 🧠 Algorithm

1. **Import Libraries**: Import the required libraries – `pandas` and `numpy`.
2. **Create Dictionary**: Define a dictionary `exam_data` with keys: `'name'`, `'score'`, `'attempts'`, and `'qualify'`.
3. **Index Labels**: Create a list of custom index labels called `labels`.
4. **Create DataFrame**: Use `pd.DataFrame()` to create the DataFrame by passing the dictionary and index labels.
5. **Display Output**: Display the DataFrame using `print()` or by simply calling the DataFrame variable.

---

## 💻 Program:

import pandas as pd

# Given dictionary
data = {
    "Name": ["Arun", "Meena", "Ravi", "Divya"],
    "Age": [21, 22, 20, 23],
    "Marks": [85, 90, 78, 92]
}

# Create DataFrame with custom index labels
df = pd.DataFrame(data, index=["S1", "S2", "S3", "S4"])

print("DataFrame with custom index labels:")
print(df)

<img width="1554" height="688" alt="image" src="https://github.com/user-attachments/assets/64e687e8-dc64-4652-a3f9-09da961f97c2" />



## Output:

<img width="1554" height="688" alt="image" src="https://github.com/user-attachments/assets/9dfcc8c3-b24d-4818-8426-96ec9c2bf9a1" />


## Result:

The program successfully creates a Pandas DataFrame from a dictionary and displays it with custom index labels assigned to each row.
