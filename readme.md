![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png)

# NodeJS

### Why is this important?
<!-- framing the "why" in big-picture/real world examples -->
*This workshop is important because:*

JavaScript has been a computer language exclusive to the browser; that is, until Node was developed. Using Node's environment, we can use JavaScript as a general purpose language for any computer process.

### What are the objectives?
<!-- specific/measurable goal for students to achieve -->
*After this workshop, developers will be able to:*

* Explain what Node is & why it exists
* Compare and contrast Node's API with the DOM's API
* Spin up a simple web server using node
* Use organize code into modules and require it where necessary

### Where should we be now?
<!-- call out the skills that are prerequisites -->
*Before this workshop, developers should already be able to:*

* Navigate the terminal
* Have a proficiency in JavaScript

## What is Node?

The makers of Node took javascript (which normally only runs in the browser) and made it available in your computer (on the server side). They took Google's V8 JavaScript Engine and gave it the ability to compile JS programs into machine code.

####Ryan Dahl

* Creator Ryan Dahl [demonstrating Node](https://www.youtube.com/watch?v=jo_B4LTHi3I).

####The Event Loop

![node event loop](http://i.stack.imgur.com/BTm1H.png)

Node really shines when it comes to heavy input-output type operations. This doesn't mean that other languages aren't capable of the same thing, it's just that by using the **Event Loop** *Node is "non-blocking" by default*.

>**Blocking**

>Imagine a paper delivery boy riding on his bike delivering papers every morning. Imagine he stops at each house, throws the paper on your doorstep, and waits to make sure you come out & pick it up before moving on to the next house. That would be what we'd call _blocking_ – each line of code finishes before moving on to the next line of code.

>**Non-blocking**

>Now, imagine the paperboy throwing the newspaper on your porch but never stopping his bicycle; 
never stopping, he just keeps throwing papers on porches, so that by the time you pick it up he'll be 3 or 4 houses down. That would be _non-blocking_, or _asynchronous_.


#### Installing Node

To check if we already have Node installed, type: ``node -v`` in terminal. If not, install it now preferably using `brew` or `apt-get` depending on your operating system.

#### Executing a JS program

Write and execute some code in a file! In your working directory:

```bash
mkdir first-node
cd first-node
touch main.js
echo "console.log('hello world!');" >> main.js
node main.js
# hello world!
```

## Node's API Intro

* [Node's API](https://nodejs.org/api/)

## File I/O

* [](http://blog.modulus.io/absolute-beginners-guide-to-nodejs) (fs section)

## HTTP Server

* [](http://blog.modulus.io/build-your-first-http-server-in-nodejs)

## Code Organization

* (Split out `handleRequests` into seperate file)
* (Challenge: do this with another function...)

## npm

NPM stands for Node Package Manager, and is a tool that allows us to easily download community-built Node packages.
Initialize new Node project with NPM: npm init.
Install NPM packages: npm install --save express.
NPM works with package.json, which is a list of project information and dependencies that can be installed on other computers and servers.

## Node's API Self-Exploration

<!--

ACTIVITY: Developer's vote on the parts of the API that seem most interesting. We split up the class into groups to do research (10m) on each and teach the rest of the class (5m) what they learned

-->

* [Node's API](https://nodejs.org/api/)


## Closing Thoughts
<!--
- review objectives & hierarchy of importance
- look ahead & link to future workshops
- clarify expectations and what developers should know by now
- reiterate “the why” with a perspective of your intentions
- create an active recall
- Check for understanding
-->
## Additional Resources

...