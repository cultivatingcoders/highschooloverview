# Week 1 - HTML / CSS
## Project: Personal Site
* Intro to HTML.  Create a basic website, no css, talks about themselves, they're interests, etc.  (learn how to use the p, ul, li, and header tags)
* Intro to CSS.  Learn about how to style things by focusing on text attributes first.  Then, learn about divs (spans?) and how they can come in handy.  Honestly on the fence about if we should explain the box model, and how we should explain it.
* More HTML.  Introduce them to img tags.  Show them how to use a form.  If you haven't talked about classes yet, do that now.
* Basically teach them how to build a personal site for themselves with a home page, about, and a contact over the next two days.
* Homework: Install p5 over the weekend, watch some p5 videos from Daniel Shiffman, keep working on that personal website.

# Week 2 - JS Part 1
## Project: Tic-Tac-Toe and PONG.
* Intro to JS.  Setup a webpage that uses javascript and do the usual "Hello World" program using console.log.  Then show them how to do the same thing using a variable and two console.logs (change the var after first log).  Then show them the other datatypes that they can work with along with some basic arithmetic (don't really talk about booleans yet, too confusing).
* Intro to functions / p5.  I've learned from personal experience that students learn best visually, so introduce p5, bring up what a code library is, show how to include p5 along with their code.  Introduce the concept of functions at this time since p5 is very function intensive, show them how to write their own functions (such as a function that combines geometry primitives from p5 to make something interesting, like a cat, a car, a whatever).  It's also a good time to introduce event listeners at this point since p5 provides this really nice function for handling mouse clicks.
* If statements.  Show students how to use if statements.  Start with the basics, work your way up to more complex examples, introduce comparison operators, AND and OR, wrap up with a complex if statement that uses a combination of AND and OR.  Great way to talk about if statements in p5 is to make a bouncing ball.
* While / For.  Bring up a while loop first (I've noticed while loops are a controversial topic, but they translate well from if statements and make it easier to make the leap towards a for loop).  Use while and random to generate a bunch of randomly placed geometries.  Then do the same using a for, taking great care to explain the difference.
* DOM.  Take a break from p5 for a while to show how they can apply all that they've learned to DOM manipulation.  Show them how to manipulate already existing elements, how to create new ones (including a lot of new ones using the for loop), etc.  At this point they'll be eager to see how all they've learned ties into HTML / CSS.  Additionally, we'll be using a lot of dot accessors, which will provide a great segue into objects next week.
* Homework: Help me out here.

# Week 3 - JS Part 2
## Project: NASA NEO
* Objects.  Last week they'll have been exposed to a lot of dot accessors due to all the dom manipulation, so now is a good time to talk about objects.  Start by talking about very basic objects in js (i.e. an object with some attrs and methods).  Make a simple object that extends from another one.  Don't get too crazy with objects though, they're confusing.
* Arrays.  Introduce what an array is, how it's useful, how to traverse through one, etc.  Great way to talk about arrays is to use one to manage a bunch of randomly placed "bubbles" in p5.
* Algorithms.  Now that they know what an array is, now might be a great time to talk about basic sorting algorithms.  You might want to go back to p5 for this one, since it's more intuitive to understand how sorting algos work when you can see them in action.
* AJAX requests. This is a great way to wrap up the week before switching gears and talking about Node, since we'll be introducing GET requests and thus http protocols and backend dev.  Use NASA's NEO API to collect data about near earth objects and put them into a web page.  While we're at it, this is a great opportunity to introduce Bootstrap.
* Homework: continue working on NEO app, install cmder, practice command line with a set of exercises (how to cd, ls, etc)

# Week 4 - Intro to Node
## Project: Fumblr (?) (It's a blog, but it's also kinda like tumblr, which apparently is still cool among high school kids)
* Install node, setup a very simple "hello world" node server that renders a "hello world" page when you visit a route.  They're going to ask questions about how this is different from what they've already learned (besides being harder) so we'll want to have an example app handy that we can demonstrate does something new that only backend can do (or at least, that backend does better than frontend).
* Introduce Git version control.  We've had a hard time teaching effective git in the past, so this will require some thought.  Ideally I'd *really* like to teach how to do effective branching.
* Install Express, which is a great time to talk about packages. Tack on some new routes to serve more pages.  Add some pages that use POST requests to send data to the server, but don't actually save said data.
* Install MySQL and Sequelize, talk about databases.  Go ahead and try saving data.  Disclaimer: in the past we've used XAMPP A LOT.  We tried using Vagrant, didn't go too well.  I'd like to use Vagrant again since that's my preferred way of dealing with trying to run MySQL on, well, anything, but we'd have to make sure it goes really smoothly.

# Week 5 - More Node
## Project: SnapCat (Snapchat for Cats) (Just build a hypothetical API backend for snapchat)
* This time we'll basically re-hash over a lot of what we covered last time, but in the context of an API backend as opposed to a server that serves up fully-rendered HTML.
* As they're building the app, we'll give them a mostly finished frontend that requests data from the server and then parses it into content.

# Week 6 - Frontend Tools Overview + Community Projects
* So, around this point we want to start giving them more time to fully focus on community projects and personal websites.  We basically want to start winding down lecture.
* This week, start talking about some of the more advanced frontend tools out there, with a focus on either Vue or React (Angular + Ember are too Rails-ish, have too high of a learning curve, but they still merit a discussion).
Whichever we pick, show how particular example is useful by building a single page app that really relies on state management.

# Week 7 & 8 - Community Projects & Personal Sites
* At this point, instructors and assistants should help out students with their projects and any questions they have.  Basically, no more lecture.
* Maybe introduce some agile (kanban?) to show them how to keep things managed.
