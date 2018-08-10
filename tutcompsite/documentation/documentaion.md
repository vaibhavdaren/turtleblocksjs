Documentation of Stage:-

Each final stage looks like one shown below.

![Level](https://github.com/vaibhavdaren/turtleblocksjs/blob/tutorials/tutcompsite/documentation/doc1.PNG)

1. The level displays the task to do on top right corner.
2. Opens the relavant palette to be used
3. Displays the challenge image to be tarced



![Level](https://github.com/vaibhavdaren/turtleblocksjs/blob/tutorials/tutcompsite/documentation/doc2.PNG)
On the backend we have the following blocks present on the stage.
Nameley
1. start-yertle
2. start
3. check
4. stage complete
5. stage laod
6. microop
7. chi 
8. process
9. shado

These  comprise of the logic behind the game level. From drawing the stage to load to verifying the stage to printing the stage complete message with sounds.

![Level](https://github.com/vaibhavdaren/turtleblocksjs/blob/tutorials/tutcompsite/documentation/doc3.PNG)

1. The stage load block sets the turtle to centre of the to be traced shape .Draws the to be traced shape with the help of chi action.  
2. chi sets the turtle to relavant position and calls the shado action block with draws the required shape in purple color.
3. Stage load finally sets the pen color to yellow which is the color on which the check logic of the stages work.

![Level](https://github.com/vaibhavdaren/turtleblocksjs/blob/tutorials/tutcompsite/documentation/doc4.PNG)

1. The other start blocks run concurrently on the other hand and loads the images which contains the relavant artwork of the stage and other sprites.
2. It also contains the checking logic of the stage. Which is the crux of the project and verifies the shape drawn by the user.
3. Microop and process checks the shape drawn by the user in pixel by pixel format.
4. If the image traced is same as the challenge image  global value of flag is set to 1 and Checkpoint Reached message is printed.

![Level](https://github.com/vaibhavdaren/turtleblocksjs/blob/tutorials/tutcompsite/documentation/doc5.PNG)

 

