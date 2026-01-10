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




### Questions
1. What is difference between a Function, Method and Operator?
2. What will happen if you try arithmetic operators on strings?
3. What are Truthy Values? What are Falsy Values?
4. What is git? What is github?
5. What is docker?
6. What is difference between HTTPS link and SSH link available at github for cloning?
7. What steps are taken once the PR is merged by the owner of PR?
8. Explore JSON object
9. javascript - more on shallow copy, more on spread operator
