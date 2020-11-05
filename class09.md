# CLASS 09 READING NOTES

- [Home](https://seidomo.github.io/201-reading-notes/home) 

## FORMS AND EVENTS

### Form Controls
- ADDING TEXT
- Making Choices
- Submitting Forms
- Uploading Files

### How Forms Work

A user fills in a form and then presses a button
to submit the information to the server.
A form may have several form controls, each
gathering different information. The server
needs to know which piece of inputted data
corresponds with which form element.

### Form Structure

- form
Form controls live inside a
form> element. This element
should always carry the action
attribute and will usually have a
method and id attribute too.

- Action
Every form element requires
an action attribute. Its value
is the URL for the page on the
server that will receive the
information in the form when it
is submitted.

- Method

Forms can be sent using one of
two methods: get or post.
With the get method, the values
from the form are added to
the end of the URL specified in
the action attribute. The get
method is ideal for

● short forms such as search boxes

● when you are just retrieving data from the web server
not sending information that
should be added to or deleted
from a database  With the post method the
values are sent in what are
known as HTTP headers. As a
rule of thumb you should use the
post method if your form:

● allows users to upload a file

● contains sensitive data e.g. passwords

● adds information to, or deletes information from, a 
database If the method attribute is not
used, the form data will be sent
using the get method.

- Id
We look at the id attribute 
 but the value is used to
identify the form distinctly from
other elements on the page (and
is often used by scripts — such
as those that check you have
entered information into fields
that require values).

### Password Input

- input
type = password
When the type attribute has
a value of password it creates
a text box that acts just like a
single-line text input, except
the characters are blocked out.
They are hidden in this way so
that if someone is looking over
the user's shoulder, they cannot
see sensitive data such as
passwords.
- name
The name attribute indicates
the name of the password input,
which is sent to the server with
the password the user enters.
size, maxlength
It can also carry the size and
maxlength attributes like the
the single-line text input.

### Text Area

- textarea
The textarea element
is used to create a mutli-line
text input. Unlike other input
elements this is not an empty
element. It should therefore have
an opening and a closing tag.
Any text that appears between
the opening textarea and
closing textarea tags will
appear in the text box when the
page loads.
If the user does not delete any
text between these tags, this
message will get sent to the
server along with whatever the
user has typed. Some sites
use JavaScript to clear this
information when the user clicks
in the text area.

### Drop Down List Box

- select
A drop down list box also
known as a select box allows
users to select one option from a
drop down list.
The select element is used
to create a drop down list box. It
contains two or more option
elements.
- Name
The name attribute indicates the
name of the form control being
sent to the server, along with the
value the user selected.
- option
The option element is used
to specify the options that the
user can select from. The words
between the opening option
and closing option tags will
be shown to the user in the drop
down box.
- Value
The option element uses the
value attribute to indicate the
value that is sent to the server
along with the name of the
control if this option is selected.
- Selected
The selected attribute can be
used to indicate the option that
should be selected when the
page loads. The value of this
attribute should be selected.

### TABLE PROPERTIES

You have already met several
properties that are commonly
used with tables. Here we will
put them together in a single
example using the following:
- width to set the width of the table
- padding to set the space
between the border of each table
cell and its content
- text-transform to convert the
content of the table headers to
uppercase
- letter-spacing, font-size
to add additional styling to the
content of the table headers
- border-top, border-bottom
to set borders above and below
the table headers
- text-align to align the writing
to the left of some table cells and
to the right of the others
- background-color to change
the background color of the
alternating table rows


- [Previous](https://seidomo.github.io/201-reading-notes/class08) 
