1. Describe the biggest difference between `.forEach` & `.map`. 
forEach() — executes a provided function once for each array element.
map() — creates a new array with the results of calling a provided function on every element in the calling array.
The biggest difference between .forEach and .map is that map returns a new array of elements while in turn passing each element back to the callback.

2. What is the difference between a function and a method?
The one I see most often is that a method is a function that’s inside an object. It's semantics and has to do with what you are trying to express.
'method' is the object-oriented word for 'function'. That's pretty much all there is to it (ie., no real difference).

3. What is closure?
A closure is a feature in JavaScript where an inner function has access to the outer (enclosing) function's variables 

4. Describe the four rules of the 'this' keyword.
* 1. Window/Global Object Binding: This is all about the where "this" will be called.It is defult to window object.
* 2. Implicit Binding: It will be call the object befor the dot.
* 3. New binding: Creat new object.
* 4. Explicit binding: When we apply method to using this it will be Explicit binding.

5. Why do we need super() in an extended class?
 IF you’re going to use extends, super() needs to be called from within the constructor function. This is to pass any new attributes back up to the constructor of the parent object.
 + super() is used to tell a parent’s constructor to be concerned with the child’s attributes vis versa