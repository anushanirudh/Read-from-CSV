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
# Developed by: R Anirudh
# Register Number: 23003227
import pandas as pd

df = pd.read_csv('pandascsv.csv')

print(df.head(10))

print(df.tail())

print("Number of rows:",len(df.axes[0]))

print("Number of columns:",len(df.axes[1]))

## OUTPUT:
![screenshot3](https://github.com/anushanirudh/Read-from-CSV/assets/151725737/e5dc4c07-98d7-428c-9f7e-5a89fbdf7512)

## RESULT:
