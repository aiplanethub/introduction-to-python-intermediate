## Learning Objectives

* Lambda function

* Map and Lambda

* Filter and Lambda

### Earlier Function

* Earlier we used the ‘def’ keyword to define a function
* And in the body of the function, we added the logic of the function










<iframe width="560" height="315" src="https://www.youtube.com/embed/HBR6wqXj2iY?start=10" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>












* A lambda function is an anonymous function. Now, what is an anonymous function? An anonymous function is a function that is defined without any name.
* For example, we defined a function in the earlier topic which can be called whenever required with a name 'even()', the map function can be called using the name 'map()' while lambda functions cannot be called whenever required. We define the lambda function whenever required.
* The lambda function can take any number of arguments but can have only one expression. Let's understand through examples.

### Syntax

`lambda arguments: expression`

For example, we had defined a function to calculate square of the number and used map function to get the list of square of numbers in a list.







![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_d46d89495962489fbf719eb34d553c1e.png)














![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_cf6958333b1043b0b75a7c8819e0ad9e.png)








As mentioned earlier that lambda function can take any number of argument, let's calculate the element wise sum of two lists.




![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_9cf3e5f6204644989654968347c49b18.png)




### Try It Yourself

Can you filter out the even numbers from the list, l1 = \[5, 7, 8, 10, 11, 13, 15, 16, 17, 19, 20] using lambda function? Think ???? and write a Python program to filter out the even numbers before continuing.




![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_7c1f63378d754b90a7765a51b89ec754.png)





The above code can also be written as:




![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_c742fcb409584801bdc0b0f96a7fa441.png)