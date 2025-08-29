1. What is the difference between **getElementById, getElementsByClassName, and querySelector / querySelectorAll**?<br>
Ans: <br>
getElementById can get only one of the unique specfic id from whole html document.<br>
By using getElementsByClassName we can get all matched element from the html.<br>
querySelectorAll can get all specfic tag, class and id's but querySelector get only the first<br>
<br><br><br>


2. How do you **create and insert a new element into the DOM**?<br>
Ans:<br>
// Create a new element<br>
const element = document.createElement("div");<br>
<br>
// Insert into the DOM<br>
document.body.appendChild(element);
<br><br><br>



3. What is **Event Bubbling** and how does it work?<br>
Ans:<br>
Event Bubbling is when an event on a child element propagates upward to its parent elements in the DOM hierarchy, triggering their event handlers.

<br><br><br>

4. What is **Event Delegation** in JavaScript? Why is it useful?<br>
Ans:<br>
Event Delegation is a technique where you attach a single event listener to a parent element to handle events on its child elements.
<br><br>
Usefulness:<br>

Reduces memory usage by avoiding multiple listeners.<br>
Works for dynamically added elements.<br>



<br><br><br>
5. What is the difference between **preventDefault() and stopPropagation()** methods?<br>
Ans:<br>
preventDefault() prevents default behaviour. <br>
on the other side<br>
stopPropagation() prevents an event from bubbling up (or capturing down) the DOM, so parent elements won’t be triggered by that event.