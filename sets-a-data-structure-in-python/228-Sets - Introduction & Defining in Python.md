## Learning Objectives

* Sets in Python

* Defining a set in Python

* Accessing items of a Set in Python

### Exercise

* We have a list, say list1 = \[10, 20, 51, 60, 20, 10, 23, 25, 23, 51, 25]. We want to remove the duplicates. **Can we remove the duplicates and have unique elements only?**
* Can you write Python code to get the unique elements from the list1? **Try it by yourself before continuing.**

### Approach To Solve The Previous Problem

  1. Define an empty list, say list2, to store all the unique elements
  2. Iterate over list1 (use for loop)
  3. Check if an item is present in list2 or not:
     1. If the item is present, then continue
     2. If it is not present, then append the item to list2
  4. print list2

### 'in' Keyword in Python

Before jumping to the code for the approach mentioned earlier, let's see the **' in '** keyword.

**'in'** is a keyword in Python that has two purposes:

1. The **' in '** keyword is used to check if a value is present in a collection of items or a sequence (list, string, dict, set, etc.) or not.
2. The **'in'** keyword is also used to iterate through a sequence of items in a for loop.

### Python Code To Solve The Previous Problem
```
# Python program to remove the duplicates from list1
list1 = [10,20,51,60,20,10,23,25,23,51,25] # given list1

list2 = [] # define an empty list

for item in list1:
  # Check if item is present in list2 or not
  if item in list2:
    continue

  else:   # if the item is not present in list2
    list2.append(item)  # append the item to list2

print(list2)
```
The above list (i.e., list2) contains no duplicate elements.

## Sets in Python

Python provides one more data structure mainly related to keeping the uniqueness of values, called Sets.

**Sets:** A set is a collection of unique elements, i.e., a set cannot have any duplicate elements.












<iframe width="560" height="315" src="https://www.youtube.com/embed/482kbk1x04w" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>












## Defining a Set in Python

A set in Python is defined using curly brackets, i.e., { }







![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_e71557add0334ec787402f705c359e2a.png)




From the above examples, you can notice that the elements in a set are not in order. Hence, a set is an **unordered collection of elements.**

## Accessing Items of a Set in Python

We cannot access an item in a set using the index of the elements.





![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_509b41dfa0a44b979583a4185fec6d2f.png)




**How to get a single element at a time from a set?**

We can take the help of the 'for' loop to get a single element at a time from a set.

![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_47a598f8afef402ca03eccb39ccdb65c.png)


One can also ask if a particular element is present in the set or not using the **'in'** keyword.



![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_011e413abdb64c93bd198659ddfd5a31.png)