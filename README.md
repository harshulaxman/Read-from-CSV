# EX-12: Read-from-CSV

## AIM:
To write a python program for reading the csv file content.
## ALGORITHM:
### Step 1:
Load the CSV into a DataFrame.
### Step 2:
Print the number of contents to be displayed using df.head().
### Step 3:
The number of rows returned is defined in Pandas option settings.
### Step 4:
Check your system's maximum column with the pd.options.display.max_column statement.
### Step 5:
Increase the maximum number of rows to display the entire DataFrame.
## PROGRAM:
```
#To write a python program for reading content from a CSV file.
#Developed by: Harsshitha lakshmanan
#Register Number: 212223230075

import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```
## OUTPUT:
![image](https://github.com/user-attachments/assets/d24de9bc-a09d-4fcd-a286-ae283990fe06)
![image](https://github.com/user-attachments/assets/4d5e7b62-ee99-4a56-880e-2231a29ae36d)

## RESULT:
Thus the program is written to read the csv file.
