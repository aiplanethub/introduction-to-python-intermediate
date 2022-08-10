<iframe width="560" height="315" src="https://www.youtube.com/embed/6TEGxJXLAWQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>











* With the while loop, we can execute a set of statements repeatedly as long as a condition is true.
* Syntax:
```
while condition:
  statement(s)
```
* All the statements indented by the same number of character spaces after a while condition are considered part of a single block of code. Python uses indentation as its method of grouping statements.

* For example:




![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_3d0a609a2d804634a64d58be1043de78.png)








* Let us understand what is happening in the above program.
  * Value of x is assigned as 1
  * The while loop starts with the condition that x must be less than 4
  * The subsequent two statements have the same indentation and will be considered a part of the while loop
  * The value of x is printed. Initially, x=1
  * The value of x is then increased by 1. So now, x=2
  * Control goes back to the condition line; x is less than 4 (2<4). This means that the following statements will be executed again
  * This continues until x is assigned a value of 4. Then, the condition fails as x is not less than 4
  * The next two statements will not be executed, and the while loop will end.

The tutor in the below video has used a different Python editor. But don't worry, the same code will work in Jupyter or Colab Notebooks.






<iframe width="560" height="315" src="https://www.youtube.com/embed/jSs58VZVLw8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>