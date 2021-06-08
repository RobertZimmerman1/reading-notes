# What is CSS?

CSS stands for Cascading Style Sheets.  It is the programming language that defines the aesthetic style of a webpage.  CSS differs from the presets in HTML in that one can precisely control the styling variables to a far greater degree.

Aspects that can be controlled with CSS include:

- Color
- Font Size
- Bold / Italics
- Relative Position
- Border
- Padding
- Background Color

### Selectors

CSS operates by targeting HTML content that has been defined by it's Class, ID or Tag.  For instance, if one set up a CSS rule that stated all Elements with the Class of "h2" will be periwinkle blue, that would then render as such.

### CSS Syntax

Here are two examples of the syntax of a CSS rule:

h1 {
    color: periwinkleblue
    font-size: 7em
}

quote {
    font-style: italic
}

Therefore, any HTML elements with the Tag of either h1 or quote would visually display those traits.

### Linking the Stylesheet

The HTML part of the programming must be told where to find the CSS part of the programming.  This is done by referencing the two.  To reference associated HTML and CSS files within the "head" tag use a "link" tag.  For example, the code looks like this:

head

    link rel="stylesheet" href="goodstyle.css

head

*(Brackets have been ommited from tags in the preceeding example.)*