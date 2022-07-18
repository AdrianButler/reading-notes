# Reading 6

## Javascript

- How would you describe an object to a non-technical friend you grew up with?
  - an object is a storage container than has labels on everything inside it and specials things it can do to all those objects
- What are some advantages to creating object literals?
  - Easy access to variables that are labeled with what they are
- How do objects differ from arrays?
  - Array values are not labeled and can not have special functions attached to them
- Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.
  - When the dot identifier is not available (number names)
- Evaluate the code below. What does the term this refer to and what is the advantage to using this?

>const dog = {  
name: 'Spot',  
age: 2,  
color: 'white with black spots',  
humanAge: function (){  
console.log(`${this.name} is ${this.age*7} in human years`);  
    }  
}

- this refers to the object that is currently being called

- What is the DOM?
  - data representation of html
- Briefly describe the relationship between the DOM and JavaScript.
  - Javascript reads the dom and manipulates it

