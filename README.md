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
Developed by: murali s
RegisterNumber: 212222230088
def max_marks(marks):
    #Write your code here
    marks.sort()
    large = max(marks)
    return large
```

ii)	# To find the maximum marks using the list method max().
```Python
Program to find the maximum marks using the list method max().
Developed by: murali s 
RegisterNumber: 212222230088
def max_marks(marks):
    # write your code here
    large = max(marks)
    return large
```

iii) # To find the maximum marks without using builtin functions.
```Python
Program to the maximum marks without using builtin functions.
Developed by: murali s
RegisterNumber: 212222230088
def max_marks(list1):
    # write your code here
    max = list1[0]
    for i in list1:
        if i > max:
            max = i
    return max        
```
## Sample Input and Output
Write a program to mark the maximum of marks using the list method sort.

For example:

Test	Result
print(max_marks([88, 67, 77, 93, 95, 11, 67, 89, 56, 89]))
95
print(max_marks([80, 60, 70, 90, 98, 65, 50, 89, 75, 85]))
98


## Output:
![image](https://github.com/MURALI22008445/FindMaximum/assets/119643767/47e5b76a-7edc-4067-bee2-1e251d183eb6)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
