# Read-from-CSV

## AIM:
  To write a python program for reading the csv file content.
## EQUIPMENTS REQUIRED:
PC Anaconda - Python 3.7
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
#Program for reading a content from csv file 
#Developed By : Jayakrishnan L B L
#Referance No. : 22003251
import pandas as pd
df=pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print('Number of rows:',len(df.axes[0]))
print('Number of Columns:',len(df.axes[1]))
```
## OUTPUT:
![image](https://user-images.githubusercontent.com/120232371/215279152-fe7e18de-eb78-469b-90be-8e46de008d73.png)

## RESULT:
Thus a python program is written to read the contents of a CSV file.
