## Course Map
### Week Two

-----------------------------------------

### WORKBOOK!!!
* [Workbook](https://javascript-workbook.netlify.com/)

### Class Objectives

#### Day One: Class Objectives

* To gain a preliminary grasp of JavaScript definitions and of basic syntax.
* To utilize variables, logging, arrays, and if/else statements to create simple JavaScript applications.
* To understand the use and syntax of JavaScript's **for loops**.

#### Day Two: Class Objectives

* To use for loops, arrays, and conditional logic to create a rock-paper-scissors game.

#### Day Three: Class Objectives

* To gain an understanding of JavaScript Functions and Objects.
* To begin utilizing the basic JavaScript learned so far to build simple JavaScript games.



-----------------------------------------

### Week Two | Activities

#### Day One: Activities

* [01-CodeDissection](activities/day-1/01-CodeDissection)
* [02-BasicVariablesDemo](activities/day-1/02-BasicVariablesDemo)
* [03-PizzaVariables](activities/day-1/03-PizzaVariables)
* [04-ConsoleLogDemo](activities/day-1/04-ConsoleLogDemo)
* [05-PizzaConsole](activities/day-1/05-PizzaConsole)
* [06-PromptDemo](activities/day-1/06-PromptDemo)
* [07-PromptSushi](activities/day-1/07-PromptSushi)
* [08-ConditionalDemo](activities/day-1/08-ConditionalDemo)
* [09-ConditionalActivity](activities/day-1/09-ConditionalActivity)
* [10-ConditionalActivity2](activities/day-1/10-ConditionalActivity2)
* [11-ArraysDemo](activities/day-1/11-ArraysDemo)
* [12-ArraysActivity](activities/day-1/12-ArraysActivity)
* [13-Bands](activities/day-1/13-Bands)
* [14-JSDissect](activities/day-1/14-JSDissect)
* [15-CoolPeopleArray](activities/day-1/15-CoolPeopleArray)
* [16-ArraySetting](activities/day-1/16-ArraySetting)
* [17-MyFirstLoop](activities/day-1/17-MyFirstLoop)
* [18-ZooLoop](activities/day-1/18-ZooLoop)

#### Day Two: Activities

* [21-Events](activities/day-2/21-Events)
* [22-PseudoCode](activities/day-2/22-PseudoCode)
* [23-RPS-Coded](activities/day-2/23-RPS-Coded)
* [24-Recap](activities/day-2/24-Recap)
* [25-LoopTV](activities/day-2/25-LoopTV)
* [26-SuperheroLogging](activities/day-2/26-SuperheroLoggingp)
* [27-MyFirstFunctions](activities/day-2/27-MyFirstFunctions)

#### Day Three: Activities

* [28-GoodArray](activities/day-3/28-GoodArray)
* [29-JoanOfArcArrays](activities/day-3/29-JoanOfArcArrays)
* [30-GandalfTheGreyObjects](activities/day-3/30-GandalfTheGreyObjects)
* [31-MyFirstObject](activities/day-3/31-MyFirstObject)
* [32-CarGame](activities/day-3/32-CarGame)
* [33-Scope](activities/day-3/33-Scope)
* [34-QuestionGame](activities/day-3/34-QuestionGame)


-----------------------------------------

### Week Two | Video Walkthroughs
* [Homework #2 - My bootstrap themed portfolio!](https://youtu.be/C3cMAcsv1Lg)
* [Homework #2 - My responsive portfolio](https://youtu.be/jF0kIhpX6tk)
* [Lesson 3.2 - Rock, Paper, Scissors](https://youtu.be/Tio88WjwFO0)
* [Lesson 3.2 - Zoo Loop!](https://youtu.be/zJO9g7S2_Xo)

-----------------------------------------

### Week Two | Slide Deck

* Day 1: [Slide Deck](resources/slide-decks/day-1)
* Day 2: [Slide Deck](resources/slide-decks/day-2)
* Day 3: [Slide Deck](resources/slide-decks/day-3)
-----------------------------------------

### Week Two Homework

- Issued 11/5/2018 | **DUE 11/08/2018** | [Part 1](homework/part-1)
    * Create one of two possible computer games: Hangman or Psychic

-----------------------------------------

### Week Two | Helpful Links

* [Bootswatch](https://bootswatch.com)
* [DOM](https://css-tricks.com/dom/)
* [todomvc in jquery](http://todomvc.com/examples/jquery/#/all)
* [jQuery API](https://api.jquery.com/)

-----------------------------------------

### Week Two | Terminology

* **JavaScript**

> JavaScript is the third of the three fundamental programming languages of the modern web (along with HTML, CSS).

> JavaScript allows developers to create dynamic web applications capable of taking in user inputs, changing what’s displayed to users, animating elements, and much more.

Your javascript code, for now, will go on your HTML file, in the body, and between your script tags:

```
<body>
  <script type="text/javascript">
    <!-- JavaScript Magic -->
  </script>
</body>
```


* **Variables**

Variable Names:

All names start with a letter.

Avoid single letter names. Be descriptive with your naming.

Use camelCase when naming objects, functions, and instances.

Use PascalCase when naming constructors or classes
>Words created by concatenating capitalized words. An example is this page's title, PascalCase. Sometimes called "UpperCamelCase", or "DromedaryCase". Distinguished from CamelCase by the restriction that the first letter must be upper case. ("camelCase" isn't PascalCase, but "PascalCase" is.)

Always use var to declare variables. Not doing so will result in global variables. We want to avoid polluting the global namespace. Captain Planet warned us of that.

Use one `var` declaration per variable. It's easier to add new variable declarations this way, and you never have to worry about swapping out `a` ; for `a` , or introducing punctuation-only diffs.

Declare unassigned variables last. This is helpful when later on you might need to assign a variable depending on one of the previous assigned variables.

```

var variableName = value;

var variableName = "String";

var variableName = true;

var variableName = 42;

var variableName = [1,2,3];

```

> The syntax for creating a new variable and assigning it a value is as follows:
> * var + the variable names
> * = the equal sign (the assignment operator). The variable name should go left of the value to be assigned.
> * to the right of the = / equal sign (the assignment operator) we should place the value to be assigned. This can be Numbers, Strings, Boolean, Arrays, etc

> Variables are the nouns of programming.

> They are “things” (Numbers, Strings, Booleans, etc.).

> They are composed of variable names and values

>When you use "var" , you are instantiating a variable in the current scope. This will also prevent access of variables named the same in higher scope, within the current scope.

#### Data Types

* **Strings**

> String literals (denoted by double or single quotes) and strings returned from String calls in a non-constructor context (i.e., without using the new keyword) are primitive strings. JavaScript automatically converts primitives to String objects, so that it's possible to use String object methods for primitive strings.

```
var newString = "I am a new string";
```
or

```
"I am a lonely string not assigned to a variable"
'I am a string made with single quotes'
```


* **undefined**

A primitive value automatically assigned to variables that have just been declared or to formal arguments for which there are no actual arguments.

* **Numbers**

> JavaScript has only one type of number. Numbers can be written with, or without, decimals.

Incrementing Numbers

```
var i = 0;
i++ // increments the value by 1
//Same As:
i = i + 1;
i += 1

```

```
i-- // decrements the value by 1
//Same As:
i = i -1;
i -= 1;
```

* **Operators**

```
+ - * /
```

* **Booleans**

true

false

> A JavaScript Boolean represents one of two values: true or false.


* [Arrays](https://www.w3schools.com/js/js_arrays.asp)

> Arrays are a type of variable that are collections.

> JavaScript arrays are used to store multiple values in a single variable.

> These collections can be made up of strings, numbers, booleans, other arrays, objects, anything.

> Each element of the array is marked by an index.

> Indexes always start with 0.

> Index Values start at 0

> To access a value in an array state the name of the array and then access it's index with the [ ] syntax: example:

```
var myFarm = ["Apples", "Walnut", "Emu berry", "Star Fruit", "Olive Fruit","Macadamia","Elderberry Fruit "];

// to access the element at the first index (index 0):

var firstElement = myFarm[0]

```


* **Null**

In computer science, a null value represents a reference that points, generally intentionally, to a nonexistent or invalid object or address. The meaning of a null reference varies among language implementations.


-----------------------------------------

* [Conditionals](https://www.w3schools.com/js/js_if_else.asp)

> Each statement is composed of an if, else-if, or else (keyword), a condition, and the resulting code in { } curly brackets.

```

if (condition to be checked goes here) {
  /*If the condition is true this code gets executed*/
  /*This code is between the Curly Braces*/
}
```
* [Comparison and Logical Operators](https://www.w3schools.com/js/js_comparisons.asp)

```
==	equal to

===	equal value and equal type

!=	not equal

!==	not equal value or not equal type

>	greater than

<	less than

>=	greater than or equal to

<=	less than or equal to
```

```
Given that x = 6 and y = 3, the table below explains the logical operators:

&&	and	(x < 10 && y > 1) is true

||	or	(x == 5 || y == 5) is false

!	not	!(x == y) is true

```
* [For-Loops](https://www.w3schools.com/js/js_loop_for.asp)

Helps us 'DRY' (Don't Repeat Yourself) our code. We loop through each index of an Array:

```
var array = ["I","am", "an","array","with", "multiple","elements"];

for (i = 0; i < array.length; i++) {
    console.log(array[i]);
}
```

**Functions**
* [console.log()](https://developer.mozilla.org/en-US/docs/Web/API/Console/log)
* [alert()](https://www.w3schools.com/jsref/met_win_alert.asp)
* [prompt()](https://www.w3schools.com/jsref/met_win_prompt.asp)
* [confirm()](https://www.w3schools.com/jsref/met_win_confirm.asp)
* [document.write()](https://www.w3schools.com/jsref/met_doc_write.asp)
* [Math.random()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/random)
* [Math.floor()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/floor)

* [DOM Events](https://www.w3schools.com/jsref/dom_obj_event.asp)
* [Element.innerHTML](https://developer.mozilla.org/en-US/docs/Web/API/Element/innerHTML)
* [Document.querySelector()](https://developer.mozilla.org/en-US/docs/Web/API/Document/querySelector)

#### [CREATING FUNCTIONS](https://www.w3schools.com/js/js_functions.asp)

A JavaScript function is a block of code designed to perform a particular task.

A JavaScript function is executed when "something" invokes it (calls it).

The function is composed of two parts:
1. The function definition.
Arguments bind on function calls, and demonstrate that argument names are only visible inside of the function body.

2. The function call (or execution).

```

function myFunctionName(argument1, argument2) {
  /*code inside {} will be executed*/
}
```

When JavaScript reaches a return statement, the function will stop executing.

If the function was invoked from a statement, JavaScript will "return" to execute the code after the invoking statement.

Functions often compute a return value. The return value is "returned" back to the "caller":

```
var x = myFunction(4, 3);        // Function is called, return value will end up in x

function myFunction(a, b) {
    return a * b;                // Function returns the product of a and b
}
```


**Asides**:

Brackets:
```

[ ]
```
Braces:
```

{ }
```

camelCase:
```

var myFirstVariable = value;
```

### Your Guide to Semicolons in JavaScript
When do you need a semicolon? Here’s a handy cheat sheet…

REQUIRED: WHEN TWO STATEMENTS ARE ON THE SAME LINE

The semicolon is only obligatory when you have two or more statements on the same line:

```
var i = 0; i++        // <-- semicolon obligatory
                      //     (but optional before newline)
var i = 0             // <-- semicolon optional
    i++               // <-- semicolon optional
```

OPTIONAL: AFTER STATEMENTS

The semicolon in JavaScript is used to separate statements, but it can be omitted if the statement is followed by a line break (or there’s only one statement in a {block}). A statement is a piece of code that tells the computer to do something. Here are the most common types of statements:

```
var i;                        // variable declaration
i = 5;                        // value assignment
i = i + 1;                    // value assignment
i++;                          // same as above
var x = 9;                    // declaration & assignment
var fun = function() {...};   // var decl., assignmt, and func. defin.
alert("hi");                  // function call
```

All of these statements can end with a ; but none of them must. Some consider it a good habit to terminate each statement with a ; – that makes your code a little easier to parse, and to compress: if you remove line breaks you needn’t worry about several statements ending up unseparated on the same line.

AVOID!

1. After a closing curly bracket

You shouldn’t put a semicolon after a closing curly bracket }. The only exceptions are assignment statements, such as var obj = {};, see above.

```
// NO semicolons after }:
if  (...) {...} else {...}
for (...) {...}
while (...) {...}
```

2. After the round bracket of an if, for, while or switch statement

It won’t harm to put a semicolon after the { } of an if statement (it will be ignored, and you might see a warning that it’s unnecessary).

```
if (0 === 1); { alert("hi") }

// equivalent to:

if (0 === 1) /*do nothing*/ ;
alert ("hi");
```

This code will alert “hi”, but not because 0 equals 1, but because of the semicolon. It makes JavaScript think that you have an empty statement there, and everything to the right of it is treated as no longer belonging to the if conditional and thus independent of it.


An important quirk: inside the () of a for loop, semicolons only go after the first and second statement, never after the third:

```
for (var i=0; i < 10; i++)  {/*actions*/}       // correct
for (var i=0; i < 10; i++;) {/*actions*/}       // SyntaxError
```


## [Function Declaration]()

```JavaScript
function name([param,[, param,[..., param]]]) {
   [statements]
}
```
```code
name
```
The function name.

```code
param
```
The name of an argument to be passed to the function. Maximum number of arguments varies in different engines.

```code
statements
```
The statements which comprise the body of the function.

### Description

A function created with a `function` declaration is a Function object and has all the properties, methods and behavior of Function objects. See [Function](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Function) for detailed information on functions.

A function can also be created using an expression: `function expression`.

By default, functions return `undefined`. To return any other value, the function must have a `return` statement that specifies the value to return.

### Conditionally created functions

Functions can be conditionally declared, that is, a function statement can be nested within an if statement. Most browsers other than Mozilla will treat such conditional declarations as an unconditional declaration and create the function whether the condition is true or not, see this [article](http://kangax.github.io/nfe/#function-statements) for an overview. For this reason, they should not be used — for conditional creation use function expressions instead.

### Function declaration hoisting
`Function declarations` in JavaScript are hoisting the function definition. You can use the function before you declared it:

```JavaScript

hoisted(); // logs "foo"

function hoisted() {
  console.log('foo');
}
```

Note that `function expressions` are not hoisted:

```JavaScript
notHoisted(); // TypeError: notHoisted is not a function

var notHoisted = function() {
   console.log('bar');
};
```

### Examples
#### Using `function`

The following code declares a function that returns the total amount of sales, when given the number of units sold of products `a`, `b`, and `c`.

```javascript
function calc_sales(units_a, units_b, units_c) {
   return units_a * 79 + units_b * 129 + units_c * 699;
}
```
