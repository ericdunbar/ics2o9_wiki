An _algorithm_ is a set of instructions used to solve a problem.  You use algorithms every day, for example:

```
Getting Ready for School
1. Wake Up
2. Eat Breakfast
3. Brush Teeth
4. Get Dressed
etc
```

Algorithms can be expressed in plain language (like above), flow charts (later!) or pseudocode (code intended to be read by humans and not computers).

There are three main components of algorithms:

**Sequencing**

This refers to the fact that the steps need to be completed in that order (top to bottom).  It wouldn't make sense to `Brush Teeth` before `Wake Up`.

**Selection**

Perhaps something should only happen IF a condition is met.  For example:

```
Getting Ready for School
1. Wake Up
2. I am hungry:
     Eat Breakfast
3. Otherwise:
     Stop at McDonald's on the way to school.  Buy Mr. Kowalczewski a Bacon & Egg McMuffin and coffee (one cream)
```

**Iteration**

Certain steps can be repeated a certain number of times, or until a certain condition is met.

```
Eating a Sandwich
1. Open mouth
2. Insert sandwich in mouth
3. Bite
4. Chew
5. Repeat all steps until sandwich is done
```

Not all algorithms are the same, even if they are accomplishing the same task.  Some may be more _efficient_ than others.  

Imagine that we want to search for a particular item in a list.  Here are two algorithms for searching:

```
Linear Search
1. Check item
2. Item is what you require:
     Stop
3. Otherwise:
     Move to next item, go back to #1
```

```
Binary Search
1. Sort Data
2. Locate middle item
3. Item is what you require:
     Stop
4. Required item is LESS THAN middle item:
     Remove upper half, go back to #2
5. Required item is GREATER THAN middle item:
     Remove lower half, go back to #2
```

Both searches will eventually find what you're looking for (if it exists).  But which one is more efficient? Are there different situations where one may be better than the other?

# In Class Task:

In small groups, come up with an algorithm to solve the problem below.  Near the end of the period other groups will look at your algorithm, and discuss whether it works and if it could be more efficient.

**Problem:** You have 12 people, 11 of which are equal weight and one that is different (could be less or more).  Using _only_ a see-saw, determine which individual weighs differently than the rest.

There are many ways to get the desired result, but try to make your algorithm as _efficient_ as possible.