## What is an Abstraction?

In your Hardware report you included an Abstract - a brief summary of the entire report.  In order to write it you had to focus on only the most important concepts that you wrote about, removing a lot of the details.

**Abstraction reduces information and detail to facilitate focus on relevant concepts.**

## Example 1 (Algorithms):

In class we saw an algorithm for walking to a certain area while navigating around obstacles.  We didn’t include steps on how to walk (lift the right leg, move forward, put down etc) because it wasn’t the point of the exercise (navigating).  This is an example of an abstraction - we simplified certain details in order to focus on needs to be accomplished.

## Example 2 (Digital Data):

You previously learned about different ways digital data can be represented.  Digital data uses many different types of abstractions.

Take the colour **Yellow**.  That in itself is an abstraction - we know what yellow looks like without knowing all the details about how it’s made or represented in the computer.  This is called “high level” because it’s easily understood by humans.

In Processing we would represent Yellow with the **RGB values (255, 255, 0)**.  This provides more detail (mixing Red and Green) but it’s still somewhat easy for us to understand.

We also learned about **Hexadecimal (#FFFF00)** which is used because it’s more easily understood by humans, but it’s getting closer to the language that computers use.

Finally we have **Binary (111111111111111100000000)** which is what computers use to process data.

These are multiple levels of abstraction, each providing increasing levels of detail.  We could go even further if wanted to, because computers don’t actually use “numbers” - they represent those binary numbers using transistors, logic gates etc.

## Example 3 (Programming):

All of the coding that we do is at a “high level”, so that we (humans) can understand.  But even within the programming language (Processing), there are many abstractions that we use all the time.

`rect(x, y, width, height)`

When we draw a rectangle, we have made use of an abstraction.  The actual process of drawing a rectangle on the screen involves many complicated steps.  But the creators of the language have removed almost all the details for us so we can easily draw the shape.

When we learned about functions we described it as reusable code.  The ability to reuse code is an abstraction because it gives you less to think about (once you’ve initially created it).  During the actual creation of the function, you may also find yourself removing detail you don’t feel is relevant to what you are trying to accomplish.

Even using a `List` (like in Exercise 7) is an example of an abstraction.  You didn't have to think about how to add/remove each individual tree.  Once you set up your List (and `for` loops), all of the trees get handled in the same way.

In your next assignment and in your Create Task, you will be asked to discuss an abstraction that you used.









