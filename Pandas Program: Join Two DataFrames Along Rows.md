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

## 💻 Program
```
import pandas as pd

# First DataFrame
student_data1 = {
    'name': ['Ankit', 'Riya'],
    'marks': [85, 90]
}

df1 = pd.DataFrame(student_data1)

# Second DataFrame
student_data2 = {
    'name': ['Karan', 'Meena'],
    'marks': [78, 92]
}

df2 = pd.DataFrame(student_data2)

# Concatenate row-wise
df_combined = pd.concat([df1, df2], axis=0)

# Display result
print(df_combined)
```
## Output
<img width="668" height="548" alt="image" src="https://github.com/user-attachments/assets/4a08a3ed-7834-4b4d-a9a9-99c1451daf5f" />

## Result
Thus, the Python program to join two DataFrames along rows using pd.concat() was successfully executed.
