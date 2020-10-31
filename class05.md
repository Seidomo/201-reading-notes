# CLASS 05 READING NOTES

- [Home](https://seidomo.github.io/201-reading-notes/home) 

## Adding Images

### <img>
To add an image into the page you need to use an <img> element. This is an empty element (which means there is no closing tag). It must carry the following two attributes:
* src 
This tells the browser where it can find the image file. This will usually be a relative URL pointing to an image on your own site. 
* alt 
This provides a text description of the image which describes the image if you cannot see it.
* title 
You can also use the title attribute with the <img> element to provide additional information about the image. Most browsers will display the content of this attribute in a tootip when the user hovers over the image
### Height & width of Images
You will also often see an <img> element use two other attributes that specify its size:
height 
This specifies the height of the image in pixels.
width 
This specifies the width of the image in pixels.

## COLOR

The color property allows you to specify the color of text inside an element. You can specify any color in CSS in one of three ways:
* rgb
values These express colors in terms of how much red, green and blue are used to * make it up. For example: rgb(100,100,90)
* hex
Codes These are six-digit codes that represent the amount of red, green and blue in a color, preceded by a pound or hash # sign. For example: #ee3e80
* Color names 
There are 147 predefined color names that are recognized by browsers.

### OPACITY

CSS3 introduces the opacity property which allows you to specify the opacity of an element and any of its child elements. The value is a number between 0.0 and 1.0 (so a value of 0.5 is 50% opacity and 0.15 is 15% opacity).
The CSS3 rgba property allows you to specify a color, just like you would with an RGB value, but adds a fourth value to indicate opacity. This value is known as an alpha value and is a number between 0.0 and 1.0 (so a value of 0.5 is 50% opacity and 0.15 is 15% opacity). The rgba value will only affect the element on which it is applied (not child elements).
Because some browsers will not recognize RGBA colors, you can offer a fallback so that they display a solid color. If there are two rules that apply to the same element, the latter of the two will take priority. To create the fallback, you can specify a color as a hex code, color name or RGB value, followed by the rule that specifies an RGBA value. If the browser understands RGBA colors it will use that rule. If it doesn't, it will use the RGB value.

### Indenting Text

The text-indent property allows you to indent the first line of text within an element. The amount you want the line indented by can be specified in a number of ways but is usually given in pixels or ems.


### DROP SHADOW

The text-shadow property has become commonly used despite lacking support in all browsers. 
It is used to create a drop shadow, which is a dark version of the word just behind it and slightly offset. It can also be used to create an embossed effect by adding a shadow that is slightly lighter than the text.
The value of this property is quite complicated because it can take three lengths and a color for the drop shadow. 
The first length indicates how far to the left or right the shadow should fall.
The second value indicates the distance to the top or bottom that the shadow should fall.
The third value is optional and specifies the amount of blur that should be applied to the drop shadow.
The fourth value is the color of the drop shadow.




- [Previous](https://seidomo.github.io/201-reading-notes/class04)





