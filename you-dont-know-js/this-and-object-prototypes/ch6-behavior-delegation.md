# Chapter 6. Behavior Delegation

Let's now dig into how we could and should be thinking about the object [[Prototype]] mechanism in JS, in a much simpler and more straightforward way than the confusion of classes.

Prototype chain: If the object can't fulfill the lookup, it's [[Prototype]] is followed, and so on.

This single observation is fundamental and critical for the motivation of behavior delegation: It's all about objects being linked to other objects.

## Toward Delegation-Oriented Design

### Class Theory

### Delegation Theory

OLOO, objects linked to other objects, a foundamental difference design pattern from classes.

- In general, with [[Prototype]] delegation, we want state to be on the delegators, not on the delegate.
- Avoid if at all possible naming things the same at different levels of the [[Prototype]] chain.
- The general utility methods that exist on delegate are available to delegator, because delegator can delegate to delegate.

#### Mutual Delegation (disallowed)

#### Debugged

Chrome's specific internal constructor name tracking is really only useful if you're fully embracing class-style coding, but is moot if you're instead embracing OLOO delegation.

### Mental Models Compared

---

## Classes Versus Objects
