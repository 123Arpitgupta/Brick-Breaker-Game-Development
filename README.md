                                                                                             Project Implementation

1. This is a java project so you can use the IDE like eclipse and Net beans etc.

2. Initially, you have to create a frame for the game. For that create a class called Main which contains the main method. Then create boundaries by assigning the dimension. Along with this use JFrame which is a built-in class for the minimize and close functions. Import Jframe package also.

3. Next, create a Run game class and extend it with JPanel. Import JPanel package also.

4. Use keylistener and action listener packages. KeyListener for moving the small platform with arrow

keys and ActionListener for moving the ball. Add an unimplemented method for it. 5. Mention the initial location of the slider or platform along with ball location and direction with x and y

axis.

6. Then create Rungame() constructor for calling the methods for the timer, keylistener, and many more.

7. Create a function shapes() which include the graphics of ball, bricks, and slider. It also includes a background color.

8. Use setColor() for background color and fillRect() for boxes. Continue this for all other shapes.

9. Then assign the limitations in key events for the movement of the slider so that it does not go out of the border.

10. 10. Enter code in actionPerformed event for the movement of the ball. You can use the if a condition for that if the ball collides with boundaries or sliders, it will bounce.

11. The next step is to create bricks and actions related to bricks. Create a Brick class. Insert condition in the function so that the call interacts with the brick boundary then it will bounce along with the vanishing brick. Don't forget to create a background colored border to the bricks for an individual break.

12. Create a loop for calculating score after every interaction of brick and ball...

13. The final step is what makes you fail and win the game. If all bricks disappear then the player Won the game by displaying a title as WON!!!. And if the ball touches the lower boundary the player fails with the display of GAME OVER.

