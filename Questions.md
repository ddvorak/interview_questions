### Soft Skills
* How do you keep up with the latest tech
* Do you have any preferred JavaScript libraries or frameworks (don’t list more than three). For one of the  libraries/frameworks, please briefly state how you used it to solve a problem.  
* [Soft Questions to Ask Interviewer](https://gist.github.com/vcarl/14275c72baf976ff1665392e14225dcc)

### Protocol Questions
* When you type google.com into the browser what happens, go into as much detail as possible

### Backend/API design and Understanding
* What is REST
* Socket vs http requests


### Debugging
* There is a button on the page, when you click it the page is non-responsive and the pinwheel starts spinning, how do you go about debugging this
* How would you go about debugging a program that crashes at different lines of code each time it’s run.

### HTML Questions
* When would you (a) not put CSS <link> between <head></head>,  and (b) JavaScript <script></script> just before </body>?
* How do you go about optimizing a webpage?
* Write the HTML5 doctype. What is it used for?
* Categorize div, span, p, h1, and section as inline or block HTML elements.
* What is a new input element type included in HTML5?


### CSS
* What is the css box model
* Explain the stacking context?
* Explain the difference between flex and grid display
* Given three buttons, how can you increase the click area of the buttons without changing the buttons’ size or the space between the buttons?
* Given the following HTML, how do you select all of the `<li>` elements using CSS? How do you select all `<li>` elements except the ones inside of the `<ul>`?
```html
<div>
   <ol>
    <li></li>
    <li></li>
    <li>
     <ul>
        <li></li>
        <li></li>
        <li></li>
     </ul>
   </li>
  <ol>
</div>
```
* How is the following CSS selector interpreted by the browser?   
```css
div p span {  }
```

* What are all of the potential values of the CSS property display?

* Which CSS selector takes precedence, given a div with an ID of foo?
```css
#foo { }
div[id=’foo’] div { }
```
* Using only css (and not css3 aka no flexbox) create a horizontally and vertically centered red circle with dimensions 100x100 with a grey 10px border - should be dynamically centered so resizing the window will keep it centered. Part 2 - On hover, the circle should split in half and have a white divider down the middle

* Rewrite this single CSS property as two shorter CSS properties.
```css
div {
  margin: 3px 7px 3px 4px;
}
```

### Database
* Whats the difference between a relational db like sql and non-relational db like mongo
* Would you ever want to index a database ? (something along those lines )

### Javascript Fundamentals
* What is a closure and how does it relate to side effects
* What is prototypal inheritance vs classical inheritance
* Explain scope in javascript
* What's the difference between a function expression and function declaration
* What is the event loop
* What are promises?
* When would you consider using JavaScript prototypes?

### Node Related
* How do I use es6 syntax in Node?

### Testing
* What are unit tests
* Whats the difference between unit tests and continuous integration tests

### Javascript Quirks
* What is the output of the following expressions?
```javascript
   True == 1
   False === 0
   1 + ‘1’
   1 + 1 + ‘1’ + ‘1’
   True + 1
   False - 1
```

* Using code, please demonstrate an asynchronous call in JavaScript?

* In ES2015 (aka ES6) we have Modules. What options do you have if you wanted similar functionality in ES5.

* Please describe the complexity of the following jQuery expression:
```javascript
   $("#insPolicy").hide();
   $("#insForms").show();
   $("#btnForms").addClass("active").attr("data-dirty", true);
   $("#btnPolicy").removeClass("active").attr("data-dirty", false);
```
* What happens when this code is run? What appears in the console and in what order? How can we make every console.log be a number?
```javascript
function Foo() {
  this.value = 42;
  this.method = function() {
    console.log(this.value)
  }
  setTimeout(this.method, 500);
}

const foo = new Foo();
foo.method();
const bar = foo.method;
bar();
```

### Angular
* What is the difference between $rootscope and $scope in Angular?

### Frontend Programming Question
* Given an API endpoint and JSON data schema, use vanilla JS or whatever framework desired to create a search bar that automatically provides suggestions fetched from the API as a dropdown when the user types. If the user selects a suggestion from the dropdown, the dropdown should close and the text should appear in the search bar.
* Show me how you would turn your resume into a static website using HTML and CSS.
* Given 2 identical DOM trees (not same trees) and one element of the first DOM tree, how would you find this element in the second DOM tree?
* Write an Emitter class. Support Subscribing to events. Support Emitting events. Support Unsubscribing from events.
* Implement a simple observable
* Design/code a poll widget
* Given a picture, how would you hide/show a child picture on hovering on this parent? How would you ensure clicking on this picture would go to a specific link? How would you ensure the child is positioned in the top right of the parent picture?

# Basic Program Design
* You have an excel file you are parsing in node that is 3000 lines and a method that you have to run on every line. The method can not be optimized any further. It runs synchronously. How can you optimize this?

### System Architecture Questions
* What are the pros and cons to a microservice architecture?
* Explain how you would go about creating a url shortening service like bit.ly.

### Programming Paradigms
* Please describe functional programming in JavaScript and when you might consider using it?

### Computer Science
* Explain what a stack is and what it is used for.
* Merge Sort
* Depth First Traversal of BST
* Given a LinkedList with four nodes, how would you remove the third node? How would you remove the head node?
* Given a BST, print all paths from root node to leaves (common fb question)

### LEETCODE Questions

* Given five candles, each candle yields one residue when it completes burning. For every two residues, we can create a new candle. Write a function that returns the greatest number of candles we can burn if we reuse the residue.

* Write a function that takes in an input array [1, 2, 3, 4, 5] and returns an output array [1, 2, 3, 4, 5, 5, 4, 3, 2, 1]. What is the big O notation of your solution?

* Write a function that takes in an input array [1, 3, 3, 4, 5, 1, 6, 1] and returns an output array [4, 5, 6]. What is the big O notation of your solution?

* Return the first duplicate of an array of integers

* You have a shit computer with 64 kb of RAM. Given a huge data set of unsorted integers (think millions) how would you sort these with the memory constraints in mind. (You can only read in a certain amount of data at one time, but are not limited to the number of actual files you create/read/write to on disk)

* Flatten Array iteratively/recursively (DEEPLY NOT SHALLOW)

* Translate an inputted number to its alphabetical value

* Given an array of buildings that have height, and an x start and endpoint, write a function that outputs an array of (x,y) coordinates representing vertices of the sillohouette of the buildings. (leetcode hard)






