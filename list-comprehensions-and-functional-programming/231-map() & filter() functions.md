## Learning Objectives

* map() function
* filter() function

## map() function

Lists, tuples, sets, dictionaries, etc., are iterables. Watch this video till 2:44 only.










<iframe width="560" height="315" src="https://www.youtube.com/embed/34OOY_AxEs4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>











* The **map()** is a built-in function in Python that takes two arguments:
  1. a function
  2. an iterable (A sequence or collection of elements like list, tuple, etc.)
* map() function applies a given function for each item in an iterable
* Returns a list of the results.

### Syntax

`map(function, iterable)`

### What is typecast?

* The process of converting any object's type (i.e., the datatype) is called typecasting.
* For example, converting a list 'a' to a tuple.  
  a = [2, 4, 6]
  b = tuple(a) ===> This is typecasting











![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_aa710e7e82174040bd47ee3051b9a409.png)








![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_a1d90ffec01244e39a47c073f1124417.png)




* We can provide more than one iterable in the **map()** function.

* Let's say we want to add elements of two lists index-wise. For example,  
  list1 = \[2, 4, 6, 8, 10]  
  list2 = \[1, 3, 5, 7, 9]

* And, we want to get \[3, 7, 11, 15, 19] - This is nothing but the element-wise sum of the elements from the two lists.*





![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_80c0cc0caf154a66894b90aa80b03a5d.png)



### Try It Yourself

Consider you have a list, l1 = \[5, 7, 8, 10, 11, 13, 15, 16, 17, 19, 20]. Write a Python program and use the map() function to get the even numbers from the list. Think ????. Do it by yourself before continuing.








![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_380a9f0262784e2e93cf43885c436364.png)










* Can you observe the disadvantage of map here? While using the map() function, if you have an input of 10 elements in the iterable, the output will also consist of 10 elements. So we cannot filter out the elements in map().
* Here filter() function comes into picture.


## filter() function

* The filter() is an in-built function in Python that works similar to the map() function
* It takes two parameters; the first is a function, and the second is an iterable
* The function tests each element in the iterable to be true or not
* If the function returns true for a particular element, the filter() function selects that element. Else it skips that element.

### Syntax

`filter(function, iterable)`

Let's understand this through an example. Consider the same list, l1 = \[5, 7, 8, 10, 11, 13, 15, 16, 17, 19, 20].
**We want to get only the even numbers from l1.**




![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_3c352f4ee5e6466498a09bee63324530.png)