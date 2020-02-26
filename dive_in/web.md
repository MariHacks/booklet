# Web Development

Building a website or a web application is no simple task. It’s a process with a whole lot of steps. However, fret not, there are plenty of tools to help you in this process. The task of a web developer can be mainly divided into 2 parts: front-end and back-end. Front-end refers to the part of the website that the visitor can see and interact with \(the client\), while back-end refers to the server-side mechanisms that interact with the databases and other cloud services \(the server\).

A great resource that can help you get started with web development is [Free Code Camp](https://www.freecodecamp.org). To have a solid foundation in web development, doing the HTML5 and CSS \(5 hours\) as well as the Basic Javascript \(10 hours\) courses would be a great start. Once you finished those, you can look into other courses such as Bootstrap and jQuery to sharpen your skills. There are also some courses on Node.js and React.js available.

A great resource that can help you get started with web development is [Mozilla Developer Network](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web). To have a solid foundation in web development, working through and up to the HTML, CSS, and JavaScript basics is a great start. Once you finished those, you can look into other tutorials such as Bootstrap and jQuery to sharpen your skills.

* [Getting started with the Web](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web)

## HTML \(HyperText Markup Language\)

HTML is the most fundamental language in web development. When you visit a website, your browser downloads the .html file from the server and displays the content from the HTML code. Basically, the point of a browser is to read HTML code \(as well as CSS and Javascript\).

HTML is very beginner-friendly, as all you need to start coding in HTML is Notepad and a browser. If you want to do web development, HTML is a must-know. [Here's](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/HTML_basics) a guide that will teach you all you need to know about this language.

## CSS \(Cascading Style Sheets\)

CSS is used to complement HTML. While HTML is great for displaying the content of a webpage, CSS focuses on the presentation of that content. Let’s say you have a paragraph of text on your website. Maybe you want it to be blue, to have a Calibri font with size 56, to show text shadow and to grow bigger with an animation when you hover it. CSS got you covered. To use CSS, you can either write the CSS code directly in the HTML code or in a separate file.

* [Beginner’s guide](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/CSS_basics)
* [Exhaustive list of CSS properties](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference)

## JavaScript

JavaScript is extremely popular and versatile programming language. Traditionally, JavaScript is used along with HTML and CSS for front-end development. However, there are many frameworks for JavaScript out there which simplify and extend its implementation. With the right framework, Javascript can be used almost everywhere, front-end and back-end. That’s why it’s a good idea to get familiar with this language before the hackathon.

There are plenty of resources to learn vanilla JavaScript on the web that are available with a simple Google search. [Here](https://developer.mozilla.org/en-US/docs/Learn/JavaScript) is a good place to start with. You can also try [W3Schools](https://www.w3schools.com/js/).

* [Beginner's guide](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics)
* [Complete documentation](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference)

## Learn Front-End

Front-end of a website is defined as the user interface, as in what the user interacts with directly and how it looks from a stylistic point of view. When getting started, it's always preferable to stick with simple HTML and CSS. However, once you gain experience you can start using more advanced JavaScript libraries to create more complex user interfaces.

For a simple HTML page, once the page has been loaded, the content of the can be changed using JavaScript. However, when building very complicated user interfaces, doing operations on the HTML manually can be unwieldy. This is where UI libraries such as Vue.js and React.js come in.

### Vue.js

Vue.js is one such JavaScript library for building complex interfaces.

* [Official guide](https://vuejs.org/v2/guide/)

### React.js

Another such library is React.js. For a static HTML page, once the page has been loaded, the content of the page doesn’t change anymore. React.js allows the content of your web page to change over time, which is key in user interactivity. If you want to build a web application, React.js can be a very useful tool for you.

If you want to start learning React.js, the official website has a great tutorial on how to build a simple [tic-tac-toe game](https://reactjs.org/tutorial/tutorial.html) with it. It’s a good place to start. There are also many more intermediate and advanced guides on the official website.

* [Official tutorial](https://reactjs.org/tutorial/tutorial.html)

## Learn Back-End

Back-end is what the user can not see but it is essential to the functioning of a website, such as the databases and complex logic and algorithms running in the background. The back-end of an app hosts all the business logic and processing that happens behind the app, such as handling accounts and logins.

### Flask (Python)

If you prefer using Python, then Flask is a great library to use. Flask
makes creating a simple back-end server quick and easy.

* [Official guide](https://flask.palletsprojects.com/)
* [Official website](https://palletsprojects.com/p/flask/)

### Express (Node.js)

Traditionally, Javascript is used for client-side development: the Javascript code is embedded in HTML code and interpreted by the client’s browser. However, Node.js is a runtime environment which allow us to run server-side Javascript. This means that it is possible to create a server and interact with databases, all that with the familiar Javascript! Node.js uses a package manager called **npm**, which allows user to install external packages and modules very easily.

To transform your computer into a server and run Node.js code on it, you have to first install the runtime environment onto your computer. You can download it from their official [website](https://nodejs.org/en/). To run a Node.js application, you have to use the command prompt and navigate to the path of the folder that contains the script you created. Then, you can use the _**node &lt;filename&gt;.js**_ command to initiate the script. This will create a local testing server, with the address “localhost:&lt;port number&gt;”, that will run your script. A great beginner’s guide [here](https://www.w3schools.com/nodejs/nodejs_get_started.asp) by W3Schools. If you are planning on using external modules, here’s a beginner’s guide on how to use [npm](http://nodesource.com/blog/an-absolute-beginners-guide-to-using-npm/).

Then, you can use a nodejs library called Express to create a back-end server.

* [Express guide](https://expressjs.com/en/starter/installing.html)
