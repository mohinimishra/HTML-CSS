# Learning HTML & CSS

# Tags in HTML

* ```<strong> </strong>``` It indicates that it is strong importance. Browser makes this text BOLD.
* ```<em> </em>``` : It has stress emphasis. Browser makes its text in Italic.
* ```<a> </a>``` This known as a anchor tag. Use to link either to a different loacation within the current page or to another page.
 


``` html 
<a> google </a>
```
* ``` <h1></h1> <h6></h6>``` This is heading tags. 
* ``` <p> </p>``` Used to write paragraph.
* ``` <div> </div>``` Short for division.
* ``` <span> </span>``` A container for small piece of text. Smaller Div.
# Attribute 

* Elemets can have attributes.
* Attributes  are always within the opening tags.
* It gives extra information to the browser about the element , such as where the link goes or location of the image files.
* Atrributes are followed by :
``` html
<a href= "https://google.com">google </a>
```
* A link will not work without href attribute.
* Can link to other pages within the site by simply putting the file name.
``` html
<a href= "about-us.html">about us </a>
``` 
# css

* CSS is written in property: value pairs.
* They are always seprated by colon :
* The value is always followed by semicolon ;
* We can write CSS inside the style attribute 
``` html
<h1 style= "color: blue, font-size: 40px;">Hello</h1>
```
# Lists In HTML

* List are used for all short of things:
* Regular bullets or numbered lists.
* Navigations 
* Organizing other content
# Two types of list
# Ordered list 
 ``` html  
 <ol> </ol> 
 ```

# Unordered list
``` 
<ul> </ul>
```
* Each bullets or numbered items is a list item 
``` html
<li> </li>
```
# example:
``` html
<ol>
<li> List item  </li>
<li> list item </li>
<li> List item </li>
</ol>
```
# Images In HTML
* Images are like links, they required an attribute to work.
* Images are diff. from others elements, they are self-closing.
* Use src attribute which is short of source.
* Images are not valid without an alt atrribute.Used to describe the image.
``` html
<img src ="image.jpg" alt="">
```
# Id & Classes
### The Class selector:
```html
<p class="intro">...</p>
```
* In CSS , the class attributes is referenced by using a full stop.
```css
.intro{
    font-size:20px;
    color:#2b5dad
}
```
### The ID Selector:
```html
< p id="intro">..</p>
```
* An ID is represented by hashtag.
``` css
#intro{
    font-size:20px;
    color: 2b5dad;
}
``` 
* ID is indivisual. Can be used on time per page.
* Class is a group. Can be used over and over again.
* ID will overwrite teh Class, if they both are selecting the same thing.

# Comments in HML & CSS

### Two diff. ways to write them
* In HTML 
```html
<!-- comment here -->
```
* In CSS
``` css
/* comment here */
```
# layouts In HTML:
* Header

# Self-closing tags :
* Input tag:  It allows user to input their stuff into the Website.
```html
<input>
```
# CSS Background-Properties:
* background-color
* background-image
* background-repeat
* background-attachment
* background-position

## Background-color:

### Opacity / Transparency :
* The opacity property specifies the opacity/transparency of an element.
* It can take a value from 0.0 - 1.0. The lower value, the more transparent.
``` css
div {
    opacity: 0.3;
    }
```
# Transparency using RGBA:
* If you do not want to apply opacity to child elements, like in our example above, use RGBA color values.
*It sets the opacity for the background color and not the text.
``` css
   div {
        background: rgba(0,0,0,0);
   }
```
* An RGBA color value is specified with: rgba(red, green, blue, alpha). The alpha parameter is a number between 0.0 (fully transparent) and 1.0 (fully opaque).

### Background-image:
* The background-image property specifies an image to use as the background of an element.
* By default, the image is repeated so it covers the entire element.
```css
 body {
    background-image: url("paper.gif");
}
```
# Background-Repeat:
* If the image is repeated only horizontally (background-repeat: repeat-x;), the background will look better.
```css
body {
  background-image: url("gradient_bg.png");
  background-repeat: repeat-x;
}
``` 
* To repeat an image vertically, set background-repeat: repeat-y.
* Showing the background image only once is also specified by the background-repeat property.
``` css
body {
  background-image: url("img_tree.png");
  background-repeat: no-repeat;
}
```
# CSS Backgroubd-Positions:
* The background-position property is used to specify the position of the background image.
``` css
body{
 background-position: right top;
}
 ```
 # CSS background-attachment:
 * The background-attachment property specifies whether the background image should scroll or be fixed (will not scroll with the rest of the page).
 ```css
 body{
     background-attachment: fixed;
 }
```
* Specify that the background image should scroll with the rest of the page.
``` css
body{
    background-attachment: scroll;
}
```
# CSS Border Properties:
* The CSS border properties allow you to specify the style, width, and color of an element's border.

# CSS Border Style:
* The border-style property specifies what kind of border to display.
``` css
border-style: dotted;
``` 




































# CSS Animations :
* An animation lets an element gradually change from one style to another.
* You can change as many CSS properties you want, as many times you want.
* Keyframes hold what styles the element will have at certain times.
## The @keyframe Rule :
* When you specify CSS styles inside the @keyframes rule, the animation will gradually change from the current style to the new style at certain times.

```css
/* The Animation code */

@keyframe example {
    from {background-color: red;}
    to   {background-color: yellow;}
}

/* The element to apply the animation to */

div{
    width:100px;
    height:100px;
    animation-duration:4s;
    animation name:example;
    background-color:red;
}
```
* The animation-duration property defines how long time an animation should take to complete. If the animation-duration property is not specified, no animation will occur, because the default value is 0s (0 seconds). 

* sIt is also possible to use percent. By using percent, you can add as many style changes as you like.


* The given example  will change both the background-color and the position of the div element when the animation is 25% complete, 50% complete, and again when the animation is 100% complete:

# Animation Delay Properties:
*The animation-delay property specifies a delay for the start of an animation.
```css
animation-delay:2s;
```

# Animation-Iteration-Count:
* The animation-iteration-count property specifies the number of times an animation should run.
```css
animatin-iteration-count:3;
```
* Uses the value "infinite" to make the animation continue for ever
``` css
animation-iteration-count: infinite;
```
# Animation-Direction Properties:
* The animation-direction property specifies whether an animation should be played forwards, backwards or in alternate cycles.
``` css
animation-direction: normal; 
animation-direction: reverse; 
animation-direction: alternate; 
animation-direction: alternate-reverse;
```
* Normal - The animation is played as normla(forward). This is by default.
* Reverse - The animation is played as reverse direction (backward).
* Alternate - The animation is played forward first, then backward.
* Alternate-reverse - The animation is played backword direction first then forward. 
# Specify the Speed Curve of the Animation:
* The animation-timing-function property specifies the speed curve of the animation.
``` css
animation-timing-function: ease;
```
* The animation-timing-function property can have the following values:

* ease - Specifies an animation with a slow start, then fast, then end slowly. This is by default.
* linear - Specifies an animation with the same speed from start to end.
* ease-in - Specifies an animaion with a slow start. 
* ease-out -  Specifies an animaion with a slow end.
* ease-in-out-  Specifies an animaion with a slow start and end.
* cubic-bezier(n,n,n,n) - Lets you define your own values in a cubic-bezier function.  
# CSS Icons:
* The simplest way to add an icon to your HTML page, is with an icon library, such as Font Awesome.
* Add the name of the specified icon class to any inline HTML element (like <i> or <span>)
# Font Awesome Icons:
```css
<script src="https://kit.fontawesome.com/yourcode.js"></script>
```






