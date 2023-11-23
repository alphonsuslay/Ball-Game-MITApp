# What the Project does
The project is a Pong ball game created using MIT app Inventor.
It is a ball game where users must prevent the ball from hitting the bottom of the space using a slider.

# How the Project Works
The project opens a start game screen called "Screen 1" which then allows the user to set their ball speed from 1-5 using a slider. Upon pressing the start button, it intializes another screen where the game is held. 

Clicking the "Sound On" checkbox will enable user to have audio generated when the ball hits either the slier or the top,left, or right edge of the screen. 
Pressing the start button will start the game with the ball from the top of the screen to fall down. The goal is to use the slider and bounce the ball back. Each successful bounce, +1 is added to the score and is displayed on the score counter on the bottom left.

If the ball touches the bottom edge of the screen, the game can no longer be played and the background will show a game over sign held by the cat.

To reset the game, simply press the Reset Button.

# Enhancements Added
**Start Screen 'Screen 1'**
1. Colors used for most components are a custom color code ``#f7f3e7ff`` and ``#bf515bff``. This creates an aesthetic basic look.
2. Added a start screen which consists of a Banner + Game Title + Slider to adjust the ball speed + START button
3. Sliding the slider towards the left is able to decrease the ball speed while sliding the slider to the right will increase the ball speed.
4. Not sliding the slider at all, will set the default ball speed to 1.
5. Start button pressed when save the ball speed in TinyDB, a database, and open the Game Screen.


**Game Screen 'Screen 2**
1. Colors used for most components are a custom color code ``#f7f3e7ff`` and ``#bf515bff``. This creates an aesthetic basic look.
2. Ball Speed value is called over from the Start Screen and initialized here. Setting the default ball speed to what is predetermiend in Start Screen.
3. Modified the canvas background setting to a Cat Image.
5. Modified the slider such that it is a cat bowl to match the theme of cats.
6. Implemented a feature when the START button is clicked, the ball will now spawn randomly along the x-axis of the screen. Specifically, the ball's x-coordinate is set to a random integer between 1 and 300, allowing it to appear at different positions from left to right on the screen.
7. Modified the GameOver situation such that the canvas backgroud would display a GameOver Sign held by the cat.

