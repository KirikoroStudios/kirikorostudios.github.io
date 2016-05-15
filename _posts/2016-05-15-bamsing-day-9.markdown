---
title: "Bamsing - Day 9: One Big State Machine"
layout: post
date: 2016-05-15
tag:
- bamsing
- first week
blog: true
---
# Day 9
Hi, My name is Pontus Lindgren @happypwn on Twitter.
I'm 9 Days in on [finishing this prototype](/bamsing-prototype) of my game [Bamsing](http://bamsing.com).

# What did I do on Day 9?
Yesterday I took a day off to celebrate my grandmothers 80th birthday. It was great!

Today I have been doing some clean up work of the features I implemented recently. I have built my game as one big state machine with sub-state machines.
At the top level I have a state machine with 3 states called Gameplay, Cutscene and Menu. Every object in my game that has a behavior
that changes has another state machine on them that listen to the top level state machine and adjust their state and behavior accordingly.
Some have more than 4 state machines controlling different behaviors!

It's works very well for me to organize this way, and I only have to worry about what is happening in a state rather than a whole
stateless update loop with a lot of checks to get the desired behavior.

Short blog today as I did a short workday today.

Tomorrow I will be implementing a way to handle the player falling of platforms. And start tying together the starting cutscenes + tutorial-gameplay with the puzzle mechanics!

# How can you help?
You can help by providing feedback, I would love to hear absolutely any thoughts you have about the game.

And by following company in any of its outlets as well <3:

 - [Email sign up](http://eepurl.com/b0UUhj)
 - [Facebook](http://Facebook.com/kirikorostudios)
 - [Twitter](http://twitter.com/happypwn)
