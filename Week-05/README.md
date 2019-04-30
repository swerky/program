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
#### Add a toggleAll() method to your todoList object
Remember, all list items have a "completed" key who can be true or false.<br>
When using this method you have to have this behavior :
1. If **all items** have "completed" key value set to **false** :<br>
   Asign "true" to this key for all items

2. If **all items** have "completed" key value set to **true** :<br>
   Asign "false" to this key for all items

3. If **at least one item** have "completed" key value set to **true** :<br>
   Asign **true** to this key **for all items**

> Note: It's not simple to see the solution. Here's are some tips:<br>
> 1. First, you have to loop into your list and check if you have items set to "true".<br>
  Tip: Find a way to increment a number each time you find a "true" item (you can store this value into a variable **var counter** or similar)
> 2. Second, you have to loop into your list **2 more times** to asign true or false to all items dependig on what value "counter" have:<br>
If *counter == 0*   → all items to "true"<br>
If *counter > 0* → all items to "true"<br>
If *counter == todos.length* (means all items are checked) → all items to "false"

> If you are (completly) stuck, look into "app-versions-curriculum/v6" to see the solution



### Day 1 ressources
 > [MDN - Loops and iteration](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration)<br>
 [w3schools.com - if/else Statement](https://www.w3schools.com/jsref/jsref_if.asp)<br>