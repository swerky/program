# POCO - WEEK 5
JavaScript


<br>

---

<br>

## Day 1

### Course
1. Week 4 Recap + info about new ressouces
2. Loops
3. Conditions
4. Todo App workshop - Versions 3 to 5


### Suggested Exercises
* **W3Schools - JavaScript Exercises:** (if not done last week)<br>
    https://www.w3schools.com/js/exercise_js.asp

    * JS Objects
    * JS Booleans
    * JS Conditions
    * ~~JS Loops~~


### Day 1 ressources
 > [MDN - Loops and iteration](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration)<br>
 [w3schools.com - if/else Statement](https://www.w3schools.com/jsref/jsref_if.asp)<br>


<br>

---

<br>

## Day 2

### Course
1. Day 1 Recap
2. JS Booleans suite (the "bang" operator "!")
3. Loops
4. Todo App workshop - Versions 4 and 5


### Suggested Exercises
#### Add a toggleAll() method to your todoList object (todo-app v6)
For this exercise, create a new folder *"v6-toggleAll"* inside your *"app-versions"* folder.

Remember, all list items have a "completed" key who can be true or false.<br>
When using this method you have to have this behavior :
1. If **all items** have "completed" key value set to **false** :<br>
   Asign **true** to all

2. If **all items** have "completed" key value set to **true** :<br>
   Asign **false** to all

3. If **at least one item** have "completed" key value set to **true** :<br>
   Asign **true** to all

> Note: It's not simple to see the solution. Here's are some tips:<br>
> 1. First, you have to loop into your list and check if you have items set to "true".<br>
  Tip: Find a way to increment a number each time you find a "true" item (you can store this value into a variable **var counter** or similar)
> 2. Second, you have to loop into your list **2 more times** to asign true or false to all items dependig on what value "counter" have:<br>
If *counter == 0*   → all items to "true"<br>
If *counter > 0* → all items to "true"<br>
If *counter == todos.length* (means all items are checked) → all items to "false"

> If you are (completly) stuck, look into "app-versions-curriculum/v6" to see the solution


### Day 2 ressources
 > [MDN - Loops and iteration](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration)<br>
 [w3schools.com - if/else Statement](https://www.w3schools.com/jsref/jsref_if.asp)<br>


<br>

---

<br>

## Day 3
Social & Business skills


<br>

---

<br>

## Day 4

### Course
1. Day 2 Recap
2. "Thinking code", how **toggleAll()** method works
3. HTML & the DOM
4. Todo App workshop - Versions 7 to 8


### Suggested Exercises
* **Make mobile menu work for your website**<br>
Use your new "DOM" knowledge to add a class *"menu-is-open"* to your `<body>` tag when clicking on a hamburger icon/link

* **Play with the DOM**<br>
Use your "DOM" knowledge to :
    * Add HTML elements with JavaScript
    * Add HTML elements attributes with JavaScript
    * Add a class to a specific HTML element when clicking a button
    * When scrolling, detect scroll distance from the top of the window and display the value inside an HTML element


### Day 4 references / links
 > [MDN - Introduction to the DOM](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction)
 
 > Get DOM elements<br>
 [MDN - document.getElementById()](https://developer.mozilla.org/en-US/docs/Web/API/Document/getElementById)<br>
 [MDN - document.query​Selector()](https://developer.mozilla.org/en-US/docs/Web/API/Document/querySelector)<br>
 [MDN - document.query​SelectorAll()](https://developer.mozilla.org/en-US/docs/Web/API/Document/querySelectorAll)

 > Events<br> 
 [MDN - Events and the DOM](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Events)<br>
 [MDN - Event reference](https://developer.mozilla.org/en-US/docs/Web/Events)<br>
 [MDN - Event​Target​.add​Event​Listener()](https://developer.mozilla.org/en-US/docs/Web/API/EventTarget/addEventListener)

 > Manipulate HTML attributes<br>
 [MDN - Element​.class​List](https://developer.mozilla.org/en-US/docs/Web/API/Element/classList)<br>
 [MDN - Element​.set​Attribute()](https://developer.mozilla.org/en-US/docs/Web/API/Element/setAttribute)


 

<br>

---

<br>

## Day 5

### Course
1. Day 4 Recap
2. HTML & the DOM
3. Todo App workshop - Versions 8 to 9

### Suggested Exercises
Continue to work on day 4 exercises

### Day 5 references / links
IDEM day 4