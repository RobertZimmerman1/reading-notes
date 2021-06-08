## Basics of HTML, CSS and JS

---

### HTML

- Headings, Paragraphs and Typical Types of Markup

  - `<h1>` through `<h6>` denotes standard formatted headings for ease of use
  - `<p>` paragraph
  - `<b>` bold
  - `<i>` italics
  - `<sup>` superscript
  - `<sub>` subscript
  - `<br>` linebreak
  - `<hr />` horizontal break <i>(for a break between sections of a page)</i>

- Structural and Semantic Markup
  - Semantic Markup: Semantic markup are text elements which do not necessarily render to the page. Rather they are intended to provide extra information to the page. Examples of uses for semantic markup include screen readers and search engine optimizers.

### CSS

- What CSS Does

  - The box model: CSS treats every element as if there is a box around it. The boxes can then be targeted and certain elements of the box can have aesthetic rules applied to it. For example, the width, height, text color, background color or image, padding, margin etc. can be manipulated.

- How CSS Works

  - Syntax Example:<br>
    `header { background-color: red;}`  
     In this example "header" is the tag that is being targeted. "background-color and "red" is the declaration which states that all elements that are nested under the "header" tag will have a backround color that is red.

- External CSS
  - External CSS may be applied to HTML documents by linking the HTML file to a CSS file. This is done within the `<head>` element of the HTML file. The syntax to link HTML to CSS is as follows:<br>
    `<link> href="css/styles.css" type="text/css" rel="stylesheet" />`
- Internal CSS
  - Internal CSS may be applied to HTML docuements by including CSS rules directly within the `<head>` tag of the HTML document.
- CSS Selectors
  - Universal Selector = \*
  - Type Selector = h1, h2, h3
  - Class Selector = .nameOfClass
  - ID Selector = #
  - Child Selector = la>a
  - Descendent Selector = a p

### JavaScript

- Variables: Variables are pieces of code which are used to temporarily store values of information. The values of variables is subject to change.<br>
  <b>Example:</b> let myVariable = 'This is a text string.<br>
  The value of the variable titled "myVariable" is the string "This is a text string."
- Variable may be declared with the keywords "let", "const" or "var". However "var" is an outdated method for declaring variables but still exists in some older pieces of code.
- Data Types:
  - Strings: 'This is a string.'
  - Numbers: 50
  - Booleans: True or False
  - Arrays: Store multiple values in a single variable. The multiple values have value and position within the array.
  - Objects: Objects have properties that are organized by value-pairs. For example an object named "car" might have the following value pair properties:
    - car.color = white
    - car.make = ford
    - car.model = F150
- Control Flow
  - Evaluations = Evaluations analyze values in the code and when used with logical operators determine if a statement evaluates to true or false.
  - Loops: Loops are used in statements with logical operators when an evaluation needs to be made repeatedly with iterative values.
  - Decisions: Decisions are used to determine which path through the code should take. For example, if the code evaluates to "x", then go down code-path "a", otherwise, go down code-path "b".
