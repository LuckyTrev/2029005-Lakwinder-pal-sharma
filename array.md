## 1. Write a Python program to create an array of 5 elements and display the array items Access each individual items through indexes
```python
import arrray as arr
a= arr.array('d',[10,20,30,40])
print(a[0])
print(a[1])
print(a[2])
print(a[3])
```

[Output](https://user-images.githubusercontent.com/79211248/120897317-14435e80-c643-11eb-9932-349f3e023da6.png)


## 2. Write a Python Program to reverse the order of items in the array.
```python
import array as arr
arr = arr.array
arr=[1,2,3,4,5]
result = list(reversed(arr))
print "Reversed array using reversed() method:",result
res=arr[::-1]
print "Reversed arrary using list slicing is:",res
arr.reverse()
print "Reversed array using reverse() method",arr
```

[Output](https://user-images.githubusercontent.com/79211248/120897347-49e84780-c643-11eb-82f1-0b68982741dd.png)
