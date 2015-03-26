# WireFraming
WIREFRAMING WITH HTML AND CSS

Based on Michael Botsko's article "HTML5 AND CSS3: WIREFRAMING IN THE FINAL PRODUCT" at Webdesignerdepot April 26th 2011
(http://www.webdesignerdepot.com/2011/04/html5-and-css3-wireframing-in-the-final-product/).

If you are just a little proficient in HTML and CSS it is often easier to wireframe with HTML and CSS then graphical tools. This way you also get fast interactive prototypes to test your navigation, task flow, information architecture etc.

OUTLINE

Use the CSS outline property on all major block level tags as shown in the wireframe.css

TRANSPARANCY

Use background-color with opacity (via RGBa) as shown in wireframe.css. This will make overlapping elements look darker!

IMAGES

Using the wireframe.js will turn all image tags into DIV tags. Just use with and height attributes in your image tag and the DIV will be set to this size in pixels. The div has a class 'image_holder' for seperate styling.

WIREFRAME.JS

Apart from making images to DIV's the javascript shows css information (height, with, padding and margin) on hover via the title attribute. This works for most block level elements.

