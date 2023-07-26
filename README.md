# Read-from-CSV

## AIM:
To Write a program to read a csv file.

## ALGORITHM:
## Step 1:
Import pandas module as pd

## Step 2:
Read a csv file

## Step 3:
print the first five rows and last five rows

## Step 4:
print the length of the rows and columns

## Step 5:
End the program
## PROGRAM:
```
#write a program to read a csv file
#Developed by : MALLIGESH M
#Register number : 23002936

from google.colab import drive
drive.mount('/content/drive')

import pandas as pd
df=pd.read_csv('/content/drive/My Drive/python/cars.csv')
print(df.head())
print(df.tail())
print("Rows",len(df.axes[0]))
print("Columns",len(df.axes[1]))

```

## OUTPUT:

![OUTPUT](/PR.png)
![OUTPUT](/csv.png)

## RESULT:
Thus the program is written to read a csv file. 
