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

''' 
Program to mark the maximum of marks using the list method sort
Developed by: Sanjeevi J
RegisterNumber: 212222110040
'''
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
```

ii)	# To find the maximum marks using the list method max().
```Python

''' 
ii) To find the maximum marks using the list method max().
''' 
Program to find the maximum marks using the list method max().
Developed by: Sanjeevi J 
RegisterNumber: 212222110040
'''
def max_marks(marks):
    large=max(marks)
    return large

```

iii) # To find the maximum marks without using builtin functions.
```Python


''' 
iii) To find the maximum marks without using builtin functions.
''' 
Program to the maximum marks without using builtin functions.
Developed by: Sanjeevi J
RegisterNumber: 212222110040
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
## i) To find the maximum marks using the list method max()
![py 3a (1)](https://github.com/sanjeevi00/FindMaximum/assets/121484976/0ce9ee75-d22f-4881-a736-58ee64b339d7)

## ii)	 To find the maximum marks using the list method max().
![py 3a (2)](https://github.com/sanjeevi00/FindMaximum/assets/121484976/e92dcd8d-ece0-4f85-b92c-377b7df12b8b)

## iii)  To find the maximum marks without using builtin functions.
![py 3a (3)](https://github.com/sanjeevi00/FindMaximum/assets/121484976/f23f500b-b48d-459a-9f17-a14d05ccc89a)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
