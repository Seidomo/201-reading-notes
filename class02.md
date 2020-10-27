
# Class 02 Reading

 - [Home](https://seidomo.github.io/201-reading-notes/home) 


 # MARKUP

 - When creating a web page, you add tags (known as markup) to the contents of the
   page. These tags provide extra meaning and allow browsers to show users the
   appropriate structure for the page.

  - STRUCTURAL MARKUP: the elements that you can use to describe both headings and paragraphs
  - SEMATIC MARKUP: which provides extra information; such as where emphasis is placed in a sentence, 
    that something you have written is a quotation (and who said it), the meaning of acronyms, and so on.

  ## Superscript & Subscript

  - <sup>
The <sup> element is used to contain characters that should be superscript such
as the suffixes of dates or mathematical concepts like raising a number to a power such as 22.
 - <sub>
The <sub> element is used to contain characters that should be subscript. It is commonly
used with foot notes or chemical formulas such as H20.

 ## Quotations

 - <blockquote>
The <blockquote> element is used for longer quotes that take
up an entire paragraph. Note how the <p> element is still
used inside the <blockquote> element. Browsers tend to indent the
contents of the <blockquote> element, however you should not
use this element just to indent a piece of text — rather you should
achieve this effect using CSS.

 - <q>
The <q> element is used for shorter quotes that sit within a paragraph. Browsers are
supposed to put quotes around the <q> element, however Internet Explorer does not —
therefore many people avoid using the <q> element. Both elements may use the cite
attribute to indicate where the quote is from. 

  ## CSS Associates Style rules with HTML elements

- CSS works by associating rules with HTML elements. These rules govern
how the content of specified elements should be displayed. A CSS rule
contains two parts: a selector and a declaration.

  ## CSS Properties Affect How Elements Are Displayed

- CSS declarations sit inside curly brackets and each is made up of two
parts: a property and a value, separated by a colon. You can specify
several properties in one declaration, each separated by a semi-colon.

 ## How Css Rules Cascade 

- If there are two or more rules
that apply to the same element,
it is important to understand
which will take precedence.
- LAST RULE
If the two selectors are identical,
the latter of the two will take
precedence. Here you can see
the second i selector takes
precedence over the first.
- SPECIFICITY
If one selector is more specific
than the others, the more
specific rule will take precedence
over more general ones. In this
example:
h1 is more specific than *
p b is more specific than p
p#intro is more specific than p
- IMPORTANT
You can add !important after
any property value to indicate
that it should be considered
more important than other rules
that apply to the same element.
Understanding how CSS rules
cascade means you can write
simpler style sheets because
you can create generic rules
that apply to most elements and
then override the properties on
individual elements that need to
appear differently.

# JAVASCRIPT

## WHAT IS A VARIABLE?

- A script will have to temporarily
store the bits of information it
needs to do its job. It can store this
data in variables.
When you write JavaScript, you have to tell the
interpreter every individual step that you want it to
perform. This sometimes involves more detail than
you might expect.
Think about calculating the area of a wall; in math
the area of a rectangle is obtained by multiplying two
numbers:
       width x height = area
You may be able to do calcula tions like this in
your head, bu t when writing a script to do this
calculation, you need to give the computer very
detailed instructions. You might tell it to perform the
following four steps in order:
1. Remember the value for width
2. Remember the value for height
3. Multiply width by height to get the area
4. Return the result to the user
In this case, you would use vari ables to "remember"
the va lues for width and height. (This also illustrates
how a scrip( contains very explicit instructions about
exactly what you want the computer to do.)
You can compare variables to short-term memory,
because once you leave the page, the browser will
forget any information it holds.


- [Previous](https://seidomo.github.io/201-reading-notes/class01) 
