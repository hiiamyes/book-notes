# Chapter 5. Prototypes

## [[Prototype]]

**Object.prototype**

**Setting and Shadowing Properties**

## "Class"

## (Prototypal) Inheritance

incorrect

```
Bar.prototype = Foo.prototype
Bar.prototype = new Foo()
```

correct, pre-ES6

```
Bar.prototype = Object.create(Foo.prototype)
```

correct, ES6

```
Object.setPrototypeOf(Bar.prototype, Foo.prototype)
```

**Insepecting "Class" Relationships**

## Object Links

## Review


