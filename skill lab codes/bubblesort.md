```
def bubblesort (lists):
    list 1=lists
	for i in range(0,len(list1)):
	    for j in range (0,len(list1)-1):
		   if (list1[j]>list1[j+1]):
		        temp=list1[j]
				list1[j]=list1[j+1]
				list1[j+1]=temp
	return list1
list1=[99,88,77,66,55,44,33,22,11]
print("This is before sorted list")
print(list1)
sorted_list=bubblesort(list1)
print("The list is sorted")
print(sorted_list)
```