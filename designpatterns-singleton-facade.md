# Design Patterns

^A design pattern is a way to solve a code problem in a way that is recognizable and reusable. It gives us common language with which to discuss code techniques.

---

# Objectives
- Explain what the Singleton pattern is
- Explain two reasons to use this pattern
- Review two ways to use the Singleton pattern
- Explain what the Facade pattern is
- Explain two reasons to use this pattern

---

#[fit] The Singleton Pattern
## Make One

---

# Singleton: What is it?

- A Singleton is a pattern to use when you only want one instance of an object to be created.

---

# Singleton: Why use it?

- Don't waste resources
- Stay organized with name-spacing (aka module design pattern)

^may be used for handling database connection or http requests

---

# Singleton: Example Code #1

```javascript
var MySingleton = {
  name: "Teddi",
  speak: function(){
    console.log("Hello");
  }
}

```

---

# Singleton: Example Code #2

```javascript
var MySingleton = (function(){
  var privateValue = "secret";
  return {
    name: "Teddi",
    speak: function(){
      console.log("Hello");
    }
  }
})();

```
^ Does this look familiar? It looks like the module that we created yesterday which was also a Singleton.

---

#[fit] The Facade Pattern
## Build an Interface

---

# Facade: What is it?

- A facade is an object that provides a simplified interface to a larger body of code, such as a class library.
-- Wikipedia

---

# Facade: Why use it?

- Only exposes what is necessary
- Can make the underlying functionality easier to consume
- Can be used to hide confusing or messy code
- Can be used to unify several sub-systems


---

# Facade: How to implement it:

- Create a function that will act as your facade.
- Access the original functions from inside of your facade.
- Create a new API that does what you need it to do.
- The end result is that you have a simpler interface.

^ Example - jQuery
Example - legacy code with lots of different components, you create an interface on top of that. Whiteboard pic.

---

# Questions?
