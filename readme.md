### 6. 

1. What is the difference between **getElementById, getElementsByClassName, and querySelector / querySelectorAll**?
Ans: 
getElementById can get only one of the unique specfic id from whole html document.
By using getElementsByClassName we can get all matched element from the html.
querySelectorAll can get all specfic tag, class and id's but querySelector get only the first



2. How do you **create and insert a new element into the DOM**?
Ans:
// Create a new element
const element = document.createElement("div");

// Insert into the DOM
document.body.appendChild(element);




3. What is **Event Bubbling** and how does it work?
Ans:
Event Bubbling is when an event on a child element propagates upward to its parent elements in the DOM hierarchy, triggering their event handlers.



4. What is **Event Delegation** in JavaScript? Why is it useful?
Ans:
Event Delegation is a technique where you attach a single event listener to a parent element to handle events on its child elements.

Usefulness:

Reduces memory usage by avoiding multiple listeners.

Works for dynamically added elements.


5. What is the difference between **preventDefault() and stopPropagation()** methods?
Ans:
preventDefault() prevents default behaviour. 
on the other side
stopPropagation() prevents an event from bubbling up (or capturing down) the DOM, so parent elements won’t be triggered by that event.