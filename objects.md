# Objects
## How do we make them?

---

# Objectives
- Explain several ways to  create an Object
- Explain what happens when the New keyword is used
- Explain the Prototype Chain

---

# Creating an Object
- Object Literal `{}`
- `Object.create()`
- `new Object()`

---

# Object Literal

```javascript
var Person = {
  name:"Teddi",
  reverse: function(){
    return this.name.split('').reverse().join('');
  }
}
```

---

# Object Create

```javascript
var Person = {
  name:"Teddi",
  reverse: function(){
    return this.name.split('').reverse().join('');
  }
}

var personA = Object.create(Person);
```

---

# New Object
```javascript
function Person(name){
  this.name = name;
  this.reverse = function(){
    return this.name.split('').reverse().join('');
  }
}

var person1 = new Person('person1');
```

^new makes this a constructor call
a new object is created (it is empty!)
the object is linked to the one we specified
the object gets bound as the 'this' keyword
if there is no explicit return, it will implicitly return a new object

---

# New Object Prototype

```javascript
function Person(name){
  this.name = name;
}

Person.prototype.reverse = function(){
  return this.name.split('').reverse().join('');
}

var person1 = new Person('person1');

```

---

# The Prototype Chain
### whiteboard

---

# Let's Explore Some Code
