<h4>Introduction to HTML/CSS</h4>

HTML stands for Hyper Text Markup Language.

HTML defines the structure and layout of a Web document by using a variety of tags and attributes. The correct structure 
for an HTML document starts with ```<html><head>```(enter here what document is about)```<body>``` and ends with ```</body></html>```. 
All the information you'd like to include in your Web page fits in between the ```<body>``` and ```</body>``` tags.

Eg:

Structure of a basic html webpage:

``` 
  <html>
    <head>
      <title>My Page</title>
    </head>
      <body>
        Hello World!
      </body>
  </html>
```
Assigning value to a div ID attribute:
```
<div id="about"></div>
``` 

For the class attribute:
``` 
<div class="textStyle"></div>
```

CSS: Cascading Style Sheets (CSS) is a style sheet language used for describing the look and formatting of a document 
written in a markup language.

ID vs Class

IDs must be unique where as class can be applied to many tags. In CSS, IDs look like #elementID and class elements 
look like .someClass

In general, use ID whenever you want to refer to a specific element and class when you have a number of things that 
are all alike. For instance, ID elements are things like header, footer, sidebar. Common class elements are 
things like lists or using the same class to apply the same rules to multiple tags.

It's a good idea to read up on the cascade and understand the precedence assigned to various selectors: 
http://www.w3.org/TR/CSS2/cascade.html

The most basic precedence you should understand, however, is that ID selectors take precedence over class selectors. 
If you had this:

```
<p id="intro" class="foo">Hello!</p>
```
and the CSS rules for the above tag would be:
```
#intro { 
  color: red;
}
.foo { 
  color: blue; 
}
```
The text would be red because the ID selector takes precedence over the class selector.

IDs are an incredibly powerful tool. An element with an ID can be the target of a piece of JavaScript that manipulates 
the element or its contents in some way. 

ID example
```
#about {
    background: red;
}
```

Class example
```
.textStyle {
  color: white;
}
```
Here's a great resource with more details: http://www.c4learn.com/css/css-syntax/
