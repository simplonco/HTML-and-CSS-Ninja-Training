# HTML and CSS Ninja Training!

**Prerequisites HTML**
------------------

* Understand [CSS selectors](http://discourse.simplon.co/t/selecteurs-css/32/1)

* Understand `width`, `height`, `padding`, `border` and `margin`


**Course**
---------

<http://fr.learnlayout.com/>

Page 1 to 6: mostly, it’s better that the `width` and `height` integrate `padding` and `border`. This section tells you how to do that. 

Pages 7 to 13: explanations of the positioning of elements. 

Page 14: explanation on how to make a responsive website. Skip this page for the moment.

Page 16: description of `display: inline-block` to horizontally align elements that usually line up vertically. 

Page 17: Skip this page for the moment. 

After all this, you understand the essentials of CSS and can confidently move on!  

**Attributes used**
----------------------

```css
    /* to definewidth of elements */
    display: inline-block;
    
    /* needed with inline­block */
    vertical-align: top;
    box-sizing: border-box;
    width: 100%;
    min-height: 100px;
    border: 1px #000 solid;
    margin: 0; /* outer margin */  
    padding: 0; /* inner margin */
```
------------------------------------------------------------

EXERCISE 1 - HTML
-----------------

**Test 1 :**

Create two paragraphs with a height of 300 pixels and a width of 700 pixels. Include a very long 
text and manage the overflow so it’ll be fully legible.

**Test 2 :**

Create five titles (level 2) and display them as a list (look for the property `display`).

**Test 3 :**

In a `<div>` element, include a `<span>` element with text inside and apply a bloc style.  

**Test 4 :**

Create a vertical menu whose items are links `<a>`.

**Test 5 :**

Create an image containing a paragraph with text and two consecutive elements `<img />`.
Make images floating, the first on the left and the second on the right. 

**Test 6 :**

Place three images of different sizes in the same page. Find the CSS properties so they will be 
displayed with the same size. Then position them to get a cascade effect with constant horizontal 
and vertical offset for each image relative to the previous one. The user must be able to put each 
of them in the foreground by mouse hover on it (look at property `z-index`).

**Test 7 :**

Create a layout with three columns of respective widths of 20%, 65% and 15%. The first and third 
ones respectively shall contain a menu and a list of links created from images. The central 
column must have editorial content. 

**Test 8 :**

Create a layout modeled on the figure below:

![](http://discourse.simplon.co/uploads/default/original/1X/56fb84ccace7ac3435101813835f602df2cd3425.png)

The left column (item 1) has a width of 200 pixels and the panel (item 2) has a height of 150 
pixels. The banner contains the title of the site. The left column contains a menu of the main 
zone (item 3), text and images (your choice). The first link of the menu must display a page 
having the same structure and the same content in zones 1 and 2, but a different editorial 
content in Zone 3.

RESSOURCE HTML
--------------

<https://developer.mozilla.org/fr/docs/Web/HTML/Element>

EXERCISE 2 - CSS
----------------

<http://flukeout.github.io/>

EXERCISE 3 - TEMPLATES
---------------------

Progressively realize this page, ideally without looking at the CSS.

<http://chatchan.us/gabarits.html>

The more adventurous can directly reproduce the templates of this site: 

<http://www.alsacreations.com/static/gabarits/liste.html>

Please note, you must reproduce the entire template page! 
