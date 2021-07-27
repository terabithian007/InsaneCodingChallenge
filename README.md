# The Insane Coding Challenge

Hi! :wave:

Whether you have been sent here by one of our recruitment ninjas, or stumbled upon it by accident, we're excited you're here!

We are on a mission to build the best home fitness solution on the planet. We are using computer vision, augmented reality and artificial intelligence to create workout games. Computer vision tracks your body motion, augmented reality creates the best workout experiences, and artificial intelligence understands the impact of exercise on your body and personalizes your workouts to help you maximise your performance.

<p align="center">
  <a href="https://www.app.insane.ai/careers"><img src="https://i.imgur.com/Acib87qb.png"/></a>
</p>

This document describes the coding challenge for those interested in working with us. You are free to refer any websites/blogs/videos while attempting this challenge. Just don't forget to mention the major sources in the README file.

## Swords and Shields

### Act 1 || Scene 1 [Front End]

Our game designers "Oliver Klozoff" and "Ollie Tabooger" came up with the idea of building a 4x4 Tic Tac Toe with a medieval twist. They came with the designs of all the required elements but need your help to build a working prototype of the game.

For the first prototype, the idea is to create an offline version of the game where both players take turns on the same device. The design of the screens is described in the [Act 1 || Scene 1](descriptions/act1scene1.pdf)

Your task is to implement this as an app/website using the language and framework of your choice.

### Act 1 || Scene 2 [Back End]

The launch of "Swords and Shields" was a huge success but once the COVID-19 lockdowns started, a lot of users started finding it really difficult to have someone to play the offline version of the game with.

The next task is to make an online version of the game through which 2 friends can play against each other at the comfort/safety of their own homes. 

The design of the screens required for this is described in the [Act 1 || Scene 2](descriptions/act1scene2.pdf)

You will need to use [sockets](https://socket.io/) to develop the multiplayer functionality. If you are not comfortable with sockets then you can figure out a combination of SSE and REST APIs to achieve this (Although sockets would be preferred).

### Act 1 || Scene 3 [Databases]

Once the online version of the game was released, users instantly fell in love with the feature and started playing 100's of matches everyday. As the number of games increased some of the players wanted a feature that allowed them to go through the results of their previous matches, bookmark the ones they liked and filter the results based on won/lost/bookmarked games.

The next task is to build a database that stores the results(final board positions) of the previous matches, allows users to select the matches they liked and filter the results according to their needs.

The design of the screens required for this is described in the [Act 1 || Scene 3](descriptions/act1scene3.pdf)


### Act 2 || Scene 1 [Front End - Game Variation]

A month after the launch of the previous version, players started churning away from the game. A survey of the churned users pointed to a core problem that most of them were facing - "The game had become monotonous". 

In order to tackle this problem, a new feature needs to be added which can add more layers of strategy to the game. In the new version of "Swords and Shields", before the game starts, the player who is creating the game can decide on another combination of 4 tiles which will be used as a tie breaker in case none of the players end up getting any "4 in a line" winning combination. In case of a tie, the player who ends up having more number of these "tie-breaker" combination would win the game.

Note: Just like the basic working of Tic Tac Toe, any rotated version of the "Tie-breaker" combination should also considered during the scoring.

The design of the screens required for this is described in the [Act 2 || Scene 1](descriptions/act2scene1.pdf)

### Act 3 || Scene 1 [Algorithms]

With the new game variation, players want a way to practice and learn new strategies of winning the game, but it is difficult to find friends who can practice with them on the same schedule.

In order to learn new strategies, an option to fight against AI bots needs to be added. Your task is to design the algorithm for these AI players and implement an AI mode in the game.
For the MVP, you can ignore the tie-breaker scenario and design an algorithm for the AI player that will optimize for winning with the "4 in a line" strategy.

The design of the screens required for this is described in the [Act 3 || Scene 1](descriptions/act3scene1.pdf)

### Act 3 || Scene 2 [Advanced Algorithms]

As the players started getting better by training against the bots, the need to develop smarter bots with the ability to handle the tie-breaker scenario increased.

Your task is to update the algorithm designed in the above step to optimize for handling the tie-breaker patterns in the new variation of the game.

## The Handover

Just make a repo on github (or any of its accessible alternatives) and shoot us a mail at careers@insane.ai with the link to the task.

We really appreciate the time and effort it took to complete the task! We promise to return the favor as best as we can.

## The Review

We believe that code is like humour. When you have to explain it, it's bad.

But do include a README file briefly describing your thought process and any other points you want to highlight. During the review we would look at the project structure, architecture and signs of good coding practices (Formatting/Naming Conventions/Comments)


