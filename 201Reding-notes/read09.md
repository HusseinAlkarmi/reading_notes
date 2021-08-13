# read09

## Forms

### What is form in HTML?

![form](https://www.htmlgoodies.com/wp-content/uploads/2021/04/HTML-Form.png)

HTML Form is a document which stores information of a user on a web server using interactive controls. An HTML form contains different kind of information such as username, password, contact number, email id etc. The elements used in an HTML form are check box, input box, radio buttons, submit buttons etc.

## forms type:

|type=" "|	Description|
 |------------ | -------------|
|text|	Defines a one-line text input field|
|password|	Defines a one-line password input field|
|submit	|Defines a submit button to submit the form to server|
|reset|	Defines a reset button to reset all values in the form.|


## How does an HTML Form work?

+ Your visitor loads the form page in her web browser. The browser sends a request to the web server. 
+ Your visitor fills the form and submits it.
+ The form submission data is sent to the web server. 
+ The web server processes the request. 
+ A response is sent back to the browser.


## Summary FORMS

1. Whenever you want to collect information from
visitors you will need a form, which lives inside a
< form> element.

2. Information from a form is sent in name/value pairs.

3. Each form control is given a name, and the text the
user types in or the values of the options they select
are sent to the server.

4. HTML5 introduces new form elements which make it
easier for visitors to fill in forms.



## What are lists in HTML?

HTML lists allow web developers to group a set of related items in lists.

## There are three list types in HTML:
+ unordered list — used to group a set of related items in no particular order.
+ ordered list — used to group a set of related items in a specific order.
+ description list — used to display name/value pairs such as terms and definitions.

## table in html

## HTML Table Tags
|Tag|	Description|
|------------ | -------------|
|< table>|	Defines a table|
|< th>|	Defines a header cell in a table|
|< tr>|	Defines a row in a table|
|< td>|	Defines a cell in a table|

## What is table in HTML?
A table is a data structure that organizes information into rows and columns.

## Summary LISTS, TABLES AND FORMS
+ In addition to the CSS properties covered in other
chapters which work with the contents of all elements,
there are several others that are specifically used to
control the appearance of lists, tables, and forms.
+ List markers can be given different appearances
using the list-style-type and list-style image
properties.
+ Table cells can have different borders and spacing in
different browsers, but there are properties you can
use to control them and make them more consistent.
+ Forms are easier to use if the form controls are
vertically aligned using CSS.
+ Forms benefit from styles that make them feel more
interactive.


# Events in JS:
JavaScript's interaction with HTML is handled through events that occur when the user or the browser manipulates a page. When the page loads, it is called an event. Events are a part of the Document Object Model (DOM) Level 3 and every HTML element contains a set of events which can trigger JavaScript Code.

![events](https://data-flair.training/blogs/wp-content/uploads/sites/2/2019/07/Ways-of-Using-JavaScript-Events.png)


## TRAVERSING THE DOM

## SELECTOR REQUIRED

|METHOD| DESCRIPTION|
|------------ | -------------|
| find()| All elements within current selection that match selector|
| closest()| Nearest ancestor (not just parent) that matches selector|

## SELECTOR OPTIONAL

|METHOD| DESCRIPTION|
|------------ | -------------|
|parent()| Direct parent of current selection|
|parents()| All parents of current selection|
|children()| All children of cur.rent selection|
| siblings() |All siblings of current selection|
|next() |Next sibling of current element|
| nextAll () |All subsequent siblings of current element|
|prev()| Previous sibling of current element|
|prevAll () |All previous siblings of current element|


| SELECTOR| DESCRIPTION|
|------------ | -------------|
|:button |< button> and < input> elements whose type attribute has
a value of button|
|:checkbox| < input> elements whose type attribute has a value of
checkbox. Note that you get better performance with
$('(type="checkbox"]')|
|:checked| Checked elements from checkboxes and radio buttons
(see : selected for select boxes)|
|: disabled |All elements that have been disabled
|:enabled|All elements that are enabled|
|: focus |Element that currently has focus. Note that you get better
performance with$ (document. acti veEl ement)|
|: file |All elements that are file inputs|
|: image |All image inputs. Note that you get better performance
using (type=11 image"]|
|: input | All < button>, < input>. < select>, and < texta rea>
elements. Note that you get better performance from
selecting elements, then using • filter ( 11 : input 11 )|
|: password |All password inputs. Note that you get better performance
using$ ('input: password')|
|: radio |All radio inputs. To select a group of radio buttons, you can
use$(' input (name="gender"] : radio')|
|:reset |All inputs that are reset buttons
: selected All elements that are selected. Note that you get better
performance using a CSS selector inside the • filter()
method, e.g .. . filter(": selected")|
|: submit| < button> and < input> elements whose type attribute
has a value of submit. Note that you will get better
performance using (type=" submit"]|
|: text Selects| < input> elements with a type attribute whose
value is text, or whose type attribute is not present. You
will likely get better performance from ('input: text')|