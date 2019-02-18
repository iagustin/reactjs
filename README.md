# Learn React.js - Full course for beginners - Tutorial
https://www.youtube.com/watch?v=DLX62G4lc44
vid time 1-5:25
* Components: Reusable pieces of HTML, ie <MyComponent>
* JSX: Code using HTML like syntax you are already familiar with. 
* Props: Passing data around your application.
* State: How to maintain and change data
* Event handling: Interactivity with users.
* Lifecycle methods: Hook into different timing events of your react components.
* Fetching data from API using HTTP
* Forms: Role in creating good user experience

Pre-requisite:
HTML CSS JS ES6

Projects:
@ 5:26 mins

You can modularize code into JSX components.

@11:25 
* Everything is going to have to tie back to an html page of some sort => Everything in the end comes down to creating an HTML. 
* The JS we are going to contineu to write it's simply going to be compiled down to, or turned into elements on a page. The JS we are going to write will be turned into HTML elements on a page. 

@13 mins
* Why import React? To be able to use JSX (sudo language). React library will enable JSX to work.
* JSX: JS rendition or version of HMTL. Looks identical to html with few slight differences.

My understanding: You have one main HTML page. You can manually create an element in the html page, a list item, a css card... But we can automate using JS, so we can create a few thousands of the same element on the page most likely with different data which makes this combo powerful. You are programming in one language, JS, but there is some code that will generate HTML in the end and this part is easier to see if we use JSX, JS that renders html elements.

@39 mins
Components vs elements: Elements end up being html code. If convention is used, elements are lowercase and components usually start with a Capital letter.

Components form a tree. There is one root element and it can have components and elements.

@45:38
Any single Component can only return one element.

@50 mins
Static todo app

func App
 div
  input type 'checkbox'
  p text here
  
  input type 'checkbox'
  p text here
  
  input type 'checkbox'
  p text here

For class on jsx elements use className 

@58 mins
Writing JS in JSX. You need to use {} to insert JS inside JSX.
You can use ES6 literal string `${}` ie `${firstname} ${lastname}`

@ 1 hour
if(){}else if(){}

15. Inline styles
* regular html styles
** h1 style="color: #ddd"
* JSX style expects an object
** h1 style={color: #ddd}
**  this is still wrong
* h1 style={{color: #ddd}}
**   this is better since going from JSX to JS you need to start with {} then add your obj {{color: #ddd}}
**   since now you are inside of JS, everything that can have a dash - in html, inside JSX will need to be camel case. If the value is a number ie fontSize, the value can be a number and it defaults to px. You can specify the measurement but make the value a string

inline styles can make styles dynamic
