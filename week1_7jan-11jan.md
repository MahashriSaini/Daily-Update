## 7 Jan 2026
### Basics of JavaScript

1. Dynamically typed programming language

2. Data types
   - **Primitive (immutable values)**
     - Number(Infinte, NaN)
     - String
     - Boolean
     - Null
     - Undefined
     - Symbol
     - BigInt
   - **Non-primitive (call by reference, variables store reference to location of memory)**
     - Object
     - Arrays
     - Functions

3. Variable declaration types
   - **const**
     - Cannot be redeclared
     - Cannot be reassigned
   - **let**
     - Cannot be redeclared
     - Can be reassigned
   - **var**
     - Can be redeclared
     - Can be reassigned

4. String methods
   - `slice()`
   - `indexOf()`
   - `includes()`
   - `concat()`
   - `charCodeAt()`
   - `fromCharCode()`
   - `toUpperCase()`
   - `toLowerCase()`
   - `replace()`
   - `replaceAll()`
   - `repeat()`
   - `trim()`
   - `trimStart()`
   - `trimEnd()`
5. template literals(` `` `)
   - for string interpolation(${---})
   - for embedding javascript code
   - for newline and space or other special symbols without \n or\. simply im whichever way it is written inside template literal that way it will be logged.
6. Operators
  - **a. unary**
    - +, -, ++, --, !, ~, void(), typeof, Bitwise(>>, <<, &, |, ^)
  - **b. binary** 
    - Arithmetic(+, -, *, /, %), Conditions(>,<,>=,<=, &&, ||, ??), Equality(==, ===, +=, -=, /=), Inequality(!=, !==), operator precedence and operator association
  - **c. ternary**
    - `condition ? true statement : false statement`
