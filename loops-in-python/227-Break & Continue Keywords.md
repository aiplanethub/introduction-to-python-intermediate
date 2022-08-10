## Learning Objectives

* Break Keyword

* Continue Keyword

## Break & Continue Keywords











<iframe width="560" height="315" src="https://www.youtube.com/embed/NUpCL-552tA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>










## Break Keyword

* If you want to stop or come out of the loop, you can use the break keyword. This keyword helps you come out of both for and while loops.
* Let's say you have a list of numbers, numbers = \[1, 3, 2, 5, 4, 6, 8]. Now you are interested in getting the first even number.

### For Loop & break Keyword









![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_b7ce344ef14a4b52b0f4d3c9e6e45301.png)




* You were only interested in the first even number, but the above Python code has returned all the even numbers in the list.

* Let's see how the break keyword can help:



![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_29353805476d4b01b08d1891e13a2c92.png)




* The first even number in the list is 2. Once the condition is satisfied for the first time, we print the number and use the break keyword to come out of the loop.

### While Loop & break Keyword






![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_63bb1548e75e445898eb7a9b9797af89.png)




* As you can observe, the while loop was to be run till the value of i was less than 9, but here the output is only 1, 2, and 3.
* This is because when the value of i was 3, the loop was discontinued, i.e., the break keyword helped to break the while loop.

## Continue Keyword

* The continue keyword helps you skip or end the current iteration of both for and while loops and starts the next iteration. It will be more apparent through the examples below.
* For example, consider the list of numbers, numbers = \[1, 3, 2, 5, 4, 6, 8]. You want to skip the iteration if the current number is an even number, otherwise, print the number.

### For Loop & continue Keyword








![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_32257c8095fc443986d79ef39c5f5c23.png)



### While Loop & continue Keyword






![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_cda94e9473ac4e99a2b17b675c98a3be.png)