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
```

Program to sort the elements in the list using the Selection Sort algorithm.
Developed by: NIRAUNJANA GAYATHRI G R
RegisterNumber: 22008369

def selection_sort(nums):
    for i in range(len(nums)):
        lowest_value_index = i
        for j in range(i+1, len(nums)):
            if nums[j] < nums[lowest_value_index]:
                lowest_value_index = j
        nums[i], nums[lowest_value_index] = nums[lowest_value_index], nums[i]



    
    
    
    
list_of_nums = eval(input())
selection_sort(list_of_nums)
print(list_of_nums)




```
ii)	#Insertion Sort
```
Program to sort the elements in the list using the Insertion Sort algorithm.
Developed by: NIRAUNJANA GAYATHRI G R
RegisterNumber: 22008369

def insertion_sort(nums):
    for i in range(1, len(nums)):
        item_to_insert = nums[i]
        j = i -1
        while j >=0 and nums[j] > item_to_insert:
            nums[j+1] = nums[j]
            j -= 1
        nums[j+1] = item_to_insert   
            
    
    
list_of_nums = eval(input())
insertion_sort(list_of_nums)
print(list_of_nums)





```

## Output:
![WhatsApp Image 2023-01-25 at 21 10 43](https://user-images.githubusercontent.com/119395610/214608870-33ff98d2-ec6f-4b64-8948-42f5b75fa738.jpg)
![WhatsApp Image 2023-01-25 at 21 11 52](https://user-images.githubusercontent.com/119395610/214608976-7648a42f-7266-4414-a0f7-d9064e2286f4.jpg)
![WhatsApp Image 2023-01-25 at 21 13 27](https://user-images.githubusercontent.com/119395610/214609052-c4dd4ffe-707b-4cdf-9aa9-43fff35f4172.jpg)
![WhatsApp Image 2023-01-25 at 21 16 09](https://user-images.githubusercontent.com/119395610/214609127-396f0dd0-4dad-4008-a0f2-3583c2c69009.jpg)



## Result:
Thus the program is written to perform selection sort and insertion sort using python programming.
