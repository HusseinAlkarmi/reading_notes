# reading notes 201 

## read 1

## introduction about HTML

The HyperText Markup Language, or HTML is the standard markup language for documents designed to be displayed in a web browser. It can be assisted by technologies such as Cascading Style Sheets (CSS) and scripting languages such as JavaScript. HTML elements are the building blocks of HTML pages.

## HTML structure

+ a line containing HTML version information,
+ a declarative header section (delimited by the HEAD element),
+ a body, which contains the document's actual content. The body may be implemented by the BODY element or the FRAMESET element.

## example of a simple HTML document:

![html](https://www.pslc.ws/macrog/quiknote/html/structure/a_html_code2.gif)


## HTML Extra markup


1. Doctypes

Because there have been several versions of HTML, each webpage should begin with a DOCTYPE declaration to tell a browser which version of HTML the page is using
Browsers usually display the page even if DOCTYPE is not included
In this class, we are using HTML5, so we will include the DOCTYPE as <! DOCTYPE html > at the beginning of each file

2. Comments in HTML

If you want to add a comment to your code that will not be visible to in the user’s browser, you can add the text between these characters
<!-- comment goes here -->
Comments are useful to add notes for yourself, or to make a piece of code invisible to the user until you would like to add it
Although comments are not visible to users in the main browser window, they can be viewed by anyone who looks at the source code behind the page

3. ID Attribute Every HTML element can carry the id attribute
The ID attribute is used to uniquely identify that element from other elements on the page
It’s value should always start with a letter or an underscore, not a number or any other characters
It is important that no two elements on the same page have the same value for their id attributes
ID attributes will become more important when we look at CSS in the future

4. Class Attribute Every HTML element can carry a class attribute
Class attributes define multiple elements as being different from other elements on the page
Class attributes do not need to be unique, but may appear on several different elements that you want to be in the same group
As with ID attributes, class attributes should begin with a letter or underscore, rather than letters or other characters

5. Block Elements

Some elements will always appear to start on a new line in the browser window
These are known as block level elements
Examples of block level elements are < h1 >, < p >, < ul >, and < li >

6. Inline Elements

Some elements will always appear to continue on the same line as their neighboring elements
These are known as inline elements
Examples of inline elements are < a >, < b >, < e m>, and < img >

7. Grouping Text & Elements in a Block

The < div > element allows you to group a set of elements together in one block-level box
You might create a < div > element to contain all of the elements for the header of your site, or you might create a < div > element to contain comments from visitors
In a browser, the contents of the < div > element will start on a new line, but other than this it will make no difference to the presentation of the page

8. Grouping Text & Elements Inline

The < span > element acts like an inline equivalent of the < div > element
It is used to either:
Contain a section of text where there is no other suitable element to differentiate it from its surrounding text
Contain a number of inline elements
The most common reason why people use < span > elements is so that they can control the appearance of the content of these elements using CSS

9. Information About Your Pages

The < meta > element lives inside the < head > element and contains information about the web page
It is not visible to users but fulfills a number of purposes such as telling search engines about your page, who created it, and whether or not it is time sensitive
The meta element is an empty element so it does not have a closing tag. It uses attributes to carry the information
Some common attributes used with the meta tag are name and content. The value of the name attribute is the property you are setting and the value of the content attribute is the value that you want to give this property.
The < meta > element also uses the http-equiv and content attributes in pairs.

10. Escape Characters

There are some characters that are used in and reserved by HTML code (for example, the left and right angled brackets)
If you want these characters to appear on your page you need to use what are termed escape characters
For example:
To write a left angled bracket, you can use either < or <
To write an ampersand (&), you can use either & or &

## What is HTML5 layout?
HTML Layouts. HTML layouts provide a way to arrange web pages in well-mannered, well-structured, and in responsive form or we can say that HTML layout specifies a way in which the web pages can be arranged. Following are different HTML5 elements which are used to define the different parts of a webpage.

![html](https://static.javatpoint.com/htmlpages/images/html-layouts.png)

## Why HTML is used?
HTML is used to create electronic documents (called pages) that are displayed on the World Wide Web. Each page contains a series of connections to other pages called hyperlinks. Every web page you see on the Internet is written using one version of HTML code or another.

* The new HTML5 elements indicate the purpose of
different parts of a web page and help to describe
its structure.
* The new elements provide clearer code (compared
with using multiple < div> elements).
* Older browsers that do not understand HTML5
elements need to be told which elements are
block-level elements.
* To make HTML5 elements work in Internet Explorer 8
(and older versions of IE), extra JavaScript is needed,
which is available free from Google.


# Java script

Javascript (JS) is a scripting languages, primarily used on the Web. It is used to enhance HTML pages and is commonly found embedded in HTML code. JavaScript is an interpreted language.

## What is the use of JS?
JavaScript is a text-based programming language used both on the client-side and server-side that allows you to make web pages interactive. Where HTML and CSS are languages that give structure and style to web pages, JavaScript gives web pages interactive elements that engage a user.

## What is a script and how do I create one?
A script is a series of instructions that a computer can follow to achieve a goal

To write a script, you need to first
state your goal and then list the
tasks that need to be completed in
order to achieve it. 

+ A script is a series of instructions that the computer
can follow in order to achieve a goal.
+ Each time the script runs, it might only use a subset of
all the instructions.
+ Computers approach tasks in a different way than
humans, so your instructions must let the computer
solve the task prggrammatically.
+ To approach writing a script, break down your goal into
a series of tasks and then work out each step needed
to complete that task (a flowchart can help). 

## How do computers fit in with the world around them?

+ Computers create models of the world using data. 
+ The models use objects to represent physical things. Objects can have: properties that tell us about the object; methods that perform tasks using the properties of that object; events which are triggered when a user interacts with the computer. 
+ Programmers can write code to say "When this event OCcurs, run that code." 
+ Web browsers use HTML markup to create a model. of the web page. Each element creates its own node (which is a kind of object).
+ To make web pages interactivé, you write code that uses the browser's model of the web page

## How do I write a script for a web page?

+ It is best to keep JavaScript code in its own JavaScript
file. JavaScript files are text files (like HTML pages and
CSS style sheets), but they have the . j s extension.

+ The HTML < script> element is used in HTML pages
to tell the browser to load the JavaScript file (rather like
the < link> element can be used to load a CSS file).

+ If you view the source code of the page in the browser,
the JavaScript will not have changed the HTML,
because the script works with the model of the web
page that the browser has created.


