#Project 1: Outbreak

##Project Description

###Project overview

For this project, you will make a simple game reminiscent of classic Atari arcade game Breakout. Players will control a platform at the bottom of the screen that moves from side to side to intercept a ball that will bounce on impact. The goal is to stop the ball from falling past your platform and deflect it into various blocks in the upper half of the screen. When the ball collides with a block, the block is destroyed.

You will create a LibGDX project, implement a Screen, draw the game objects using a ShapeRenderer, and program the controls and real-time motion of the ball.

###Why this project?

A breakout clone looks simple on the surface but there are lots of mechanics that go into making even a small game. Doing this project will allow you to build your skills and give you the confidence to tackle even more difficult projects.

###What will I learn?

This project provides an opportunity to practice many of the core skills of 2D game development: key-frame animation, 2D collision detection, asset loading and management, level design and loading, and efficiently structuring a game with many objects spawning, getting destroyed, and flying across the screen.  More important than any individual skill is the knowledge that you can make a complex game like this yourself.  Complete this project, and you will be able to apply the same skills to making a variety of 2D games--including ones you design yourself.

###Why is this project meaningful to my career?

Completing this project demonstrates a strong command of essential 2D game development skills.  You can also show potential employers or collaborators that you can make an intensive game that runs on desktop or mobile (or as a browser game).  This project is an excellent way to display a wide range of technical 2D game development ability.

##Completing the Project

Completing the project consists of the following tasks:

* Make a LibGDX project using the project generator tool.
* Create a play screen using the Game class and Screen interface.
* Write a render loop that displays all the game objects, including the player's platform, the ball, and the blocks, using ShapeRenderer.
* Program the gameplay, including: 
 * Polling for input to move the platform (arrow keys for the desktop build, and using the accelerometer on Android).
 * Moving the ball in real time and programming its bounce behavior. 
 * Collision detection that makes the ball bounce when hitting a wall or block or the player platform, and destroying blocks on hit.

###Bonus challenges

* Implement a Score that goes up as the player destroys blocks.
* Add a start screen, Game Over screen, and/or win screen. 
* Implement different difficulty settings (eg the ball moves faster, there is a time limit, blocks take multiple hits).

##Submitting Your Project

Before submitting your project for evaluation, we recommend that you check that each of the following is true:

* Your app compiles & runs as expected
* You are proud of your app and its output
* You completed your project according to the instructions
* You checked your project against [the rubric](https://review.udacity.com/#!/projects/5609616480/rubric)