Assignment Questions:

1. Difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?

Ans: getElementById: Finds and returns a single element by its unique id.
     getElementsByClassName: Returns a live HTMLCollection of all elements that share the same class name.
     querySelector: Uses CSS selectors and returns the first matching element.
     querySelectorAll: Returns a static NodeList of all elements that match the selector.


2. How do you create and insert a new element into the DOM?
Ans: Firstly create an element using document.createElement("div"). Then, insert it into the DOM using methods like appendChild() or insertBefore().
Example:
 let newDiv = document.createElement("div");
 newDiv.innerText = "Hello World!";
 document.body.appendChild(newDiv);


3. What is Event Bubbling and how does it work?
 Ans:Event bubbling means when an event happens on a child element, it propagates upward to   its parent, then ancestors, up to the document.
 

4. What is Event Delegation in JavaScript? Why is it useful?
Ans: Event delegation means adding an event listener to a parent element, so when a child element triggers the event, it is caught by the parent and it is useful because it reduces the need to attach separate event listeners to multiple child elements, making the code more efficient.


5. Difference between preventDefault() and stopPropagation()?
 Ans: preventDefault() : Prevents the default action of an element (e.g., stopping a form from submitting, stopping a link from redirecting).

  stopPropagation() : Stops the event from propagating (bubbling) to parent elements.