##Restaurant Project Repository



####Compiling/Running Instructions
Because I had previously installed WindowBuilder on my laptop, there is a file called "forms-1.3.0.jar" necessary for compilation.  
In Eclipse, import the project by clicking File --> New --> Java Project.  From there, manually create a project, and then drag-and-drop 
src files into the new project.  Originally, my project could be imported using an _Ant buildfile_.  However, in the past couple of test submissions,
the images have not appeared because of the method of import.

Click on the project folder.  Click src --> restaurant.gui.  Right click RestaurantGui.java.  Select Run As --> Java Application.

 + To add customer or waiters, type in a name in either boxes and click the _Add_ button.  The button must be clicked in order to add a person; the `Enter` key will not suffice.
 + The two scenario buttons will only do the intended when there is at least one waiter existing.

####Issues
  + The cook may place the food on the plating area before he fully arrives.
  + After successfully serving one customer, the waiter just freezes.
  ++ The way I wrote my code, the customers queue based on the size of the waiting customers.
	 Because the waiter is still considered "working," the host will continue to assign him customers and
	 remove those customers from the waiting list.  As a result, multiple customers will still be
	 stacked on each other.
	 

