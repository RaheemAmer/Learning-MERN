finish iti project and graduate
self study + check resources and study it well 
 then apply for front end in route 
apply for front end boot camp in sprints ( Angular)
---
New Roadmap
finish html and css  from 
Free code camp
Dr Angela boot camp
100 days of code
-----
Notes:
there two ways to get a dimension size or unit for css element
Absolute (Not dynamical) - px - not so good as it's not compatible with all smart phones cuz not all of them have same number of pixels and this make a styling problems
Relative  (dynamic) -  rem and &
used <pre> </pre> to write special characters - html shortcuts
you can't use text-align: center on image not because it's not image but because it' doesn't align the element  on which you apply it on but it does on the content of that element
so you can align the nested elements only - so if you put the align-items: center in body css everything will be centred cuz it only works if there is content
structure the css elements according to html elements
margin = spacing between elements - top bottom left right 
lang helps screen readers and search engines       
relative path
naming conventions in html and css are all small
"pseudo-selector"? a:hover
Why is it called "Cascading Style Sheets"?
because more than one css rule may apply to the same element
-----------------
inheritance and specificity
box model
------------------
---
css
font
img
list
display
---
list-style: none
for both li and ul
the property will be disabled
---
Day 3:
4 types of color:
- rgb
- hcl
- hex code
- name of color
----------------------------------------------------------------
inheritance , nesting and parent elements
three main terms in css:
- inheritance
- cascading style sheet ( if we put 2 list-style in the li element the order of them will be crucial, cuz the first one will be eliminated and the other one will be the one applied)
- specificity (but if you type in the ol that list-style: none yet nothing is changed, cuz the first thing happened is i targeted a specific element (li) so ol is less specific
- class is more specific than descendant  ( main p )
-  span - a - img - button are all of them are inline  
----------------------------------------------------------------
Css box model:
[  content ]  padding [top, bottom, right, left]
- the space between the content in the box and the border s  is called padding
[  ]  = > border 
- shorthand ( border: width = 1px, type of border,  color of the border)
[  ]  = > margin
- space between borders of each element
----------------------------------------------------------------
body
h1  [header]
anchor tag [header]
ol [ main ]
li[ main ]
p[ main ]
body [footer]
----------------------------------------------------------------
selectors 
Tag - p
ID 
Class
Attribute - src
Universal  *
Grouping p, .some-class
Combined  p.some-class
Pseudo  a:hover
----------------------------------------------------------------
combinators
descendant = li p = all paragraphs with li as their parent
child = h2 > p = only p that are direct children of h2
----------------------------------------------------------------
properties applied on inline elements:
 You can add space to the left and right on an inline element, but you cannot add height to the top or bottom padding or margin of an inline element.
----------------------------------------------------------------
Inline-Block
Inline-block  elements are similar to inline elements, except they can have padding  and margins added on all four sides . Also, width and heights. You’ll have to declare display:  inline-block in your CSS code.
----------------------------------------------------------------
margin-collapsing 
only happens for block elements
vertical margin only has margin-collapse
bigger margin wins
must be adjacent to each other (on top of each other)
if there is something between then nothing will happen
if there is nesting between then no margin collapsing will happen
----------------------------------------------------------------
red
margin bottom 20
margin top 40
blue
margin top = 40 wins
---
red
margin bottom 20
hr
margin top 40
blue
margin top = 40 wins
margin collapse won't happen
----------------------------------------------------------------
box-shadow:
4 values
x axis - y axis - blur radius -  color
5px         5px          5px              red
---------------------------------------------------------------- 
center block elements
margin: auto;
margin: top right bottom left;
---------------------------------------------------------------- 
width is not inherited
---------------------------------------------------------------- 
you can set margin to h1 unless it's bigger to it's better to put padding into the parent element
you should only use one h1 in the whole document
color will be inherited bu child elements and descendants (background-color is not and link also because it browser default style which has a higher specificity than the style we applied )
list items have default margin and padding so if you want to edit them and make theme inherit stuff you have to give them a value of zero
---------------------------------------------------------------- 
How do you align text in a block?
For  vertical alignment, set the parent element's width / height to 100% and  add display: table . Then for the child element, change the display to  table-cell and add vertical-align: middle . For horizontal centering,  you could either add text-align: center to center the text and any other  inline children elements.
---------------------------------------------------------------- 
The default box sizing is content-box, which means padding and borders are added to the overall box.
---------------------------------------------------------------- 