#Read 05

**Introduction to CSS**

### 1. What is CSS?

It is a language that tells the browser how the the content will look like. In other words, it is used for styling HTML text. 

### 2. How CSS works: 
* Elements in CSS are surrounded by 'boxes.' Each box has the following: A border, padding, and margins. 
* CSS is based on the concept of selecting HTML tags and adding styling properties/rules to them.

### 3. How does a CSS rule look like? 

HTML element { 
               The property you want to assign: propoerty type/details; 
               }


**Here is an example:** 

h2 {
     backgroung-color: red;
   }
   
 ### 4. How to selcet HTML elements: 
 
 1. The Universal selector: \* which selects all the elements in the file. 
 
 2. The class attribute: it is about creating a style rule inside this attribut and then we can include the class within any HTML element. 
 *Example:*
 
 .articles-color {
                    color: yellow;
                 }  
                 
 *Classes are created by adding a fullstop before the class name.*
 
 3. Typer Selector: it is similar to the rule in section 3; we just add the tag we are targetting. We can target multiple tags at once by separating them with commas. 
                  
4. Id Selector: this attributes is used to easily select a certain element by naming it which makes it more specific. 
*Example:* 
In HTML: 
/<h1 id="maintitle"> Hello World <\h1>
In CSS: 
h1 /#maintiltle {.....}

**These are the selectors that have been coverd in class so far, more selectors can be found in chapter 10 in this [book](https://slack-files.com/files-pri-safe/TNGRRLUMA-F01H75KA5J5/html_css.pdf?c=1608029796-3393f4231711ec5d).** 

### 5. What does Cascading mean?

It is the idea that the last writter element over-rides the previous similar element. 








               
               
               
               
             
               
           










