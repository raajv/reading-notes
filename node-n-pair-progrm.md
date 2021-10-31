An Introduction to Node.js on sitepoint.com
	What is node.js?

Node.js is an event-based, non-blocking, asynchronous I/O runtime that uses Google’s V8 JavaScript engine and libuv library

This means that Node.js is a program we can use to execute JavaScript on our computers. In other words, it’s a JavaScript runtime.

	In your own words, what is Chrome’s V8 JavaScript Engine?It is an open source JS engine that runs on chromium based web browsers


	What does it mean that node is a JavaScript runtime?
It means that you can use node to execute js on our computers


#	What is npm?

As I mentioned earlier, Node comes bundled with a package manager called npm. To check which version you have installed on your system In addition to being the package manager for JavaScript, npm is also the world’s largest software registry. There are over 1,000,000 packages of JavaScript code available to download, 

# What version of node are you running on your machine?
	We can check by using npm -v

#	What command would you type to install a library/package called ‘jshint’?

Open your terminal and type the following:
npm install -g jshint
This will install the jshint package globally on your system. We can use it to lint the index.js file from the previous example:
jshint index.js
You should now see a number of ES6-related errors. If you want to fix them up, add /* jshint esversion: 6 */ to the top of the index.js file, re-run the command and linting should pass.

If you’d like a refresher on linting, see A Comparison of JavaScript Linting Tools.

#	What is node used for?

Now that we know what Node and npm are and how to install them, we can turn our attention to the first of their common uses: installing (via npm) and running (via Node) various build tools — designed to automate the process of developing a modern JavaScript application.
These build tools come in all shapes and sizes, and you won’t get far in a modern JavaScript landscape without bumping into them. They can be used for anything from bundling your JavaScript files and dependencies into static assets, to running tests, or automatic code linting and style checking

ref - https://www.sitepoint.com/an-introduction-to-node-js/


# 	What are the 6 reasons for pair programming?

Greater Efficiency
Engaged collaboration
Learning from fellow students
Social skills
Work environment readiness
Job interview readiness

#	In your experience, which of these reasons have you found most beneficial?

Learning from fellow students. , I found this the most useful atm as knowledge is shared and we come out with solutions which I wouldn’t have by myself
	
# How does pair programming work?

While there are many different styles, pair programming commonly involves two roles: the Driver and the Navigator. The Driver is the programmer who is typing and the only one whose hands are on the keyboard. Handling the “mechanics” of coding, the Driver manages the text editor, switching files, version control, and—of course writing—code. The Navigator uses their words to guide the Driver but does not provide any direct input to the computer. The Navigator thinks about the big picture, what comes next, how an algorithm might be converted in to code, while scanning for typos or bugs. The Navigator might also utilize their computer as a second screen to look up solutions and documentation, but should not be writing any code.

https://www.codefellows.org/blog/6-reasons-for-pair-programming/
