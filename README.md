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
# CSS Animations :
```css
```

