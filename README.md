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
Developed by:S.Subashini 
RegisterNumber:22009344
'''
def max_marks(marks):
    marks.sort()
    large = marks[-1]
    return large


```

ii)	# To find the maximum marks using the list method max().
```Python
def max_marks(marks):
    large = max(marks)
    return large



```

iii) # To find the maximum marks without using builtin functions.
```Python
def max_marks(marks):
          large = max(marks)
          return large


```
## Sample Input and Output
![output](./img/max_marks1.jpg) 


##OUTPUT:




![Screenshot_20230126_081723](https://user-images.githubusercontent.com/119404951/214748904-f78a4b92-f1d7-4e00-924a-ef4b9c2d3a47.png)




![Screenshot_20230126_082410](https://user-images.githubusercontent.com/119404951/214749036-a0c898b5-748f-4515-9851-1263d4bc5392.png)



![Screenshot_20230126_081441](https://user-images.githubusercontent.com/119404951/214749074-0a614209-e342-4cb5-9d55-4023d37ac9a2.png)

## Result

Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
