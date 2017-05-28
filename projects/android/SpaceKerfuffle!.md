#Project 2: Space Kerfuffle!

##Project Description
###Project Overview

Space Kerfuffle! is a top down, starfighter combat game.  Players assume the role of an intrepid spacefighter pilot flying headlong into a swarm of aliens or robots or something else evil that wants to destroy humanity, probably.  Players control a spacecraft and fire projectiles at oncoming enemies who do the same.  Explosions happen.  Numbers go up.

See our prototype of the game here for inspiration.  Note that your game doesn’t have to function exactly like this!  You can be creative and use your own design ideas.  Make sure to read and review the project rubric before submitting, however.

(No aliens or robots were harmed in the creation of this Nanodegree program.)

###Why this project?

In How to Build a Platfroming Using LibGDX, you built GigaGal, an old-school action platformer.  Rather than recreating a similar project here, making Space Kerfuffle! will give you a chance to explore yet another classic arcade game genre.  You will get a chance to apply the skills you learned in class, but also stretch your wings (no pun intended!) a bit and design a complex game on your own.  When you're done, you'll have a way-cool space combat game to add to your portfolio.

###What will I learn?

This project provides an opportunity to practice many of the core skills of 2D game development: key-frame animation, 2D collision detection, asset loading and management, level design and loading, and efficiently structuring a game with many objects spawning, getting destroyed, and flying across the screen.  More important than any individual skill is the knowledge that you can make a complex game like this yourself.  Complete this project, and you will be able to apply the same skills to making a variety of 2D games--including ones you design yourself.

###Why is this project meaningful to my career?

Top-down fighter plane games are a classic arcade game genre, and they employ complicated game mechanics and animation.  Completing this project demonstrates a strong command of essential 2D game development skills.  You can also show potential employers or collaborators that you can make an intensive game that runs on desktop or mobile (or as a browser game).  This project is an excellent way to display a wide range of technical 2D game development ability.

##Completing the Project

###Getting Started

First, you will need to create a project using the LibGDX project generator tool. If you need a refresher on how to use the project generator, check out this video from the 2D Game Development course.

Once you have your project set up, you will need one class that extends Game, and one class that implements Screen or extends ScreenAdapter. For a model on how to set this up, look at how we made the GigaGal game in the second course.

Create an ExtendViewport, just like we did for GigaGal, but this one will extend vertically rather than horizontally. Once you have a Game, a Screen or ScreenAdapter, and a Viewport, you’re ready to start rendering your game.

###Importing Assets

We provide a bunch of art assets for Space Kerfuffle!, which you can download here. These include animation frames for multiple ship types while firing, moving left, and moving right, animation frames for a big bad boss ship, as well as a bunch of projectiles and powerups that you can use. It’s up to you what sprites you use for what parts of the game, and you are free to use your own if you or any of your friends do game art.

Loading all of these assets individually would be sub-optimal, so you will load them all at once using a TexturePacker. See Level 2-1: Sprites and Animations from How to Build a Platformer Using LibGDX for an example of how to use the built in LibGDX TexturePacker tool. This will pack all the sprite you want to use into a single image called an asset. Inside your game, you will access images from this atlas.

To access things from your TextureAtlas, you need to create an instance of the AssetManager class. You can then access individual images from your atlas using the findRegion() method.  Instead of using the findRegion() method of the TextureAtlas class at runtime, which is slow, you should load all the textures into memory ahead of time, and save them as final variables somewhere.

###Classes for the Player, Enemies, and Projectiles

It’s up to you what classes you make for SpaceKerfuffle!, but we recommend at least making a class for the player’s ship, one for enemy ship, and one for projectiles. You may choose to employ some inheritance here, as many of these objects share certain properties. These classes should manage the position and state of these entities on the screen, and also know how to draw these objects. You may want to implement methods such as `render()` or `update()`.

Inside the player ship class, or elsewhere, you will need to get input from the player themselves. The player must be able to move their ship using the arrow keys on the desktop backend, and the ship should follow their finger on mobile. There should be a button for firing projectiles on desktop, and we recommend having your ship perpetually firing on mobile. In games like this, many players will be mashing the shoot button anyway!

For making the player and defining controls, you might want to review Level 1-6: User Input from 2D Game Development with LibGDX and Level 2-2: The Player from How to Build a Platformer Using LibGDX.  For inspiration on creating enemy classes, check out Level 2-5: The Enemies.

You will also need to make a boss battle to come at the end of your level, so a class (or several!) for the boss is recommended. It’s up to you how the boss behaves, but a good boss battle has phases and forces the player to react to the boss’ tactics. Be creative!

###Rendering Your Objects

We recommend that you have some sort of Level class that keeps track of the player, enemies, and projectiles using data structures such as arrays. You can iterate through these arrays and render each individual object in a render method that you can call from the render method of your Screen object.

In order to animate your objects in real time, you will need to put together the textures you extracted from your atlas into Animation objects, and use the getKeyFrame() method of the Animation class to get the appropriate frame for any given moment. See how we animated GigaGal in Level 2-2: The Player for an example of how to do this.

You will also need to implement a collision detection mechanic that tests whether entities in your game have been hit by projectiles, removing entities that are destroyed, and spawning explosion animations. You can check out Level 2-6: The Bullets for inspiration here.

###Other Requirements

Your game must load level data from a file rather than hard-coding it all. See Level 2-7: Level Loading (_coming soon_) for a model on how to accomplish this. We recommend using the Overlap2d or Tile map editors to create a JSON, which you can then parse using <a href="https://github.com/libgdx/libgdx/wiki/Reading-&-writing-JSON" target="_blank">LibGDX’s built-in JSON parsing classes</a>.

Additionally, you will need to render a HUD that displays the player’s score, which should increase as they destroy enemies. If the player runs out of lives, a Game Over message should be displayed. If the player defeats the boss, a You Win! message should be displayed along with their final score.

##Submitting Your Project

Before submitting your project for evaluation, we recommend that you check that each of the following is true:

* Your app compiles & runs as expected
* You are proud of your app and its output
* You completed your project according to the instructions
* You checked your project against [the rubric](https://review.udacity.com/#!/projects/5761872486/rubric)