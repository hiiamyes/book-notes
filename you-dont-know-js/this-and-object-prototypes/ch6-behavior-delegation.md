# Chapter 1. Behavior Delegation

Let's now dig into how we could and should be thinking about the object [[Prototype]] mechanism in JS, in a much simpler and more straightforward way than the confusion of classes.

Prototype chain: If the object can't fulfill the lookup, it's [[Prototype]] is followed, and so on.

This single observation is fundamental and critical for the motivation of behavior delegation: It's all about objects being linked to other objects.

## Toward Delegation-Oriented Design


