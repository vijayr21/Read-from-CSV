# Read-from-CSV

## AIM:
To write a python program for reading content from a CSV file

PROGRAM:


## ALGORITHM:
### Step 1:Import pandas as pd
### Step 2:Read the CSV file using read_csv method.
### Step 3:Use head and tail method to get the required contents from the file
### Step 4:Use len() method to get the number of rows and columns.
### Step 5:Print the output

## PROGRAM:
```
# Developed by:VIJAY R
# Register Number: 23013759
import pandas as pd
df = pd.read_csv('pandascsv.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```


## OUTPUT:

![Screenshot 2023-12-25 224228](https://github.com/vijayr21/Read-from-CSV/assets/149347607/36495904-1358-413f-9a7d-c07cbc2b607f)

## RESULT:
thus the output got successfully.
