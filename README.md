# Name: Mathesh S
# Reg no: 212223230123

# Exno:1
Data Cleaning Process

# AIM
To read the given data and perform data cleaning and save the cleaned data to a file.

# Explanation
Data cleaning is the process of preparing data for analysis by removing or modifying data that is incorrect ,incompleted , irrelevant , duplicated or improperly formatted. Data cleaning is not simply about erasing data ,but rather finding a way to maximize datasets accuracy without necessarily deleting the information.

# Algorithm
STEP 1: Read the given Data

STEP 2: Get the information about the data

STEP 3: Remove the null values from the data

STEP 4: Save the Clean data to the file

STEP 5: Remove outliers using IQR

STEP 6: Use zscore of to remove outliers

# Coding and Output

## DATA CLEANING PROCESS:

![alt text](image-11.png)

<br>
<br>

![alt text](image-12.png)

<br>
<br>

![alt text](image-13.png)

<br>
<br>

![alt text](image-14.png)

<br>
<br>

![alt text](image-15.png)

<br>
<br>

![alt text](image-16.png)

<br>
<br>

![alt text](image-17.png)

<br>
<br>

![alt text](image-18.png)

<br>
<br>

![alt text](image-19.png)


### OUTLIERS  DETECTION AND REMOVAL:

```
import pandas as pd
import seaborn as sns
age = [1,3,28,27,92,30,39,40,50,26,24,29,94]
af = pd.DataFrame(age)
af

```

<br>
<br>

![alt text](image.png)

<br>
<br>

![alt text](image-1.png)

<br>
<br>

![alt text](image-2.png)

<br>
<br>

## IQR:

![alt text](image-3.png)

<br>
<br>

![alt text](image-4.png)

<br>
<br>

![alt text](image-5.png)

<br>
<br>

![alt text](image-6.png)

<br>
<br>

![alt text](image-7.png)

<br>
<br>

![alt text](image-8.png)

<br>
<br>

![alt text](image-9.png)



![alt text](image-10.png)





# Result
Thus the given data cleaned , outliers detected and removed successfully.

