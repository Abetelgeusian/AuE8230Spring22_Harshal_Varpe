Content of this package:
In the script folder you will find three python files. In the videos folder, you will find the viedos of how each code works.

Explanation:
1) circle.py-
This is a simple script that takes input from the user for radius and angular velocity of the turtle in turtlesim.

2) square_openL.py-
In this code there are three functions. "sq_openl" function calls the other two function to move the turtle in sqaure. The function "move" takes values for side of polygon, linear velocity, Twist and publisher. The function "turn" takes angular velocity, twist and publisher.

3) square_cl.py-
In this code we use gotogoal.py code from ros.org. We rely on proportional controller to adjust angular and linear velocity of turtle in the turtlesim. The main difference between this and openloop is that we subscribe to pose of the turtle in this script. we use the pose of the turtle to determine the current position of turtle and where it needs to go.
