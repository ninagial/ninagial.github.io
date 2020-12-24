---
layout: post
title: I made a small revision script for index cards in python
---





Some notes on [this Python script](https://github.com/ninagial/flashcards) I wrote in order to revise larger, and more structured, decks of index cards.

# Motivation

Every now and then I need to learn some complex stuff. In some areas, or for specific tasks, memorization is useful, if not absolutely necessary.

Now, I don't know if revision cards work for everybody, but they work for me, and I have written some hasty scripts in the past to do the job.

But as the same procedure applies to different tasks, and since the subject matter in some of the tasks needs to be better structured, I felt the urge to do it in a more concrete fashion.

# Structure

For the time being I use two classes, one to hold word pairs, and another to hold a whole deck of cards.

Several features started coming in handy using decks, so for example I would like to swap the order in the pairs, or shuffle the deck.

I needed a mechanism for putting cards aside for revision, as well as using subsets of cards, for different purposes.

# Directions

There are a couple of small things I want to add, such as a lookup function, and allowing arguments to be passed from the command line.

I hadn't felt the need to do it so far, because I am currently modifying in a local branch the subject matter script. 

There is a lot to do there programmatically, populating the decks manually, and creating subset decks, as well as actually organizing the subject matter consistently. 

It is possible I will upload these things at some point, for people who want to learn in similar domains.

Most importantly, I want to make sure that this solution works well for non latin characters and math formulas.

