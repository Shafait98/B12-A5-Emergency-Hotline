

### 6. Answer the following questions clearly:

1. What is the difference between **getElementById, getElementsByClassName, and querySelector / querySelectorAll**?
Ans: getElementById("id") → Selects one element by unique ID.

getElementsByClassName("class") → Selects all elements with that class (HTMLCollection).

querySelector("selector") → Selects the first element matching a CSS selector.

querySelectorAll("selector") → Selects all elements matching a CSS selector (NodeList).

2. How do you **create and insert a new element into the DOM**?
Ans: document.createElement("tag") → Creates a new element.

element.textContent = "..." / element.className = "..." → Add content or attributes.

parent.appendChild(element) → Insert at the end of a parent.

parent.prepend(element) → Insert at the beginning.

reference.before(element) / reference.after(element) → Insert relative to another element.

3. What is **Event Bubbling** and how does it work?
Ans: Event Bubbling means when you click on a child element, the event first happens on that element, then automatically “bubbles up” to its parent, then the parent’s parent, and so on until it reaches the root (document).

4. What is **Event Delegation** in JavaScript? Why is it useful?
Ans: Event Delegation = Instead of adding event listeners to many child elements, you attach one listener to their parent and let event bubbling handle the rest.

5. What is the difference between **preventDefault() and stopPropagation()** methods?
Ans: preventDefault() → Stops the default action of an element (e.g., a link navigating, a form submitting).

stopPropagation() → Stops the event from bubbling up to parent elements.

---

