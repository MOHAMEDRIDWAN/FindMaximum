# Find the maximum of a list of numbers
## Aim:
To write a program to find the maximum of a list of numbers.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1.	Get the list of marks as input
2.	Use the sort() function or max() function or use the for loop to find the maximum mark.
3.	Return the maximum value
## Program:

i)	# To find the maximum of marks using the list method sort.
```Python
Program to mark the maximum of marks using the list method sort
#Developed by: MOHAMED RIDWAN A
#Register no: 23003133
def max_marks(marks):
    marks.sort()
    return marks[-1]


```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: MOHAMED RIDWAN A
RegisterNumber: 23003133
'''
def max_marks(marks):
    return max(marks)


```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: MOHAMED RIDWAN A
RegisterNumber: 23003133
'''
def max_marks(list1):
    list1.sort()
    max1=list1[-1]
    for i in list1:
        if i>=max1:
            return i


```
## Sample Input and Output
![output](./img/max_marks1.jpg)

## Output:
![image](https://github.com/MOHAMEDRIDWAN/FindMaximum/assets/146993368/1efd6abd-53cb-4df7-8dd9-14cc13f97a85) 
![image](https://github.com/MOHAMEDRIDWAN/FindMaximum/assets/146993368/922ff145-da09-4506-ba16-a37cb583599b) 
![image](https://github.com/MOHAMEDRIDWAN/FindMaximum/assets/146993368/df5eff38-a2ce-4481-bdcb-87e82177675e)




## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
