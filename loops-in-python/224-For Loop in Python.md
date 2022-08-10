## Learning Objectives

* For loop
* Looping through a List
* Looping through a String
* Enumerate

### Tutorial on for loop










<iframe width="560" height="315" src="https://www.youtube.com/embed/OnDr4J2UXSA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>












* "For loop" is used for iterating over a sequence (that can be any data structure - list/tuples or even a string)
* Iteration means performing an action repeatedly
* Syntax:  
```
for variable in sequence:
   expression
```



* Which means "for each variable in sequence, execute the expression"
* Python uses indentation as its method of grouping statements. So all the statements having the same indentation will be considered inside the for loop.


## Looping through a List

* Example:  
Let's say we wish to store the heights of our family members in a list and print them one by one.  
![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_78d2a027c8a645458c8e3d8707a9a1ff.png)





* Internal Working:
  * First, we store all the heights in a list named fam_heights
  * Now, we'll go to each element and print it
  * This action will continue until all the list elements are printed in order.



## Looping through a String

* Even strings are iterable objects; they contain a sequence of characters:





![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_726789df6f2048b1bd9a1034f3729343.png)





* As you can see, each string character is printed in a separate line.
* We can even apply string methods in the for loop.





![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_a44db7e745d84708bd4a6d02cd08c3e7.png)







## Enumerate

* With the for loop, you could print the heights of your family members.
* But what if you also want to access the index of each element of the list? Here is where the enumerate function comes into play.
* The enumerate function iterates over the elements of a list and associates an index with them. You need to use two variables (index and height in this case) to store the values given by enumerate.






![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_5ec3032622da4df7964241e586047bf7.png)