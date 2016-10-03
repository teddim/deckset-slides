# Design Patterns

---

#[fit] The Classic Module Pattern
##[fit] Keep your code clean and organized

---

#Objectives
- Explain what the Module pattern is
- Explain two reasons to use this pattern
- Review and examine some code using the Module pattern

---

# What is it?

- It is essentially a function that gets executed immediately
- The function returns an object literal with methods available for use immediately
- The methods in this returned object have access to a private scope

---

# Why use it?

- Maintainability
- Reusability

^ So you only have to edit it in one place and you can reuse it in multiple projects.

---

# How to use it:

-  Assign the return value of a function to a named variable
-  Inside of the function, return the values that you want to be publicly accessible
- Anything that is not in the returned object will not be available

---

#Example code

```javascript
var myModule = function(){ // assign a function to a variable
  //hidden values
  var hiddenVal = { name: "Teddi"};
  var hiddenCounter = 0;

  //public api
  var publicApi = {
    visibleVal: function(){
      console.log(hiddenVal.name);
    },
    click: function(){
      return hiddenCounter++;
    }
  };

  return publicApi; // the return object is publicApi
}(); //this function is immediately invoked so the public API is available for use

myModule.visibleVal(); //visibleVal is a method available
console.log(myModule.hiddenVal); //hiddenVal is not accessible
```

---

#Let's explore this code

---


#Questions?

---

#Code we looked at in jsbin

```javascript
var myModule = function(){ // assign a function to a variable
  //hidden values
  hiddenVal = { name: "Teddi"};
  var hiddenCounter = 0;

  //public api
  var publicApi = {
    visibleVal: function(){
      console.log(hiddenVal.name);
    },
    click: function(){
      console.log(hiddenCounter);
      return hiddenCounter++;
    }
  };

  return publicApi; // the return object is publicApi
}(); //this function is immediately invoked so the public API is available for use

// console.log(myModule);
// myModule.visibleVal(); //visibleVal is a method available
// console.log(myModule.hiddenVal); //hiddenVal is not accessible

// myModule.click();
// myModule.click();
// myModule.click();
// myModule.click();
```
