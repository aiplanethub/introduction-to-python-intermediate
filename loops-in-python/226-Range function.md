* range() allows the user to generate a series of numbers within a given range.
* The user can decide where that series of numbers will begin and end and how big the difference will be between one number and the next.
* range() takes mainly three arguments:
  * A start argument is a starting number of the sequence. i.e., lower limit. By default, it starts with 0 if not specified.
  * A stop argument is an upper limit. i.e., generate numbers up to this number. The range() doesn't include this number in the result.
  * The step is a difference between each number in the result. The default value of the step is one if not specified.
* range() only works with the integers. You can not use float number or any other type in a start, stop and step argument of a range().

You can call the range function in three ways:
* range(stop) takes one argument.
* range(start, stop) takes two arguments.
* range(start, stop, step) takes three arguments.

**Example 1: Using only one argument**






![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_010d8999dd964eeb86cb7876a748cb5f.png)





* Output:  
0, 1, 2, 3, 4,
* By default, print statement prints in different lines. You can use the end argument if you want to print the output in the same line. ',' specifies that a comma will separate each output.
* Only a stop argument is passed to range(). So by default, it takes start = 0 and step = 1.

**Example 2: Using two arguments (i.e., start and stop)**



![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_6f075918c999401aa590c484bb627e26.png)

* Output:  
5, 6, 7, 8, 9,
* By default, it took the step value as 1.

**Example 3: Using all three arguments**


![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_a5ebd1229c7b4b04aa0967173f015f3c.png)



* Output:  
Printing All even numbers between 2 and 10 using range()  
2, 4, 6, 8,
* All three arguments are specified i.e., start = 2, stop = 10, step = 2. The step value is two, so the difference between each number is 2.

The tutor in the video below has used a different Python editor. But don't worry, the same code will work in Jupyter or Colab Notebooks.



<iframe width="560" height="315" src="https://www.youtube.com/embed/HWcs5qdvvo0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>