<h1>Documentation of Challenges </h1>

--------

The challenges contain <b> 4 levels - Beginner, Medium, Advanced and Bonus. </b> <br>
<b>Each level consists of 12 challenges<b>.<br>

Each of the stage is based on a similar design pattern structure comprising of the following blocks as described below along with the final stage representation.The initial design was drafted by my mentor Walter Bender.
All the other challenges are built taking inspiration from it.

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

 --------
The challenges require a lot of artwork i.e. clipart in the form of images .All cliparts are used from the site https://openclipart.org/ .Design UI/UX decisons are done with help of Mentor Jaskirat Singh and P. Seetarama Raju.

<h3>A List of Challenges Level wise:- </h3>

<h4>Beginner</h4>
 
 1.  The forward Block	
 2.  Right
 3.  Other Side
 4.  North West
 5.  The SetXY Block
 6.  The Box Palette
 7.  The Pen Color Block	
 8.  The Background Block	
 9.  The If Else Block
 10.  The Square: Repeat Block	
 11.  Fill Square	
 12.  Last-Easy Hut
 
<h4>Medium</h4>

 1. The Triangle	
 2. The Mirror Image	
 3. The Pentagon
 4. Print Name	
 5. Show Name	
 6. Diagonals of Square
 7. The Steps	
 8. The Parallelogram	
 9. The Hexagon
 10. Circle	
 11. Star	
 12. Dotted Line Square
 

<h4>Advanced</h4>

 1. The Complex Star
 2. Angle Bisector	
 3. 4 Coloured Boxes
 4. Wind Mill	
 5.  The Square Painting	
 6.  Sandwich
 7.  Triangular Pattern	
 8.  Octagon Flower	
 9.  Pentagon Ring
 10.  Recursion. tree	
 11.  The Rasengan	
 12.  Boss 

<h4>Bonus</h4>

 1. IF ELSE CONDITIONAL	
 2. HEAPS PUSH	
 3. SUM HEAP
 4. TRAVERSE HEAP	
 5. TRY YOURSELF.ALGO	
 6. ACTION.ARGUMENT PASSING
 7. FUNCTION-ALGO 2	
 8. EVENTS	
 9. MINI-PROJECT
 10. DICTIONARY	
 11. DICTIONARY:ALGO	
 12. Boss :Recursion
 
 
<hr>
The Resources  used to built the challenges can be found on the resources folder of the  repository at 
https://github.com/vaibhavdaren/turtleblocksjs/tree/tutorials/tutcompsite/documentation/resources

