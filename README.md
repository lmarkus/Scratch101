# Summer Code Camp - Scratch 101

This is a 12-class syllabus aimed at children ages 7 to 11. The objective of this course is to provide an introduction to basic programming concepts, using Scratch as a foundational tool.

The focus will be on creating simple games, where each one either introduces new concepts while building on, and reinforcing the learnings from previous classes.

One very important tool that will be taught is the use of Flow Diagrams.  We don't want students jumping straight into solving the problems / creating the games. It's *essential* that we teach them to plan ahead.  All class projects should first be discussed at high level, to ensure understanding, imagine possible solutions and approaches. This discussion activity should be followed by creating a flow diagram for the agreed on solution (This will serve as a roadmap for the students to then implement their solution on Scratch). Only then should students move on to actually writing the program.

One of the beautiful things about Scratch, is that due to its interface, a flow diagram will practically have a 1:1 mapping to the final program.

At the end of this course, students should be able to approach a new problem in a structured way, and apply engineering techniques for writing an algorithm / well structured program to solve it.  All students should feel comfortable moving up to a whiteboard and explaining their thought process.

## Class 1
Introduction to computers / programming

### Objectives:
* Welcome students. Level set about expectations for code camp
* Talk about basic computer concepts (CPU, Memory, Networking)
* Very brief history of computers, showing images from early computers	(ENIAC, Disc Storage Devices, etc), compare against modern equivalents
* Explain that computers are extremely dumb, and they will do exactly what you tell them to. Run a practice excercise where kids give you instructions and you follow them *literally* (eg: https://www.youtube.com/watch?v=cDA3_5982h8 )
* Intro to Scratch (Ensure students all have accounts so they can save their projects)
* Dance Animation mini project: http://scratch.mit.edu/dance/ 


## Class 2
Number Guessing Game Part 1 - You guess the computer's number [Link](https://scratch.mit.edu/projects/157331086/)

Special note: Class 2 should begin with an explanation of Flow Diagrams. 

### Objectives 
* Input / Output
* Variables
* Random Number generation
* If - else statements.
* Forever Loops

### Variations
* Limit the number of guesses a player has



## Class 3
Number Guessing Game Part 2 - The computer guesses your number [Link](https://scratch.mit.edu/projects/157334625/)

Special notes: Heads up, instructors. This is a tough one, but a real eye opener for students. When you talk about the problem description, and try to do a high level solution, you'll find that binary search is a very intuitive way to solve the problem, yet it will be hard for the students to translate that intuition into actual, bug-free code.  

You should expect to explain the principle behind binary search quite a few times.
Common pitfalls will include number rounding, and getting the search range right when you have to discard the lower half.

Spend as much time as you need making sure all the studens have drawn a good flow diagram as a foundation.

### Objectives
* Implement a binary search algorithm
* Nested operations with variables
* Other types of loops (While loops vs For Loops)
* String Concatenation
* Stop conditions for loops 



## Class 4
Hangman - [Link](https://scratch.mit.edu/projects/159401351/)

Notes: Things are getting interesting now.  Hangman is another game that's simple to understand, but requires quite a few steps to implement with Scratch's simple elements. This class introduces arrays, so you should spen some time explaining the concept. ( **Side Note:** Scracth does not use zero-indexed arrays.  That's right. The first element of an array is... **1**)

This class is a good place to start introducing functions ("custom blocks" in Scratch), as a means of grouping repetitive stuff. There's going to be a lot of new things thrown at students in this class, so be liberal with hints and help.

Start the class with an actual game of hangman on the whiteboard, to refresh the concepts for students.

In scratch the easiest way to "draw" the hangman, is by adding additional cosumes to the base cat sprite. (See example code).
You should have ~10 costumes, where each costume corresponds to one try (See the example project). Every wrong guess advances to the next costume.

Don't forget to have students play each others game!

### Objectives
* Lists
* Manipulation of text strings
* Adding/removing elements in a list
* Iterating through a list.
* Sprite manipulation (Kids get to draw their own hangman sprites)
* Custom Blocks (Functions)


## Class 5
Hungry Crabs - [Link](https://scratch.mit.edu/projects/168728586/)

Crabs are coming at you from all sides! Slap the crabs to keep them away from the apple.  The more crabs you slap, the faster they get!
You can make the game more fun (and difficult) by having students stand farther away from the computer.

This class introduces one of Scratch's must fun elements: The webcam.
Scratch makes it super simple to have video captured from the webcam interact with sprites. If you've ever played with a Microsoft Kinnect, you'll be immediately familiar with this concept. (And the students will likely be, as well)

### Objectives:

* Using Video - I highly recommend that instructors go through the documentation for the video blocks in scratch: https://wiki.scratch.mit.edu/wiki/Video_()_on_()_(block)
* Working with Clones: Students will be introduced to clones, and will have to learn how to program a sprite for multiple scenarios. (eg: How should a clone behave depending on its starting point)
* Using levels to automatically adjust the dificulty of a game (This is a basic game mechanic.)


#### Things to watch out for:
The camera works best in a well lit location, preferably against a white (or light) background.


#### Fun activity: 
Tournament! See who can get the highest score.


## Class 6
Pong - [Link](https://scratch.mit.edu/projects/159744887/)  

Special Activity: Talk about the history of video games, but do it backwards. Start with todays modern games, and work your way down to Atari / Pong.  Use plenty of visual examples.	

Notes:
Two concepts will be introduced in this class: 
* 2-Dimension coordinates: The best way I've found to do this is to simply boil it down to the fact that **X** means left/right, and **Y** means up/down.  (You'll also have to deal with negative numbers, but kids should already have this concept floating around in their brains via substraction). Scratch uses the center of the working area as (0,0), so when designing your programs it helps to draw x/y axes on the whiteboard. The drawing area is a roughly 480x360 rectangle (Meaning that it goes from [-240,-180] (Bottom-Left) to (240,180) (Top-Right).  Drawing these boundaries on the board is super helpful for students. 

* Events / : The paddles will be controlled via keyboard, so students will start scripting individual sprites.

### Objectives
* Reinforce drawing your own sprites (For the paddles)
* Variables for keeping score
* Variables as "variable data", allowing controls of in-game elements (Paddle speed, ball speed).  This is an excellent opportunity to lay down some good programming practices. Let students manually assign a value to each paddle motion (4 total), and then, ask them to change it. Once they've changed all four, re-introduce the use of variables, but this time, not just as  data stores.
* Keyboard control for games.
* Scratch motion control (Bounce on edge, actions then two colors are touching, etc)
* Thinking in 2 dimensions. (Position, speed, direction, etc)


(Fun activity: Pong Tournament with the best project in the class)

## Class #7
Flappy Bat - [Link](https://scratch.mit.edu/projects/160841634/)

Create a clone of the popular "Flappy Bird" game. This game will focus on polish.  Even though it's a relatively simple game, Students can be provided ample time to tweak their game for optimal play (Gravity, speed, control sensitivity), as well as introducing a few new concepts from slack

### Objectives:
* Fine tuning several variables to improve the game, and set the difficulty level.
* Working with cloned objects in Scratch

## Class 8
Cat & Mouse Game - [Link](https://scratch.mit.edu/projects/160739550/#player)
Create a simple game where you control a cat, and the objective is catching a mouse, as many times as possible within a given timeframe (eg: 1 minute)
The mouse is controlled by the computer. Students should come up with a strategy to make the mouse hard to catch.

A player wins the game by obtaining the highest score. However, a **programmer** wins the best program, by making his mouse the one hardest to catch. (This gives students an incentive to think things through, and try different strategies.)

Notes:
This game is simple, so we'll use this opportunity to introduce event broadcasting to coordinate sprites.  Broadcasting should be use to reset the sprites to starting conditions when the mouse is caught.

Extra notes: Reduce sprite sizes by about 50% to make better use of the stage area

### Objectives:
* Working with motion (Moving various objects around the design area)
* Working with costume changes ( Most scratch sprites have two costumes which can be used to give the appearance of motion)
* Working with object sensing (Edge bouncing, sprite proximity, sprites touching)
* Work with Scratch Timers.
* Using event broadcasting for complex sprite coordination. (eg: Resetting a game.)
* Planning strategies, anticipating the opponents move. (Explain how this is a very rudimentary form of artificial intelligence)


## Class 9
Angry Birds - [Link](https://scratch.mit.edu/projects/168731089/)
We'll make a simple clone of Angry Birds. This will probably the most complex project that the students will have to tackle in this class. It's an excellent opportunity to reinforce math concepts learned such as movement in two dimensions, and introduce some new ones (to some) like trigonometry, and force vectoring.

Your job as a teacher is to boil down the concepts so that your entire audience can understand them. However when it comes to programming, you'll need to feed them some answers for some of the more complex math formulas (eg: SIN, COS to figure our trajectory of the bird, etc).

This project will typically spread out across two classes.

At this point, students should have all the basic programming skills needed, so no new scratch concepts will be learned here. This class is all about putting all the learnings to use into one large scale project.

### Objectives

* Reinforce all past learnings.
* Force vectors (Yes, really!)
* Angles

## Class 10
Angry Birds (Cont.)


## Class #11
Presentation Skills for children
Students should pick their favorite project to present (Don't make the presentation optional, otherwise they will all try to get out of it :) ).
There will only be two objectives for this class. The first is teaching kids how to effectively present. The focus should be both on the project and the skills that they learned along the way.  Make sure that they have several practice runs, so that they feel comfortabl efor their presentations.

The second objective it to do a retrospective on the learnings from the code camp.  Go over the individual projects, and discuss what the students found interesting.  Be sure to get feedback on yourself as a teacher.  These students are usually brutally honest. Ask what worked, what didn't work, and what they would do differently.

A nice closing touch, is to talk about your own journey and observations as a teacher, on the things that they learned, and the breaktrhoughs you've seen the class have.

## Class #12
Presentations.
Sit back, relax, and cheer for your team!
