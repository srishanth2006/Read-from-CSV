# Read-from-CSV

## AIM:

## ALGORITHM:
### Step 1:
Import pandas as pd.
### Step 2:
Read the CSV file using read_csv method.
### Step 3:
Use head and tail method to get the required contents from the file.
### Step 4:
Use len() method to get the number of rows and columns.
### Step 5:
Print the output

## PROGRAM:
```
# Developed by: SRISHANTH J
# Register Number: 212223240160
import pandas as pd
df = pd.read_csv('pandascsv.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```
## OUTPUT:
<img width="317" alt="Screenshot 2023-12-26 181922" src="https://github.com/srishanth2006/Read-from-CSV/assets/150319470/38380c6c-bba1-4f93-b955-1b1c3d627fde">

## RESULT:
