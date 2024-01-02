# Read-from-CSV

## AIM:
To write a python program for reading the csv file content.
## EQUIPEMENT'S REQUIRED:
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
\*
#Program to read contents from a csv file
#DEVELOPED BY : PRITHIVIRAJAN V
#REGISTER NUMBER : 212223100042
\*
import pandas as pd
df=pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail(5))
print("Number of rows:",len(df.axes[0]))
print("number of columns:",len(df.axes[1]))
```
## OUTPUT:
![image](https://github.com/Prithivirajan2911/Read-from-CSV/assets/147020085/57fe32c9-08f7-4d38-8f2b-3e7061afa7c4)

## RESULT:
Thus the program is written to read the csv file.