7. Semicolon(;) - Automatically it is applied at end of each line but it is good to use.
8.  Single line comment(//), Multi-line comment(/*__________*/)



## 8 Jan 2026
### Basics of JavaScript
1. Math Object
  - Math.random()
  - Math.min(), Math.max()
  - Math.floor(), Math.ceil(), Math.round()
  - Math.trunc()
  - Math.sqrt(), Math.cbrt(), Math.pow()
  - Math.abs()
2. NaN (Not a Number)
  - property of global object
  - for those which should return a number but cannot return a number
3. Functions
  - named functions
  - anonymous functions
  - arrow functions
  - parameter VS arguments
  - default parameter
  - ` a function will always return something, by default it is "undefined" `
4. Arrays
  - push(), pop(), shift(), unshift()
  - destructuring (...), spread operator
  - reverse(), join(), indexOf(), splice(), includes()
5. Global Scope, Local Scope and Block Scope 
6. Shallow Copy
  - upper layer is copy, inner layer have same references

### Leetcode Problem
1. https://leetcode.com/problems/contains-duplicate/description/

### Open Source Contribution
  - added name in contributors list
  - repo link - https://github.com/firstcontributions/first-contributions?tab=readme-ov-file
1. forking repository - copying another repository on your github account as your repository
2. cloning the forked repository - copy the repository code on your local device
  - command used = git clone HTTPS/SSH link 
3. create branch - a branch where you can make the changes, 
  - command used - git switch -c branch_name 
4. make changes, save, commit
  - git add filename
  - git commit -m "commit_message"
5. push the changes to Github
  - git push -u origin branch_name
6. after pushing all changes to github, click on "Compare and Pull Request" so that owner of repository can check your changes.
7. once the owner of repo has merged your PR
  - sync + cleaning



## 9 Jan 2026
### Basics of JavaScript
1. Object (collection of key value pairs separated by commas)
   - accessing properties of object
      - Dot notation
      - Bracket notation ( helpful when property name is out of naming rules)
   - remove properties from object
      - delete operator
      - destructuring with rest parameters
   - checking existence of property
      - hasOwnProperty()
      - in operator
      - checking against undefined
   - optional chaining operator(?.) -safely access object properties or call methods without worrying whether they exist
   - destructuring object

2. Object Methods VS Functions
   - Object methods are functions defined as properties to object whereas Functions are globaly defined
   - called using dot notation of object
   - reference other properties using this keyword

3. Object() Constructor
   - new Object() - an empty new object is created
   - Object(num) = wrapper around primitiva data type

4. JSON ( JavaScript Object Notation)
   - light weight text based data format used for exchanging data between a server and a web application
   - machine parseable and human parseable
   - language independent ( java app can send to python app)
   - key-value pairs seaparated by commas
   - dot notation for access
   - JSON.parse() = convert JSON string to object
   - JSON.stringify() = JSON object to JSON string

5. Loops
   - for
   - for in
   - for of
   - while
   - do while


### Leetcode Problem 
   - https://leetcode.com/problems/smallest-subtree-with-all-the-deepest-nodes/description/?envType=daily-question&envId=2026-01-09


### Codeforces Problem
   - https://codeforces.com/problemset/problem/2169/A

### Open Source Contribution
   - repo link = https://github.com/Roshanjossey/code-contributions



## 10 Jan 2026
### Basics of JavaScript
1. Callbacks
   - function passed as argument to another function
   - event driven and not step driven
   - eg. callback function in forEach loop, all higher order functions
   - parameters of callback function - current element, index of current, array on which forEach is called
2. Higher Order Functions 
   - takes one or more function as argument + return one or more same or different function 
   - advantage - abstract complex functions
   - using same function structure with different behaviours
   - function factories - create other function
   - Examples
      - map
         - create new arrays by applying some function on original array
      -  filter
         - make new from original array but only selected elements are part of new array depending on condition
      - reduce
         -condenses array into single value after performing some process on each array
      - sort
         - callback is comparator function, inplace sorting
      - method chaining 
         - calling several functions one after another
3. DOM (Document Object Model)
   - accessing DOM nodes/ elements using DOM APIs
      - getElementById()
      - querySelector()
      - querySelectorAll()
      - innerText()
      - textContent()
      - innerHTML()
   - manipulating DOM nodes/ elements
      - createElement()
      - appendChild()
      - removeChild()
      - getAttribute()
      - setAttribute()
      - setTimeout()
      - setInterval()
      - clearTimeout()
      - requestAnimationFrame()
      - Web animations APIs
   - interfaces
      - window =represents the browser window that contains the DOM document. It provides methods and properties for interacting with the browser window, such as resizing the window, opening new windows, and navigating to different URLs
      - document = represents the DOM document that is displayed in the browser window. It provides methods and properties for interacting with the DOM, such as selecting elements, creating new elements, and modifying the content of element
      - Navigator - information about browser environment
   - Event Object
      - payload that triggers when user interacts with webpage
      - some properties = type, target, methods of event
      - some events = click, hovering, scrollup, mouseover, DOMContentLoaded 
      - adding and removing event listeners
      - EventListener interface
      - inline event handling
4. every() , some()


### Leetcode Question
   - https://leetcode.com/problems/minimum-ascii-delete-sum-for-two-strings/?envType=daily-question&envId=2026-01-10



## 11 Jan 2026
### js questions
1. https://leetcode.com/problems/array-prototype-last/description/?envType=study-plan-v2&envId=30-days-of-javascript
2. https://leetcode.com/problems/chunk-array/description/?envType=study-plan-v2&envId=30-days-of-javascript
3. https://leetcode.com/problems/is-object-empty/?envType=study-plan-v2&envId=30-days-of-javascript
4. https://leetcode.com/problems/memoize/description/?envType=study-plan-v2&envId=30-days-of-javascript
5. https://leetcode.com/problems/allow-one-function-call/description/?envType=study-plan-v2&envId=30-days-of-javascript

### leetcode question
   - https://leetcode.com/problems/maximal-rectangle/description/?envType=daily-question&envId=2026-01-11

### Project: Todo App
1. basic structure of app
2. functionality to add and remove tasks


## Questions
1. What is difference between a Function, Method and Operator?
2. What will happen if you try arithmetic operators on strings?
3. What are Truthy Values? What are Falsy Values?
4. What is git? What is github?
5. What is docker?
6. What is difference between HTTPS link and SSH link available at github for cloning?
7. What steps are taken once the PR is merged by the owner of PR?
8. Explore JSON object
9. javascript - more on shallow copy, more on spread operator
10. single threaded, multi threaded programming language
11. declarative Vs imperative language
12. closure?
13. if outer function is called with same input will the value of variables declared in outer funcn persist?
14. promises, time asynchronouns stuff, 
15. see all the problems solved in javaScript and check what is new why happening?
16. explore usage of callbacks, try to solve callback problems without callback
17. explore higher order functions, take some projects or questions on this...is there any you get same output with other approach
18. browser APIs, third party APIs
