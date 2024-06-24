#Writing our First JavaScript Program
 Well now that we have known a little bit about how things work. Now we are ready to write our first JS program.

## Installation and set up
  It's really complex and also risky to build a set up in your computer to run JS. It can harm your system and more dangerous it can crash it. But we're geeks. The codengers :D :0 let's do it 
  soo 
   you need a browser like chrome. I'm preety sure you don't need it but you know for formalities :/ 
    [click here](https://www.google.com/chrome/what-you-make-of-it/) to download. 
   :| :| :|
   and Visual Studio Code (IDE)
   to download VSCode [click here](https://code.visualstudio.com/download)

   and in vs code you can download some extensions like :
   1. live server
   2. live preview
   etc. 

## Codengers assemble 
 Now let's start writing our first program and it's not printing hello world.
 open the chrome console.
 #### if you don't know how then complete the first tutorial please.
 Now 
 write this:
 ```
  alert('codengers')
 ```
 it'll show a pop up we covered it. 
 
 Now let's talk about how to add our js to our web page.
 we've a index.html and index.js attached to this tutorial feel free to fork and learn.
 Then
 to use JavaScript in our web page we have to use 'script' tag.
 for internal JS we can attach it just before our end body (</body>) tag like this:
 ```
 <html>
 <head>
 </head>
 <body>
  Code for body
  <script>
    Our JS here
  </script>
 </body>
 </html>

 ```
Adding JavaScript to the end of the body tag is a common best practice in web development for several reasons:

1. Improved Page Load Performance
  Faster Initial Rendering: Placing JavaScript at the end of the body ensures that the HTML content is loaded and rendered first, allowing users to see the content more quickly. If JavaScript is placed in the head, it can block the parsing of the HTML, delaying the rendering of the page.
2. Reduced Blocking
  Non-blocking Behavior: JavaScript files can block the browser's parsing of the rest of the HTML document. By placing scripts at the end, this blocking only happens after the entire document has been parsed, reducing the time users spend waiting for the initial page to load.
3. Improved Perceived Performance
  Better User Experience: Users perceive pages to be faster when they can see and interact with content sooner. Delaying script loading ensures that the main content is visible before any heavy JavaScript execution begins.
4. Dependencies on DOM Elements
  Availability of DOM Elements: Many JavaScript functions interact with the DOM. By placing scripts at the end of the body, you ensure that all DOM elements have been fully loaded and are available for manipulation.

We can also add our external js file to our code like:

```
  <script src="index.js"></script>
```
 Our script will execute after the html page is loaded. 
 we can also perform mathematical operations like:
 ```
 <script>
  alert(2+3)  this will give a pop up with 5

```
 We'll learn more about these mathematical operations in the further lessons and many more interesting things are waiting. I hope you'll help me in my journey.

 ## Task
  clone this repo or create your own folder in VS Code and create an web page alerting
   'We are pursuing the tutorial'
   
 ## Thank You :) :)
 ## Happy Coding
 ---
 Chiku 
