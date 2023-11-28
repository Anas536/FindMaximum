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

## i) To find the maximum of marks using the list method sort.
```Python
'''
Program to mark the maximum of marks using the list method sort
Developed by: Mohamed Anas O.I
RegisterNumber: 23008005
'''
def max_marks(marks):
    a=sorted(marks)
    b=a[-1]
    return b


```

## ii)	To find the maximum marks using the list method max().
```Python

'''
Program to find the maximum marks using the list method max().
Developed by: Mohamed Anas O.I
RegisterNumber: 23008005
'''
def max_marks(marks):
    a=max(marks)
    return a
```

## iii)  To find the maximum marks without using builtin functions.
```Python

'''
Program to the maximum marks without using builtin functions.
Developed by: Mohamed Anas O.I
RegisterNumber: 23008005
'''
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max



```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
## i) To find the maximum of marks using the list method sort.
![Screenshot 2023-11-28 082205](https://github.com/Anas536/FindMaximum/assets/139841834/2ab4d3eb-62bf-4d63-95b0-748ab66b1af6)

## ii) To find the maximum marks using the list method max().
![Screenshot 2023-11-28 082453](https://github.com/Anas536/FindMaximum/assets/139841834/4ec7097b-1be6-43de-a2f8-868f615ffd4b)

## iii) To find the maximum marks without using builtin functions.

![Screenshot 2023-11-28 082516](https://github.com/Anas536/FindMaximum/assets/139841834/53fd0007-019e-4451-918b-7f41e2960a2c)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
