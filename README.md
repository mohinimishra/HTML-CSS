# Learning HTML & CSS

# Tags in HTML

* ```<strong> </strong>``` It indicates that it is strong importance. Browser makes this text BOLD.
* ```<em> </em>``` : It has stress emphasis. Browser makes its text in Italic.
* ```<a> </a>``` This known as a anchor tag. Use to link either to a different loacation within the current page or to another page. 

``` bash 
<a> google </a>
``` 

# Attribute 

* Elemets can have attributes.
* Attributes  are always within the opening tags.
* It gives extra information to the browser about the element , such as where the link goes or location of the image files.
* Atrributes are followed by :
``` bash
<a href= "https://google.com">google </a>
```
* A link will not work without href attribute.
* Can link to other pages within the site by simply putting the file name.
``` bash
<a href= "about-us.html">about us </a>
``` 
# css

* CSS is written in property: value pairs.
* They are always seprated by colon :
* The value is always followed by semicolon ;
* We can write CSS inside the style attribute 
``` bash
style= "color: blue, font-size: 40px;
```
# Lists In HTML

* List are used for all short of things:
* Regular bullets or numbered lists.
* Navigations 
* Organizing other content
# Two types of list
# Ordered list 
 ``` bash  
 <ol> </ol> 
 ```

# Unordered list
``` 
<ul> </ul>
```
* Each bullets or numbered items is a list item 
``` bash
<li> </li>
```
# example:
``` bash
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
``` bash
<img src ="image.jpg" alt="">
```
# Id & Classes
### The Class selector:
```bash
<p class="intro">...</p>
```
* In CSS , the class attributes is referenced by using a full stop.
```bash
.intro{
    font-size:20px;
    color:#2b5dad
}
```
### The ID Selector:
```bash
< p id="intro">..</p>
```
* An ID is represented by hashtag.
``` bash
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
```bash
<!-- comment here -->
```
* In CSS
``` bash
/* comment here */
```
# layouts In HTML:
* Header
