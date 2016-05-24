---
title: "How to identify the scope of your game"
layout: post
date: 2016-05-24
tag:
 - Game Development
blog: true
---
# How to identify the scope of your game
It can be hard to know which game, or project, is right for the time and resources available to you. I [recently had this problem](/bamsing-day-12/) and was forced to rethink my strategy. So, after some thinking I developed a method to identify the scope of my game ideas. This is useful to develop an ["MVP"](https://en.wikipedia.org/wiki/Minimum_viable_product) of a game and help you make a decision on which project to do based on analysis instead of gut-feeling.

# Divide your game into elements and your elements into needs

First we need to divide our game into elements. I'm going to make it easy for us and use the categories already created and thought through in [The Art Game Design by Schell](http://www.amazon.com/Art-Game-Design-book-lenses/dp/0123694965). I highly recommend you to read this book if you have not already. Anyway, Schell breaks a game down into four categories:
Mechanics, Story, Aesthetics and Technology.

So lets start with an easy example. Lets look at the elements that make up Tetris.
First we begin with the mechanics.
In Tetris, we can almost count the number of mechanics on one hand:

 * A mechanic where the player can adjust the speed and rotation of the currently dropping Tetris-tile
 * A mechanic where the tiles destroy themselves and give the player points in case of a matching line of tiletypes
 * A mechanic where there is always one tile falling on the screen.

This is basicly all the mechanics we need for a MVP of Tetris.

And If we do the same analysis of a more complex example, like The Legend Zelda: Ocarina of Time. We can see, even in the first mechanic example that we have a much larger set of mechanics in this game.

 * A character controller that acts differently based on gamestate, equipped inventory and playerinput.

So in relation to eachother, Tetris has _low_ mechanical needs and Zelda has _high_ mechanical needs.

![The Legend of Zelda: Ocarina of Time - Unused assets](/assets/images/Unused_Great_Fairy.jpg "The Legend of Zelda: Ocarina of Time - Unused assets")
_The Legend of Zelda: Ocarina of Time - Unused assets_


Then we move onto story.

Now a game like Tetris does not even need a storyline to create the value it provides players, it is almost purely gameplay based. And a game like Zelda is very storydriven, even the mechanics and puzzles are integrated into the story. And just imagine all the plot, dialogue and characters and backstories needed to make a world as alive and vibrant as a zelda game.

So even here, Tetris has _Low_ story needs and Zelda has _high_ story needs.

Then we arrive at Aesthetics. Tetris has some requirements on Aesthetics. We need to be able to distinguish the Tetris tiles from eachother. And you might be thinking vibrant colors. But the version that made the Tetris franchise take off was actually a greyscale [game for the original gameboy](https://en.wikipedia.org/wiki/Tetris_(Game_Boy)).

![Tetris for Game Boy](/assets/images/Tetris-Gameboy-7.jpg "Tetris for Game Boy")
_Tetris for Game Boy_

And again, in Zelda I'd argue that the characters, the environment, the sounds and the music is an essential part of the Zelda experience. We can again arrive at the conclusion that Tetris has _Low_ aesthetic needs while Zelda has _High_ aestethic needs.

And then technology. Tetris can be done with a 2d greyscale screen and two arrowbuttons. A game like Zelda Ocarina of Time needs 3d, color and a controller with an analog stick and several buttons.
Here I wrote down Tetris as having _low_ Technical needs and Zelda with _Medium_ Technical needs. Note, a multiplayer game with a matchmakingservice, a client/server software architecture and a server client would land on the _High_ scale here in my opinion.

# Compare the games
So after you've done your analysis what good can come from it? Well, compare them and find a project that fits your time and resources!

Here are some example of two recently popular games:

Clustertruck:

 * Mechanical needs = Low
 * Story needs = Low
 * Aesthetics = Low
 * Technology = Medium

DOOM:

 * Mechanical needs = High
 * Story needs = High
 * Aesthetics = High
 * Technology = High

Now, both games are made by very competent studios, they just vary in size and resources, and so does their games. You really need to think about the scope of your project before you prototype it and before you commit to anything.

# For more content like this you can follow this dev blog in these ways

 - [Facebook](http://Facebook.com/kirikorostudios)
 - [Twitter](http://twitter.com/happypwn)
 - [RSS](http://kirikoro.com/feed.xml)
