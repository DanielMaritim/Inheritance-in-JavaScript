# Inheritance-in-JavaScript
Lets discuss abit about inheritance in ES6,what it entails and its importance

Inheritance is when one class acquires the properties of another class.A child aquires the traits of its parent.

Inheritance refers to an object's ability to access methods and other properties from another object.

Objects can inherit from other objects and it works through prototypes.

In ES6 inheritance is allowed from one class to another,and that class can add more features of its own.
one class can be like a parent class while the other becomes the child class.

We will be discussing more about 'super' and 'extends'

The 'extends' is used to inherit from another class and the 'super' keyword is used to call the parent class which has the features.

The 'extends' keyword is used to create a child class of another class ie the parent.The child will inherit/get all the methods fro the parent class.

This help in code reusability and avoids duplication


The 'super' keyword is used to call methods of the parent class It is used within a cinstructor function to call the parent constructor function

Under the hood, your classes are being converted into Prototypal Inheritance models

when one wants to create a number of objects that have similar features, creating a generic object type to contain all the shared functionality and inheriting features in more specialized object types can be convenient and useful even though it looks complex,it might be of help

keep the number of inheritance at a minimum so as to keep track of your methods and properties
