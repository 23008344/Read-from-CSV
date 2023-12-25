# Read-from-CSV

## AIM:
To write a python program for copying the contents from one file to another file.

## ALGORITHM:
### Step 1:
start the program
### Step 2:
import pandas 
### Step 3:
 star to find the reading content of csv.file
### Step 4:
end the program


## PROGRAM:
```
'''
Developed by: VARNIKA.P
Register No: 23008344
'''
To write a python program for reading content from a CSV file.
import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```
## OUTPUT:

![Screenshot 2023-12-25 194703](https://github.com/23008344/Read-from-CSV/assets/145742655/a67a00ee-2bdb-41db-a51f-1d9af46d48af)

![image](https://github.com/23008344/Read-from-CSV/assets/145742655/3f45e1fd-1698-457c-8e8c-fdbd3a1fd7d2)


## RESULT:
Thus the progam has been completed sucessfully
