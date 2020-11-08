# CLASS 11 READING NOTES

- [Home](https://seidomo.github.io/201-reading-notes/home) 

## IMAGES

Controlling the size and alignment of
your images using CSS keeps rules that
affect the presentation of your page in
the CSS and out of the HTML markup.

You can also achieve several interesting effects using
background images. In this chapter you will learn how to:

- Specify the size and alignment of an image using

- Add background images to boxes

- Create image rollovers in CSS

You can control the size of an
image using the width and
height properties in CSS, just
like you can for any other box.
Specifying image sizes helps
pages to load more smoothly
because the HTML and CSS
code will often load before the
images, and telling the browser
how much space to leave for an
image allows it to render the rest
of the page without waiting for
the image to download.

You might think that your site
is likely to have images of all
different sizes, but a lot of sites
use the same sized image across
many of their pages.

For example, an e-commerce site
tends to show product photos
at the same size. Or, if your site
is designed on a grid, then you
might have a selection of image
sizes that are commonly used on
all pages, such as:

- Small portrait: 220 x 360
- Small landscape: 330 x 210
- Feature photo: 620 x 400

Whenever you use consistently
sized images across a site,
you can use CSS to control
the dimensions of the
images, instead of putting the
dimensions in the HTML.

First you need to determine the
sizes of images that will be used
commonly throughout the site,
then give each size a name.
For example:
- small
- medium
- large
Where the <img> elements
appear in the HTML, rather
than using width and height
attributes you can use these
names as values for the class
attribute.
In the CSS, you add selectors for
each of the class names, then
use the CSS width and height
properties to control the image
dimensions.

## REAPINTING IMAGES

- repeat
The background image is
repeated both horizontally and
vertically (the default way it
is shown if the backgroundrepeat property isn't used).
- repeat-x
The image is repeated
horizontally only (as shown in
the first example on the left).
- repeat-y
The image is repeated vertically
only.
- no-repeat
The image is only shown once.
The background-attachment
property specifies whether a
background image should stay in
one position or move as the user
scrolls up and down the page. It
can have one of two values:
- fixed
The background image stays in
the same position on the page.
- scroll
The background image moves
up and down as the user scrolls
up and down the page.

## Designing Navigation

Site navigation not only helps people find where they want to go, but also
helps them understand what your site is about and how it is organized.
Good navigation tends to follow these principles...

- Concise
Ideally, the navigation should
be quick and easy to read. It is
a good idea to try to limit the
number of options in a menu to
no more than eight links. These
can link to section homepages
which in turn link to other pages.

- Clear
Users should be able to predict
the kind of information that
they will find on the page
before clicking on the link.
Where possible, choose single
descriptive words for each link
rather than phrases.

- Selective
The primary navigation should
only reflect the sections or
content of the site. Functions
like logins and search, and legal
information like terms and
conditions and so on are best
placed elsewhere on the page.

- Context
Good navigation provides
context. It lets the user know
where they are in the website at
that moment. Using a different
color or some kind of visual
marker to indicate the current
page is a good way to do this.

- Interactive
Each link should be big enough
to click on and the appearance
of the link should change when
the user hovers over each item
or clicks on it. It should also
be visually distinct from other
content on the page.

- Consistent
The more pages a site contains,
the larger the number of
navigation items there will be.
Although secondary navigation
will change from page to page,
it is best to keep the primary
navigation exactly the same.



- [Previous](https://seidomo.github.io/201-reading-notes/class10) 
