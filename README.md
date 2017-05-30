## Front Trends 2017
### May 24 - 26, Warsaw
Notes on [Front-Trends 2017](https://2017.front-trends.com/).

![ft](http://i.imgur.com/gHkhVy3.jpg)

**Day 1, May 24th**
1. [Maciej Ceglowski (Yahoo, Twitter, Otworz ksiązke): Legends of the Ancient Web](#maciej) - *Past and future of the Web*
2. [Una Kravets (Digital Ocean): The Power of CSS](#una) - *CSS*
3. [Vitaly Friedman (Smashing Magazine): Smashing Magazine’s 2017 Relaunch](#vitaly) - *Responsive design/HTML, CSS, UX*
4. [Sam Bellen (Madewithlove): I didn't know the browser could do that!](#sam) - *Browsers APIs*
5. [Adam Morse (compositor.io): The past and future of designing interfaces](#adam) - *CSS*
6. [Marco Cedaro (Shazam, Kahoot, Crowdcube): Components, patterns and shit it’s hard to deal with](#marco) - *Patterns*
7. [Stefan Judis (Contentful): Watch your back, Browser! You're being observed.](#stefan) - *Browser APIs*
8. [Ally Long (freelancer): Field-tested interfaces for the next billion](#ally) - *UX*
9. [Niels Leenheer (HTML5Test.com): Monsters, mailboxes and other nonsense](#niels) - *IoT*

**Day 2, May 25th**
1. [Patrick Hamann (Fastly, The Guardian, Financial Times): The First Meaningful Paint](#patrick) - *Performance*
2. [Zoe Mickley Gillenwater (Booking.com): Experimenting your way to a better product](#zoe) - *A/B testing*
3. [Vadim Makeev (HTML5Academy): I'm in IoT](#vadim) - *APIs, Bluetooth & IoT*
4. [Val Head (lynda.com, web design day conference): Motion In Design Systems: Animation, Style Guides, and the Design Process](#val) - *Animations*
5. [Kirupa Chinnathambi (Microsoft, kirupa.com): Building a Progressive Web App](#kirupa) - *PWAs*
6. [Lin Clark (Mozilla): A Cartoon Intro to React Fiber](#lin) - *React*
7. [Jack Franklin (Songkick): The How, What and Why of migrating to ReactJS](#jack) - *React*
8. [Mihai Cernusca (Gifshop): Prevent Default — The future of authoring tools](#mihai) - *UX, mark-up, future of the web*

**Day 3, May 26th**
1. [Konrad Dzwinel (Brainly, Google Developer Expert): Alternative Reality DevTools](#konrad) - *Devtools*
2. [Martin Splitt (Archilogic):  Rendering performance inside out](#martin) - *Performance*
3. [Ida Aalen (freelancer): Easy and affordable user-testing](#ida) - *UX, testing*
4. [Ola Gasidło (Mozilla): Let's save the internet: How to make browsers compatible with the web](#ola) - *Browsers*
5. [Jenna Zeigen (Digital Ocean): On How Your Brain is Conspiring Against You Making Good Software](#jenna) - *Human factor*
6. [Chris Wright (Campaign Monitor): Changing the layout game HTML](#chris) - *CSS*
7. [Rosie Campbel (BBC Technologist): Demystifying Deep Neural Networks](#rosie) - *Machine learning, Neural Networks*
8. [Phil Hawksworth (R/GA): Microservices - The FAAS and the Furious](#phil) - *Microservices*

<a name="maciej"></a>
# Maciej Ceglowski (Yahoo, Twitter, Otworz ksiązke): Legends of the Ancient Web
Presentation about past and future of the web. Maciej said that web is like vicious circle: what has been will be again. In the last couple of years, frontend development has become very complex: there are lots of technologies and frameworks to master. Computers move fast. It's happened before, and will happen again.

There was few information about radio history, because like internet now radio brought people closer.

Technology and human nature interact in interesting ways. It is very possible the things we build may be used for bad later on. This is a threat, and we need to take it seriously.

What you're working on, who you are working for matters. It's not about frameworks and libraries, it's about direction the internet is going. We need to from history of radio and how it was used for evil and try not to repeat those mistakes.

<a name="una"></a>
# Una Kravets (Digital Ocean): The Power of CSS

We can make many Photoshop look-like effects just using css. Una showed us 10 effects written in css: modals, lightboxes, tooltips, scroll indicators, carousels ect...
They don't need JS. You can have the same results using target, data attributes, siblings- and pseudo-selectors.

http://youmightnotneedjs.com/

<a name="vitaly"></a>
# Vitaly Friedman (Smashing Magazine): Smashing Magazine’s 2017 Relaunch

Case study of Smashing Magazine (SM) redesigning. SM was losing lots of revenue because of ad-blocking. Now, they've replaced membership for ad revenue, brought more focus to their paid products (books).

We're too tied in to media queries. Defining the scope of breakpoints is almost impossible considering the huge amounts of devices and viewport sizes possible. You can't be sure your media queries cover everything. Avoid them as much as possible in the design process.

Use:
- rem for root component
- em for sub parts

To good adjustment of font sizes they used calc() css function - fluid sizing.

<a name="sam"></a>
# Sam Bellen (Madewithlove): I didn't know the browser could do that!

APIs supported in Chrome and partialy in other browsers.

- Speech API (speech recognition)
- Geolocation API
- Notification API
- Push API
- Battery Manager API
- Media Recorder API
- tracking.js - snapchat filters

Sam builded his own small cat-siri.


![sam](http://i.imgur.com/wQX5hEZ.jpg)

<a name="adam"></a>
# Adam Morse (compositor.io): The past and future of designing interfaces

Very hard to summarize. General presentation about programming, not about something specific.

Humans tend to make a lot of mistakes when working with data. We are not good at it.  A possible line of defense is modularity: breaking down a complex thing into understandable things might just help us avoid errors.

A simple component can have thousands of states. And that's what computers should be for: see these states. That's not a human task. Seeing and testing all possible states of components would make any developer's life easier.

"People want to do, people don't want to learn how to do"

"Find your people, dream big, start a revolution"

<a name="marco"></a>
# Marco Cedaro (Shazam, Kahoot, Crowdcube): Components, patterns and sh*t it’s hard to deal with

Patterns came really late into web development. Generally, everything we are doing now (patterns, components, modules), we are doing for improving maintainability of the code. Find the way to re-use your patterns, think about what problem you are trying to solve. Get involved early, talk to people (designers, product managers, not just devs).

<a name="stefan"></a>
# Stefan Judis (Contentful): Watch your back, Browser! You're being observed.
Now to increase performance we can use Browser API, especially observables. Try to find what performs bad and find better way eg. getBoundingClientRect() -> Intersection Observer

Check out:
* https://developer.mozilla.org/en-US/docs/Web/API/MutationObserver
* https://developer.mozilla.org/en-US/docs/Web/API/Intersection_Observer_API
* https://developer.mozilla.org/en-US/docs/Web/API/Navigation_timing_API
* https://developer.mozilla.org/en-US/docs/Web/API/Resource_Timing_API
* https://developer.mozilla.org/en-US/docs/Web/API/User_Timing_API
* https://developer.mozilla.org/en-US/docs/Web/API/PerformanceObserver

<a name="niels"></a>
# Niels Leenheer (HTML5Test.com): Monsters, mailboxes and other nonsense

IoT

Hacked neighbours via bluetooth, build water supply for his chickens working via bluetooth.

![niels](http://i.imgur.com/UE5k0bo.png)

<a name="ally"></a>
# Ally Long (freelancer): Field-tested interfaces for the next billion

Next bilion = Those who have no internet connection yet, like sub-saharan Africa.

- low-end android devices
- very poor internet connection
- scratched screens	
- currently opera mini is the best choice
- lack of power source
- people turn their phones off all the time
- touch screens > laptops
- under viewport - not discoverable
- big and simple buttons, obvious actions
- do not use forms, keep it page-by-page
- everything is gonna be clicked
- animations are a bad idea
- borrow from well-known apps. Facebook, What's App, Gmail already made it there.

<a name="patrick"></a>
# Patrick Hamann (Fastly, The Guardian, Financial Times): The First Meaningful Paint

The First Meaningful Paint - new metrics, time when a page's primary content appeared on the screen and web fonts have loaded 

https://developers.google.com/web/tools/lighthouse/audits/first-meaningful-paint

How to optimize:
- Inline critical css - css cannot be parsed incrementally like HTML, until css is loaded we will see white page even though html is already rendered. Inlining critical parts of css can improve rendering (first meaningfull paint) significantly - unfortunately not cachable
- Preload api - heavy resources: logos, images, fonts
- HTTP/2 server push - send resources before server requests for them - requires server logic
- Async push

https://www.webpagetest.org/

<a name="zoe"></a>
# Zoe Mickley Gillenwater (Booking.com): Experimenting your way to a better product

A/B testing - user decides

Booking.com process:
1. Make observations, gather ideas
2. User center hypothesis: why, what, who, outcome? 
* Why you want to make a change?
* What is wrong with the current state? What problem are you trying to solve, and what evidence do you have that this is a problem? 
* Who is going to be exposed to this change? 
* How are you going to track these people? And what do you expect to happen, how do you measure success and failure? What metrics will you be using? The metric is NOT the goal: it is the measurement of the goal.
3. Create tests. Start with the smallest change possible.
4. Plan the test time (week, month)
5. Do the test. Keep eye on metrics(results)
6. Accept/reject the hypothesis.

Don't test the same thing over and over again.
Don't cherry-pick metrics after running the experiment.
Don't A/B test if you don't have enough data.


<a name="vadim"></a>
# Vadim Makeev (HTML5Academy): I'm in IoT

Another very funny talk about IoT. The drone has been hacked and captured by one attendee.

![vadim](http://i.imgur.com/PNxCyrT.jpg)

<a name="val"></a>
# Val Head (lynda.com, web design day conference): Motion In Design Systems: Animation, Style Guides, and the Design Process

Plan animations before with whole team: developers, designers, product owners. The better the communication is between the two, the better your animations will be. You'll be able to create re-usable patterns instead of re-inventing the wheel every time there's a new animation.

1. Sketch animation. Meaning matters. Find the trigger of the animation (page load or user gesture)
3. Motion 
4. Interactive prototypes

<a name="kirupa"></a>
# Kirupa Chinnathambi (Microsoft, kirupa.com): Building a Progressive Web App

PWA contains:
1. Web app
2. JSON manifest
3. Service workers

![kirupa](http://i.imgur.com/Q8SMbka.jpg)

PWAs go beyond the browser. They have a life outside of the browser. They blur the line between web apps and native apps. 

1. PWAs are just web apps thay provide a great user experience.
2. Use progressive enhancement so everyone can use them.
3. PWAs work great both inside and outside the browser.
4. Sometimes they're the right solution, sometimes not, and that's okay.
5. Have fun!

Check out:
* https://ionicframework.com/
* http://www.pwabuilder.com/
* https://github.com/jeffposnick/create-react-pwa
* https://developer.mozilla.org/en-US/docs/Web/API/Service_Worker_API
* https://www.pwastats.com/

<a name="lin"></a>
# Lin Clark (Mozilla): A Cartoon Intro to React Fiber

React Fiber improves performance and responsiveness of complex React applications.

<a name="jack"></a>
# Jack Franklin (Songkick): The How, What and Why of migrating to ReactJS
How to move from Angular to React and still maintain the product?

![jack](http://i.imgur.com/x8EnmBL.jpg)

Release early and often, one bit by a time.

Learn as migrate and get better at it.

Don't break existing functionality.

https://github.com/ngReact/ngReact

https://www.sitepoint.com/test-react-components-jest/

<a name="mihai"></a>
# Mihai Cernusca (Gifshop): Prevent Default — The future of authoring tools

The history of authoring tools, starting from Macintosh text editor, through MS Word and ending with Google Documents.

<a name="konrad"></a>
# Konrad Dzwinel (Brainly, Google Developer Expert): Alternative Reality DevTools

The history of the Dev Tools. It started from seperate application. Mozilla was first who attached devtools to browser. Now every browser has very powerfull DevTool. 

Konrad did a step forward and present us his ideas about what could add more value to modern web browsers. He did a small research in other industries like architecture (autocad), integrated circuts design (LabView), movie production to inspire and found few things:
1. Graphics elements preview (eg. svg)
2. Component debugger (to debug seperate element without rendering whole page)
3. Timeline of rendering (what customer see eg. after 2 seconds)
4. Infinite canvas (debug many devices within same screen)

![konrad](http://i.imgur.com/YViWjZy.jpg)

<a name="martin"></a>
# Martin Splitt (Archilogic):  Rendering performance inside out

Pixels are the smallest possible graphic unit, and it's technically a small box which we can color in by making 3 tinier dots inside it in three colours: red, green, blue. They are independent.

* 0: lowest intensity
* 255: highest (brightest)

Sprites(layers) are arrays of pixels. We can manipulate them using math functions:
* output[x, y] = source[x, y] || dest[x, y]
* Screen blend mode: color(x, y) = 1 - (1 - color(x, y)) * (1 - color(x, y))
* Translate (move): source[x + a, y +b] + dest[x, y]
* Rotate, translate, scaling, blending and filters are all composites (no browser repainiting)

Composite-only filters:
* grayscale
* blur
* contrast
* hue-rotate
* invert
* opacity
* saturate
* sepia
* drop-shadow (repaints in Safari)

Pixels are just a bunch of numbers in memory. Useful to be separate them in layers. Compositing is combining these layers, and blending is how exactly we combine them. Compositing can be done concurrently, because pixels are independent of each other.

Performance is the art of avoiding work (Paul Lewis). The more work avoided, the faster we can render.

`will-change` only works if the element isn't in the layout flow!

* https://csstriggers.com/

![martin](http://i.imgur.com/ya2Plxi.jpg)

<a name="ida"></a>
# Ida Aalen (freelancer): Easy and affordable user-testing

1. Hit the streets(take snacks for testers).
2. Information architecture (set up a survey about your information architecture and ask people what do they think).
3. First click
4. Prototype meets actual user(link to prototype instead of current version of website)
5. Did you get it done? Did user found what he/she was looking for?
6. Microtesting content
7. Weakly drop-in test: in lab/office.

<a name="ola"></a>
# Ola Gasidło (Mozilla): Let's save the internet: How to make browsers compatible with the web

Report browser bugs! http://webcompat.com/

Browser wars:
* 1st Browser War: 1995-2002, IE vs Netscape
* 2nd Browser War: 2003-2014, Opera vs Safari vs Firefox vs Chrome

Participate in improving specification, report bugs!

<a name="jenna"></a>
# Jenna Zeigen (Digital Ocean): On How Your Brain is Conspiring Against You Making Good Software

* We do not think logically, we prefer workaround rather than better but more time consuming solution
* We have problems with thinking outside the box, approach different point of view -> pair programming, taking breakes
* We are terrible at estimating (we overestimate)
* We prefer things that we made
* Unskilled people think they are better at tasks than thet actually are.
* Skilled people underestimate their abilities and think that tasks which are easy for them are easy for others


![jenna](http://i.imgur.com/niMzE90.jpg)

<a name="chris"></a>
# Chris Wright (Campaign Monitor): Changing the layout game HTML

Layout is the most hacked area on the web. 
There was tables and floats, media queries, maybe now it is time for grid?
https://www.w3.org/TR/css3-grid-layout/

<a name="rosie"></a>
# Rosie Campbel (BBC Technologist): Demystifying Deep Neural Networks

Conventional computing - many ifs.

Neutral networks are good at things human are good at (eg. pattern matching) bad at thing computer are good at (maths).

Single neutron - many requirents and wages, eg:

Should I go to the festival?
* weather 	(importance)
* music 	(importance)
* company 	(importance) 	>  0 = > Activation function -> output
* money 	(importance)
* Bias   

Train the network, change the function, repeat

* They are just a machines, neither infallible nor objective
* The network sees what is trained to see
* Humans are creating their own biases
* Networks can inadvertently learn proxies and correlations instead of real insight
* Can produce racist, sexist and other irrational results  

Check out:
* Tensor Flow, opensource google python library - many inbuilt functions to deal with tricky maths, good documentation and a lot of tutorials

<a name="phil"></a>
# Phil Hawksworth (R/GA): Microservices - The FAAS and the Furious

Complexicity can be barrier, simplicity can be enabler. Unfortunately, simplicity is hard to achieve. Let's talk about offloading complexity. Websites used to be collections of static assets. These days, we have to deal with views, routing, app logic, databases, caching, load balancing, CDNs, etc. There are a lot of moving parts that cannot be maintained by just one person.

Static page despite of opinions can have:
* site search 
* forms
* comments
* content management

Stack: JAM - Javascript, APIs, Markup.
* Storing data in outer service
* Hosting only one function (FaaS - function as a service)
* IFTTT webhooks for new twitter posts

![phil](http://i.imgur.com/5l6I5YJ.jpg)




