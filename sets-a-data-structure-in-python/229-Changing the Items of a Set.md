## Learning Objectives

* Adding items in a Set

* Removing items from a Set

* Getting the length of a Set

* Union and Intersection of two Sets

## Add An Item In A Set

* **add()**: Used to add one item at a time in a set.







![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_0a079570260b4db7823bb21208d2f633.png)





### Add More Than One Item In A Set

* **update(): Used to add more than one item at a time in a set.**


![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_749c464f9fda45af9d056141f1da6943.png)


Note: update() method can also add one item to a set. Try this by yourself!

## Remove an Item from a Set

* **remove()**: Used to remove an item from a set





![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_19139741b2fa4a23ac133c34064f2208.png)

Note: If we try to remove an item not present in the set, the remove() method will raise an error.





![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_b6777f3fffc14e14b670d8e6ecb24a57.png)




* If the item is not present in the set, the discard() method will not raise an error.





![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_3f2223055ebb45d18b9b57486d310bce.png)





## Getting The Length Of A Set

To determine the number of elements present in the set, we can use len() method.





![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_3f38a9d22e4a4ea4b1d11ed91c753b9c.png)




## Joining Two Sets

There are different methods to join two sets in Python.

* **update()** method helps you add the items of one set to another.
* **union()** method returns a new set containing all items appearing in either one set, the other, or both sets.
* **intersection()** method returns a new set containing all the common elements in the two sets.

The update method has already been covered before. Let’s have a look at union and intersection now.

### union()











<iframe width="560" height="315" src="https://www.youtube.com/embed/vVKfO1y5YtM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>















![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_ca6d768cc8b34de7abc7fdf90de13e11.png)






Note: The union operation can also be performed as:  
s3 = s1 | s2




![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_81f42c9a79c640f4aec58e74b4660a0e.png)




**Do It Yourself:** Join these two sets using union:

S1 = {1, 1, 2, 5, 4, 3, 3} and S2 = {2, 2, 3, 1, 5, 6, 7}. Observe the output after joining these sets.

### intersection()







<iframe width="560" height="315" src="https://www.youtube.com/embed/Gb8zMt6gl-c?start=36" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>














![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_cdf35e8131714bdb8639f2ab9a27a5b9.png)





**Note**: The intersection operation can also be performed as:  
s3 = s1 & s2





![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_a8e47dbe1552469b8c0ad5ba7e2f2062.png)








![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_3af511b65c51464988c4a18a5e6d61b8.png)





**Do It Yourself:** Join these two sets using intersection():

S1 = {1, 1, 2, 5, 4, 3, 3} and S2 = {2, 2, 3, 1, 5, 6, 7}. Observe the output after joining these sets.