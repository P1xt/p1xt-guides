#GigaWars

##Description

###Project Overview

GigaWars is an epic space-combat strategy game where you unleash a fleet of ships to destroy your enemy's base.  The player (human or computer) will decide what ships to send into battle when, managing their resources.  The individual ships will control themselves, however.  In the distant future we no longer need to send soldiers into harms way; we can program the ships to fly themselves!  You will write in-depth logic for several ship types to create glorious computer-controlled space battles.  You will also write logic for computer players to play the game.

###Why this project?

GigaWars is a chance for you to combine the skills that allowed you to create Space Kerfuffle! with your newfound mastery of game AI.  This project will demonstrate mastery of a variety of game development concepts.  The unique factor that separates video games from other media is their interactivity; their ability to create a dynamic user experience respond intelligently and meaningfully to situations.  AI is the cornerstone of this interactivity.  Imagine the power you will feel watching two fleets of ships duke it out, knowing that every automated maneuver is the result of your careful planning!

###What will I learn?

This project will provide hands-on experience writing the type of AI scripts that you see in video games everywhere.  Programming the ship logic will give you a chance to practice writing logic for active game entities and apply the steering and pathfinding techniques you learned in the course.  Creating the computer agent that decides what ships to deploy when will be an exercise in creating high-level, strategic AI using decision trees, state machines, or whatever other AI techniques you deem appropriate.

##Completion

Follow these steps to complete the project:

* Create a new libGDX project.  Be sure to check the "Ai" box in the libGDX project setup tool when generating your project.  This will automatically add the relevant dependencies to your build.gradle files.
* Download the provided game assets (link coming soon), or find/create your own!
* Create all the classes you need to render an epic space battle.  The basic gameplay rules are as follows:
    * There are two players.  They can both be computer players, or there can be a human and a computer player.  Each player has a base, which can be destroyed by the enemy player.
    * Each player has access to a resource or resources, and they gain resources over time.  How exactly this works is up to you.
    * Each player can use a resource or resources to deploy ships.  The players do not control the ships directly!  Instead, the ships should have automated behavior.
    * Ships have decision making and steering AI that makes them fight once deployed.  Ships can attack one another or the enemy's base.  There is a mechanism by which the enemy base can be destroyed.
* Create game AI that controls the ships and controls a computer player.
* Watch your fleets fight!

If you're unsure how to go about this, here are some design tips:
* Rendering and updating all the ships is not too different from the work you did for Project 2: Space Kerfuffle!  You can use your code from that project as an example.
* For resources, the simplest option is to have a resource simply accumulate over time for each player.  From there, there are a few simple ways to spice things up.
    * Make each side earn interest on there current resource total, so players must make strategic decisions about when to save up and accumulate more total resources, and when to spend and deploy more units.
    * Make each side earn resources as they destroy enemy ships.
    * Make a unit that can retrieve resources from the environment, such as from asteroids.
* For ship decision making, and for the computer player's decision making, we recommend using `gdx.ai` [behavior trees](https://github.com/libgdx/gdx-ai/wiki/Behavior-Trees) or [state machines](https://github.com/libgdx/gdx-ai/wiki/State-Machine).
* For ship steering, we recommend using the `gdx.ai` [steering API](https://github.com/libgdx/gdx-ai/wiki/Steering-Behaviors).
* Use the built-in `gdx.ai` classes!  A lot of common behaviors, especially in the steer package, are created for you.  Using or extending these classes will be much easier than implementing everything yourself.
* The enemy ship AI is the most complex part of the project.  We recommend starting with getting some basic behaviors working for one or two ships, like avoiding walls or chasing enemies, and building up gradually from there.  Once you have your ship behavior working, it will be easy to get the resources/ship purchasing gameplay elements in place.