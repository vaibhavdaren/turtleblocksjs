Documentation of Stage:-
The challenges contain  4 levels - Beginner, Medium, Advanced and Bonus. Each level consists of 12 stages.
Each of the stage is based on a simillar design pattern structure comprising of the following blocks as described below along with the final stage representation.

![Level](https://github.com/vaibhavdaren/turtleblocksjs/blob/tutorials/tutcompsite/documentation/doc1.PNG)

1. The challenges display the to do task on the top right corner.
2. The challenges open the relavant palette to be used on the left hand side of the canvas
3. The challenges display the challenge image to be traced



![Level](https://github.com/vaibhavdaren/turtleblocksjs/blob/tutorials/tutcompsite/documentation/doc2.PNG)
On the backend, we have the following blocks present in every challenge.

1. start-yertle
2. start
3. check
4. stage complete
5. stage laod
6. microop
7. chi 
8. process
9. shado

These blocks comprise of the logic behind the game level. From drawing the challenge to loading, to verifying the challenge and to printing the 'Checkpoint Reached' message along with sound.

![Level](https://github.com/vaibhavdaren/turtleblocksjs/blob/tutorials/tutcompsite/documentation/doc3.PNG)

1. The 'Stage Load' block sets the turtle to the centre of the shape to be traced. It draws the to be traced shape with the help of 'chi' action.  
2.'chi' sets the turtle to relavant position and calls the 'shado' action block which draws the required shape in purple color.
3. Stage load finally sets the pen color to yellow color which is the color on which the check logic of the challenge works.

![Level](https://github.com/vaibhavdaren/turtleblocksjs/blob/tutorials/tutcompsite/documentation/doc4.PNG)

1. The other start block run concurrently and load the images which contain the relavant artwork of the challenge and other sprites.
2. It also contains the checking logic of the challenge which is the crux of the project and verifies the shape drawn by the user.
3. 'Microop' and 'process' checks the shape drawn by the user in pixel by pixel format.
4. If the image traced is same as the challenge image, global value of flag is set to 1 and 'Checkpoint Reached' message is printed along with background sound.

![Level](https://github.com/vaibhavdaren/turtleblocksjs/blob/tutorials/tutcompsite/documentation/doc5.PNG)

 

