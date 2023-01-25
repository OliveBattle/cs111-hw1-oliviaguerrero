# Context Free

##  Who is this programming language for?
This program is for creating vector art using programming syntax.

## What is easy to do in this language? Why is it easy?
It is easy to make recursive shapes that repeat and shrink in size, as each shape can call itself.

## What is hard to do in this language? Why is it hard?
It is hard to draw complicated designs that don't repeat (such as words), as each word has to be its own specifically coded shape.

## How did you learn how to program in this language?
I looked through the documentation, editing parts of the starting default "welcome" program until I understood what each change made. Then I started a program from the ground up, bringing in new elements as necessary.

## What is the underlying _computational model_ for this programming language? 
The program runs through a set of shapes. When it reaches one of three root shapes, it prints the shape to the image, and if the size gets too small, it disregards it. Otherwise, it goes through every shape that the current shape calls, then steps back to the prior shape until you've completely worked through the starting shape.


## What do you think is interesting about the ContextFree program you wrote?
Perspective drawing - since you have to start with the largest object and work inwards, as opposed to starting from the horizon point, you're forced into carefully fine tuning every single aspect of the drawing to get the horizon points of different repeating elements to line up.
