### Programming for Non-Programmers Notes 

##### January 30-February 1st 2015

Hsi-Chang Lin, 
<br /> 
Interactive Developer, Now This
<br /> 
Follow @hsichang

Goals: 

Day 1: Intro

* deeper understanding of HTML
* vocabulary 
* the basics of code

Day 2: Front-End

* HTML/CSS
* Create your own website

Day 3: Back-End

* ruby/rails
* basic blog
* web application

Stages of web development:

* design
* UX
* info architecture


### Section 1: How the Web Works

* Series of tubes-Ted Stevens
* **http://** = stands for (hyper text transfer protocol) use in our URL browsers
* **Host** (www is a mask for an address ie. www.nytimes.com) corresponds to a computer w/ an IP address (server)
* really get back to server is really 3 docs: HTML(hyper text markup language), CSS, Javascript

#### Rendering in the Browser

* each browser has its own rendering engine to interperet and display the markup
* IE, firefox, sarafi, opera, chrome
* [latest browser stats](http://en.wikipedia.org/wiki/Usage_share_of_web_browsers)

#### Two Ways of Responding

1. Hardcoded-static doc
2. Dynamic-html>server>program that generates HTML on the server


### Section 2: Front-End vs. Back-End
comparison: think of a resaturant. Front end what the consumers see. Backend end the kitchen staff, coookware, etc

##### Front-End languages

* HTML (sturcture)
* CSS (style)
* Javascript (behavior)


##### Back-End languages

* ruby (language of the day)
* python
* php
* javascript

##### Back-End frameworks

* ruby on rails (for ruby)
* django (for python)
* node + express (for javascript)

##### New Open Source Javascript Front-End Frameworks

* Amber.js
* Angular.js (this is one instructor uses)
* Meteor.js (very new)
* D3js [creator Mike Bostock](http://bost.ocks.org/mike/)
* React.js



### Section 3: What is Programming:

* the preparation of an expected outcome to follow a series of planned, or controlled events
* series of solutions 
> "Everyone should learn how to program a computer because it teaches you how to think." *-Steve Jobs*

**Excercise:** Write step-by-step instructions for how to bake a cake. Think in terms of variables, classifying ingredients, loops, and functions.

##### Why do many programming languages? 

First language is like latin...you can learn other langages...some things are implicit to certain lanagues.  
i.e. German words like zeigtgeist, shadenfraude are not translatable in one word in other langugages.

##### Compiled vs. Interpreted languages 
* ruby is interpreted
* java (not javascript) is compiled i.e. operating at the machine code level (0 and 1s)


####What do programs actually do?
They automate things to make our lives easier.

* mark things up (HTML/CSS)
* keeping track of things (variables)
* making decisions (if>then)
* repeating things (loops)
* displaying things
* logs things (log files)
* storing things (databases)

Coding idiom: Keep it dry (means don't repeat yourself)

#### What can I build?

* websites (static)
* web applications (processes/servers data)
* native apps
* other things

### Section 4: Web Developemnt

##### Who makes the web?

* web designer
* web developer (back end developer)
* front end developer (front end engineer)
* full stack developer (float between front and back end)
* dev ops (liason between IT, database, server processes, very technical job)
* ux designer (user experience...researh how people use the website.)
* ui designer (user interactive...dealing with the interfaces. Testing out aesthetic of website. Design with photoshop/illustrator.)
* interaction designer
* product manager
* SEO specialist

#### Stages of Web Development
* design
* develop
* test

#### Create a User Story
Answer these three questions:

* I as a (role at company)
* I want to (goal)
* in order to (benefit)

#### Project Management Systems:

* Asana (good storage)
* Pivotal Tracker
* Basecamp


#### Question your team need to be asking:

* who are our users? (audience)
* what are their goals? (interface)
* why do they suport us? (purpose)
* what aretheir habits?
* when are they visiting?
* what do we need to do in order to make this happen more often?


#### Design Steps

##### 1. User Experience (UX)

Compare and contrast: [nytimes.com](http://www.nytimes.com/) vs. [buzzfeed](http://www.buzzfeed.com/)

NYT: text, classic, hierachy of concerns, organized, b&w

Buzzfeed: visual, busy, no hierarchy, colorful

##### 2. Information Architecture (IA)

* blueprints for the site
* flow charts
* pre-wireframes (use thumnails. Focus on idea generation. Can be hand written. Basic shapes don't spend too long)
* wireframes. 
* * To see other sites wireframes: [Instant Wireframe](https://chrome.google.com/webstore/search/wireframe)
and [Wirify](http://www.wirify.com/)
* * [wireframe.cc](https://wireframe.cc/) allows you to build and share wireframes


#### Methodology for Stucturing a Team:

**Waterfall**

* Strict parameters of success, features, deadline.
* one chance to get produce tirght
* less opportunity for feedback
* less communication btwn different groups
* following a plan

**Agile**

* allows you to pivot
* many changes to get the product right
* more opportunity for feedback
* more communication between groups
* responding to change

Daily stand up meetings: what you plan to accomplish today, what you need help with, what is being delayed.


#### Should I use an API? 
API stands for Application Programming Interface. Grants one computer access to another computers database. 


#### Version Control

* keep track of the version of code
* collaborate with others.
* keep track of who contributed.
* Open-source (release it to the world for free!)
* Popular tools: Github, BitBucket


**Excercise:** 

1. Go to Google Chrome
2. Open Up Chrome Dev Tools (control, command, i)
3. Setup Screen As Pictured 


####DOM (Document Object Model)

* parent
* child
* sibling
* same tag, different parts of the tree
* HTML, XHTML

###Day 2

####Sections

1. Setup Your Dev Environment
2. Coding HTML-the basic
3. Adding Style to Our Structure
4. UX Tips
5. Build Your Own Site

####Setup Your Dev Environment

* text editor (sublime text)
* file transfer client
* terminal 

[Getting started with sublime text 3:25 tips, tricks and shortcuts](https://blog.generalassemb.ly/sublime-text-3-tips-tricks-shortcuts/)


####Syntax Highlighting

In Sublime Text

* preferences-color scheme-monokai
* view -syntax-html

File Transfer Client: [cyberduck](https://cyberduck.io/)

Cyberduck is an open source client for FTP and SFTP, WebDAV, OpenStack Swift, and Amazon S3, available for Mac OS X and Windows (as of version 4.0) licensed under the GPL. Cyberduck is written in Java and C# using the Cocoa user interface framework on OS X and Windows Forms on Windows.

Terminal: [iterm2](www.iterm2.com) 


[Ruler](http://www.pascal.com/software/freeruler/) download to make sure site is pixel perfect.


####Starting with a fresh template

* open cyberduck
* go to the directory
* in the class-assets directory, download the html-template zip
* unzip the folder and rename the folder from html template to 'sandbox'


**Alternatives to lorem ipsum**

* [tupaccsum](http://www.rodrigo-silveira.com/tupacsum/)
* [Hipster Ipsum](http://hipsum.co/)

**Photo generators**

* [Photo Kitten](https://placekitten.com/)

Commenting Out Using HTML
<!--link directly to google -->
<!--<aref>-->

**File extensions**

* png=not lossy, transparency
* jpeg=lossy, no transparency
* gif=animated

**links**

* <a href="http://google.com">Google</a>
* Using "target=blank" Opens new window/tab <a href="http://google.com"target=blank>Link 2</a></li>

**Excercise:** [Travel Website](http://67.207.129.100/pfnp-nyc/jan-2015/kcowser/travel_student/)
  
#####Section 3

#####Adding Style with CSS (Cascading Style Sheets)

**Selectors**

* selector{
property: value; 
property: value; 
}

* body{color:yellow

**Types of Selectors**

* elements
* id
* class
* position in document

**IDs & Classes**
Ex: <p id="polite"class="greeting">"hello!"</p>
<p class="greeting">Sup!</p>

* ID = use once (indetifiable via hashtags #)
* class=infinity

**Properties**
Types of properties
eg: 

* color
* background color
* font family 

**colors**

* name (red, yellow, green, blue, black, etc)
* * There are 147 different "names"
* hexadecimal (#FF0000)

* rgb and rgba(red, green, blue) A means opacity
* * rgb (100, 86, 92)
* * rgba (100, 86, 92, .05)

**Fonts**

* font style, font-weight, font-size, font-color, font-family

**Box Model**

* content
* padding
* border
* margin

**HTML/CSS**
code-along portfolio page


####Day 3

* modern UX and UI principles
* why does my web app need a back-end?
* programming concepts using ruby
* web frameworks using ruby on rails
* databases, servers, and tourings
* Hello World...on rails.


* Q: What is the root URL for any web directory. A: index.html (this is often hidden in the URL)
* Q: What is a div? margins, border, padding, content. 
* Q: What is an inline element? How does it differ from an outline element. 

Cyberduck is an open source FTP client. 

What does WYSIWG mean? What You See Is What You Get. Squarespace and Wordpress are WSIWGs. 

#####UI

[**Google Material Design**](http://www.google.com/design/) (living document. It's continually changing.) 

* A design lanaguage developed by Google with increased use of grid-based layouts, responsive animations, and transitions, padding, and depth effects such as lighting and shadows.
* based on paper and pen
* material has physical surfaces and edges
* seams and shadows provide meaning about what you can touch

[**Google fonts**](https://www.google.com/fonts)

* google suggests using Roboto
* You can download form teh materical designs webpage or use it direclty from Google Fonts webpage

**Contrast**

* space and contrast are key to any good design.
* a great example is text, consider contrasting serif fonts for the header, and large clar sans-serif fonts for the body.

[Medium] (https://medium.com/ideo-stories/how-to-design-a-business-4-lessons-from-startups-efdcf0c622ff)

[Google Design](http://www.google.com/design/spec/components/cards.html)







