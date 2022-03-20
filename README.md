# Syllabus Website

This website was a class activity for Introduction to Web Development. The site was built in Visual Studio Code utilizing HTML, CSS, and JavaScript languages, as well as Bootstrap and jQuery frameworks. Due to Grand Canyon University policy, code snippets are only allowed and will be the only code provided. 

#### Languages
HTML, CSS, and JavaScript

#### Frameworks
Bootstrap and jQuery

#### IDE
Visual Studio Code


## Functionality

- Home
  - Presents Introduction to Web Development's syllabus
- Course Matrix
  - Course assignments presented in a table
- Media
  - Support video and audio clips
- Contact Professor
  - Form to contact a Professor
  - NOTE: submitting this form will show PHP code


## Major Concepts

#### New Langauges/Frameworks

- HTML            
- CSS            
- JavaScript     
- jQuery 
- Bootstrap 

NOTE: code snippets will be provided for all five of these languages/frameworks.

#### Skills

- Familiarization with Visual Studio Code
- Development of web pages in HTML
- Styling of pages using CSS
- Adding interaction through JavaScript and jQuery
- Utilizing Bootstrap for fast and responsive design


         
## Code Snippets

### HTML

HTML was used for the overall structure of my website.

An anchor tag with hyperlink allows for linking about to the main/home page.
```
<a href="index.html">Back to Main Page</a>
```
      
                
This is a code snippet from a table that displays assignments for this class. There are three columns- the first is aligned to the left, and the other two are aligned to the center.
```
<!--Table data; row 2-->
<tr>
  <td align="left">Milestone 1: Iteration of Website</td>
  <td align="center">2</td>
  <td align="center">85</td>
</tr>
```   

NOTE: this is not the complete code for the table. 
 
<br/>         
      
      
### CSS

CSS was used for the styling of my website. A separate CSS style sheet was created and linked to all HTML pages - all pages will now follow these formatting styles.


CSS styled the `h2` tags. Color is using hex code (results in purple color), font of Arial, bold, 28px size, and a margin of top 0, left and right 0, and bottom 8px.
```
h2 {color: #4f2fb6; font-family: Arial; font-weight: bold; font-size: 28px; margin: 0 0 8px;}
```

<br/>


### JavaScript

JavaScript added functionality to my pages.


The function will write the string into the HTML page. 
```
//Define a simple function in JavaScript
function sayHello()
{
  document.writeln("Hello class and welcome to CST-120!<br/>");
}
```

NOTE: this was not used within the syllabus activity, but from another activity in class.
NOTE: this snippet was used with the jQuery code snippet below.
          
<br/>

     
### jQuery

jQuery simplifies JavaScript code.


This jQuery code makes sure that the document, and then calls the  `sayHello` method.
```
//Use jQuery document.ready() and pass it ou sayHello() method
$(document).ready(sayHello);
```   

<br/>


### Bootstrap

Bootstrap made design and customization fast and responsive.


Bootstrap's `.nav-item` and `.nav-link` classes were used for styling and making the navigation bar.
```
<li class="nav-item">
  <a class="nav-link" href="tando.html">Course Matrix</a>
</li>
```
 
NOTE: this is a code snippet from the navigation bar and is not the complete code. 
