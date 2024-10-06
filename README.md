# DATE:
# EXP NO:6 
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
#developed by:MUKESH.B
#register number:212223230128
def max_marks(array):
    array.sort()
    return array[-1]




```

ii)	# To find the maximum marks using the list method max().
```Python
#developed by:MUKESH.B
#register number:212223230128
def max_marks(array):
    return max(array)




```

iii) # To find the maximum marks without using builtin functions.
```Python
#developed by:MUKESH.B
#register number:212223230128
def max_marks(array):
    max1=array[0]
    for i in range(1,len(array)):
        if max1<array[i]:
            max1=array[i]
    return max1




```



## Output:
i)	# To find the maximum of marks using the list method sort.
![Screenshot 2024-10-06 235440](https://github.com/user-attachments/assets/49e4cd3d-b09e-4cab-baaf-469e68d339a4)
ii)	# To find the maximum marks using the list method max().
![Screenshot 2024-10-06 235446](https://github.com/user-attachments/assets/9481ce8f-4849-4f85-bea4-e2b19391849b)
iii) # To find the maximum marks without using builtin functions.
![Screenshot 2024-10-06 235452](https://github.com/user-attachments/assets/7302db65-6312-4779-b943-7fb78c0876b2)




## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
