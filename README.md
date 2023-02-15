# introduction to markdown

# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

---
-
<!--italics-->

_This is italic style_

*This is italic style*
---
<!--strong-->
This is an example of **stronng text**, anthing between the opening asterisk and closing asterisk will be displayed as **strong text**

This is another example of a way to have __strong text__ in our document. Anything between the double opening underscore and closing underscore will be displayed as __strong text__
<!--strike through-->
This is an example of ~~strike through~~, anything between the doulble opening tilde and closing tilde wll be displayed as ~~strike through~~ text

---
<!--Horizontal Rule-->
We can add triple hypens to be able to create a horizontal rule for separate content.

Another way to add __Horizontal Rule__ int our document markdown is by using three underscore.
___

<!--escaping character Rule using backslash-->
this is an example of a *text with an asterisk*, when we don't want it to be italicized. We want to use \ backslash to escape the rule of using opening \*asterisk* and closing \*asterisk* to enclose the content.

---
<!--Bl0ckquote Rule-->

> We use greater than symbol to display a block of text as a quote with a background and line on the left side.

> *"You don't have to be great to start, but you have to start to be great"* - __Unknown Author__

---
<!--Links Rule-->
**NOTE:** we would want to put the link description inside of the square brakets and the link to the resource inside the open and close parenthesis
[hermart's pexel account](https://www.pexels.com/@hermart-rey-torreon-455904153/)

---
**NOTE:** we can add a baloon tip description to our link by using double quote after the link to the resource
[hermart's pexel account](https://www.pexels.com/@hermart-rey-torreon-455904153/ "this will take you to hermart pexel account")

---
<!--List item rule-->

<!--Unordered list-->

* item 1: This is going to be our list item 1
  * this is our list item 1 child item 1
  * this is our list item 2 child item 2
* item 2: This is going to be our list item 2
  * this is our list item 2 child item 1
  * this is our list item 2 child item 2
* item 3: This is going to be our list item 3
  * this is our list item 3 child item 1
  * this is our list item 3 child item 2
* item 4: This is going to be our list item 4
  * this is our list item 4 child item 1
  * this is our list item 4 child item 2
* item 5: This is going to be our list item 5
  * this is our list item 5 child item 1
  * this is our list item 5 child item 2

<!--Ordered list-->

1. item 1: This is going to be our list item 1

     1.1 this is our list item 1 child item 1
  
     1.2 this is our list item 2 child item 2
  
2. item 2: This is going to be our list item 2

     2.1 this is our list item 2 child item 1
  
      2.2 this is our list item 2 child item 2
  
3. item 3: This is going to be our list item 3
  
      3.1 this is our list item 3 child item 1
  
      3.2 this is our list item 3 child item 2

4. item 4: This is going to be our list item 4

     4.1 this is our list item 4 child item 1
  
     4.2 this is our list item 4 child item 2

5. item 5: This is going to be our list item 5

     5.1 this is our list item 5 child item 1
  
     5.2 this is our list item 5 child item 2

---
<!--Code block with inline example rule-->

**NOTE:** *__Backticks__ will allow us to show the code block and paragraph tags in this example. it is located below the telda character and on top of tab key.*
`<p> this is a paragraph with an inline code block example opening and closing tag</p>`

---
<!--Image of a dog-->

[dog image](https://www.newshub.co.nz/home/lifestyle/2019/11/dog-years-are-a-myth-2-year-old-dogs-already-middle-aged-scientists/_jcr_content/par/video/image.dynimg.1280.q75.jpg/v1574572358818/GETTY-labrador-puppy-1120.jpg "link to image")

---
<!-- Github flavor set of code blocks-->

```
npm install

npm start
```

**NOTE** you can specify some code blocks for different languages

```javascript
function testAdd(num1, num2){
 return num1 * num2;
}
```
```python
function pythonAdd(num1, num2)
 return num1 * num2;
```
```C#
public static int Sum(int num1, int num2){
 int total;
 total = num1 + num2
 return total;
}
```

---

<!--Table rules-->

| Name           | NickName  | Email                    |
|----------------|-----------|--------------------------|
|hermartrey      | beboy     | hermartreyt@gmail.com    |
|ellanah grace   | bechay    | ellanah@gmail.com        |
|charlie may     | Mai2x     | charliemay@gmail.com     |
