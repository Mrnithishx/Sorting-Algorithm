# Selection sort and Insertion sort
## Aim:
To write a program to perform selection sort and insertion sort using python programming.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## Selection Sort Algorithm:
1.	Set the first unsorted element as the minimum
2.	For each of the unsorted elements, check if the element < current minimum.
3.	If yes, set the element as the new minimum.
4.	Swap minimum with first unsorted position.
5.	Repeat the steps 2 and 3 for all the elements in the array.
## Insertion Sort Algorithm:
1.	Set the first element as sorted element j.
2.	For each unsorted element X, check if current sorted element j >X.
3.	If yes, move sorted element to the right by 1.
4.	Break the loop and insert X.
5.	Repeat the steps 2 to 4 for sorting all the elements in the array.
## Program:
i)	#Selection Sort
```python
''' 
Program to sort the elements in the list using the Selection Sort algorithm.
Developed by:NITHISH MD
RegisterNumber: 23009587
'''
def selection_sort(array,size):
    for ind in range(size):
        min_index= ind
        for j in range(ind+1,size):
            if array[j] < array[min_index]:
                min_index=j
        (array[ind],array[min_index]) = (array[min_index],array[ind])
arr = eval(input())
size=len(arr)
selection_sort(arr,size)
print(arr)

```
ii)	#Insertion Sort
```
''' 
Program to sort the elements in the list using the Insertion Sort algorithm.
Developed by:NITHISH MD
RegisterNumber: 23009587
'''

def selection_sort(array,size):
    for ind in range(size):
        min_index= ind
        for j in range(ind+1,size):
            if array [j] < array[min_index]:
                min_index=j
        (array[ind],array[min_index]) = (array[min_index],array[ind])
arr = eval(input())
size=len(arr)
selection_sort(arr,size)
print(arr)
   
```
## Output:
i)	#Selection Sort
![image](https://github.com/Mrnithishx/Sorting-Algorithm/assets/148201573/2f913be4-c5a1-46c7-bcb0-c787b17ff48e)

ii)	#Insertion Sort
![image](https://github.com/Mrnithishx/Sorting-Algorithm/assets/148201573/44687b4a-3b8e-4706-979b-68fa65510eaf)


## Result:
Thus the program is written to perform selection sort and insertion sort using python programming.
