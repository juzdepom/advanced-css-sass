# Advanced CSS and SASS

by [@codebreakerjulia](https://www.instagram.com/codebreakerjulia/)

<a href="https://www.udemy.com/advanced-css-and-sass/" target="_blank">![course](/assets/course.png)</a>

## All Sessions
* [Session 8](#session-8) - Lecture 58-XX
* [Session 7](#session-7) - Lecture 54-57
* [Session 6](#session-6) - Lecture 41-53
* [Session 5](#session-5) - Lecture 40
* [Session 4](#session-4) - Lecture 38-39
* [Session 3](#session-3) - Lecture 34-37
* [Session 2](#session-2) - Lecture 8-33
* [Session 1](#session-1) - Lecture 1-7

## Tips & Tricks

### Sass
* How to get Sass compiling locally: ```npm run compile:sass``` (check package.json)
* Sometimes, when Sass isn't compiling, you need to randomly press Command + S on a different file (even if the file is already saved) to trigger the compile🤷🏻‍♀️

### GIF reqs
Convert to GIF [here](https://ezgif.com/optimize)
* Optimize by 200
* Reduce size to 40% of original

## Session 8 – [🔝](#all-sessions)
*🗓 Th, Nov 27, 2018* <br>
*💬Lectures: 58-63* <br>
*🕐 4:20am-6:45am (2h25)* <br>
*📍Home* <br>

* ⏰ Total Lecture Time: XXmin<br>
* ⏰ Total Lecture Time: 80min = 1h20min<br>

* ✅ (13 min - Lec 58) Writing Media Queries – Layout, About and Features Sections<br>
<!-- 5 min break -->
* ✅ (21 min - Lec 59) Writing Media Queries - Tours, Stories and Booking Sections<br>
Go to [www.sizzy.com](www.sizzy.com) to enter your URL to test your display across different screen sizes 🔥 Challenge in this lecture: make the popup responsive.

* ✅ (6 min - Lec 60) An Overview of Responsive Images<br>
What are responsive images? <br> The goal of responsive images is to serve the __right image__ to the __right screen size__ and device, in order to avoid downloading unnecessary large images on smaller screens.<br>
<!-- 5 min break -->
* ✅ (10 min - Lec 61) Responsive Images in HTML - Art Direction and Density Switching<br>
Using the ```srcset``` attribute for ```img``` element for "density switching" aka different resolutions.
![density](/assets/session8/density.png)
With the ```picture``` element, we can specify multiple sources for one image.
![picture](/assets/session8/picture.png)

* ✅ (18 min - Lec 62) Responsive Images in HTML - Density and Resolution Switching<br>
It might be helpful to go over this [lecture](https://www.udemy.com/advanced-css-and-sass/learn/v4/t/lecture/8274562?start=0) again, starting at 15:55.

Homework: change ALL of the images to responsive images (I didn't do it hurhur)

You can alter the resolution of your browser for testing 👇
![resolution](/assets/session8/resolution.png)
<br>
* ✅ (12 min - Lec 63) Responsive Images in CSS<br>

What we're going to learn here: how to implement responsive images in CSS, how to use resolution media queries to target high-resolution screens with 2x. How to combine multiple conditions in media queries.

Here we are going to reduce the size of the hero image from 2000px to 1200px for small screen sizes.
If the screen resolution is higher than 192 dots per inch, than load the larger hero image.

![hero](/assets/session8/hero.png)

Remember! **Media queries always use ```em```!**

(haven't completed yet)
* ✅ (22 min - Lec 64) Testing for Browser Support with @supports<br>
* ✅ (21 min - Lec 65) Setting up a Simple Build Process with NPM Scripts<br>
* ✅ (14 min - Lec 66) Wrapping up the Natours Project: Final Considerations<br>



## Session 7 – [🔝](#all-sessions)
*🗓 M, Nov 26, 2018* <br>
*💬Lectures: 54-57* <br>
*🕐 10:40pm-1:15am* <br>
*📍Planet Fitness* <br>

* ⏰ Total Lecture Time: 75min = 1h15min<br>
* ✅ (1 min - Lec 54) Section Intro<br>
* ✅ (18 min - Lec 55) Mobile-First vs Desktop-First and Breakpoints<br>
* ✅ (28 min - Lec 56) Let's Use the Power of Sass Mixins to Write Media Queries<br>
The order the __media queries__ are arranged matters!
* ✅ (27 min - Lec 57) Writing Media Queries - Base, Typography and Layout<br>
Oh hey, you can actually show media queries!
![mediaqueries](/assets/session7/mediaqueries.png)
Aaah! So annoying, there is this weird padding-right on the homescreen to the Advanced CSS course.<br>
There is something wonky with the top section.


## Session 6 – [🔝](#all-sessions)

*🗓 S, Nov 23, 2018 - Su, Nov 24, 2018* <br>
*💬Lectures: 41-53* <br>
*🕐 7PM-9:40am* <br>
*📍Home* <br>

#### In the Stories Section, we will learn how to:
* make text flow around shapes with ```shape-outside``` and ```float```.
* apply a ```filter``` to images.
* create a background video covering an entire section.
* use the ```<video>``` HTML element.
* how and when to use the ```object-fit``` property.

#### In the Booking Section, we will learn how to:
* implement "solid-color gradients";
* how the general and adjacent sibling selectors work and why we need them;
* use the ```::input-placeholder``` pseudo-element;
* how and when to use the ```:focus, :invalid, placeholder-shown, :checked``` pseudo-classes;
* techniques to build custom radio buttons;

#### In the Navigation Section, we will learn:
* What the "checkbox hack" is and how it works;
* How to create custom animation timing functions using cubic bezier curves;
* How to animate "solid-color gradients";
* How and why to us ```transform-origin```;
* In general: create an amazing creative effect!

#### While building a pure CSS Popup, we will learn:
* How to build a nice popup with only CSS;
* How to use the ```:target``` pseudo-class;
* How to create boxes with equal height using ```display: table-cell;```;
* How to create CSS text columns;
* How to automatically hyphenate words using ```hyphens```;

#### Progress🔥
* ⏰ Total Time: 243min = 4h03min<br>
* ✅ (16 min - Lec 41) Building the Tours Section - Part 3<br>
When some CSS is not working, the best way to debug is to inspect the element with the chrome inspector tools and play around with the styles.
* ✅ (20 min - Lec 42) Building the Stories Section - Part 1<br>
Used the ```transform: skewX(12deg)``` in ```_story.scss``` to skew the story container box.
* ✅ (14 min - Lec 43) Building the Stories Section - Part 2<br>
Whenever you want one element to be positioned over another element, you use ```position: absolute``` on the element and the ```position: relative``` on the parent element. Whenever you perform an animation, you need to use the ```transition``` property to determine animation speeds. Use ```backface-visibility: hidden``` whenever there are small weird animation glitches. This usually fixes it!
* ✅ (14 min - Lec 44) Building the Stories Section - Part 3<br>
Can go on [coverr.co](www.coverr.co) to download all sorts of handy videos for your website.<br>
Whenenever an image or video goes over it's borders, ```overflow: hidden``` is a very useful property.
* ✅ (19 min - Lec 45) Building the Booking Section - Part 1<br>
Learned a cool semi-transparent trick with ```linear gradient``` property in ```home.scss .book``` class
* ✅ (19 min - Lec 46) Building the Booking Section - Part 2<br>
Learned about ```font-family:inherit```.<br>
* ✅ (23 min - Lec 47) Building the Booking Section - Part 3<br>
Whenever you perform an animation on an element, you need ot apply the ```transition``` (helps determine speed) to the parent element, otherwise the animation won't work. Creating a custom radio button is super cool.
* ✅ (16 min - Lec 48) Building the Footer<br>
Love the text animation in the footer. Super cool!
* ✅ (30 min - Lec 49) Building the Navigation Part 1<br>
```z-index``` only works on an element with the ```position``` property defined.
* ✅ (14 min - Lec 50) Building the Navigation Part 2<br>
Check out easing functions at [easings.net](www.easings.net)
* ✅ (16 min - Lec 51) Building the Navigation Part 3<br>
Working on the hamburger icon.
* ✅ (25 min - Lec 52) Building a Pure CSS Popup Part 1<br>
* ✅ (17 min - Lec 53) Building a Pure CSS Popup Part 2<br>








## Session 5 – [🔝](#all-sessions)
*🗓 F, Nov 22, 2018* <br>
*🕐 6:30am-7:20am*  <br>
*📍Home* <br>
*✍️Commits: 20* <br>

* ✅ (31 min min - Lec 40) Building the Tours Section - Part 2<br>
Simplest way to **center** a block element within another block element: ```margin: 0 auto;``` <br>
*Needed to take a break at 7:20am to prepare for morning 8am call for the Muay Thai Mastermind*

## Session 4 – [🔝](#all-sessions)
*🗓 Th, Nov 21, 2018* <br>
*📶Progress: 32%* <br>
*⏰Lecture Hours: 57 min*<br>
*💬Lectures: 38-40* <br>
*🕐 6:20am-noon*  <br>
*📍 Home* <br>
*✍️Commits: 17-19* <br>

* ✅ (31 min - Lec 38) Building the Features Section<br>
Downloaded icon set from [lineao.io](http://linea.io/). Note: using PNGs is bad practice for icons. Instead you want to either use fonts or SVGs.
Learned a bit more about transforms.<br>
* ✅ (26 min - Lec 39) Building the Tours Section - Part 1<br>
Note to self. It is **very** important to remember the ```;``` in writing SCSS files. Otherwise, the changes aren't shown aand no errors are thrown.
* ⏰ Total Time: 57min <br>

![Session4Gif](/assets/session4/session4.gif)

## Session 3 – [🔝](#all-sessions)
*🗓 W, Nov 20, 2018* <br>
*📶Progress: 30% Complete (8.4/28 hours)* <br>
*⏰Lecture Hours: 1h 40min*<br>
*💬Lectures: 34-37* <br>
*🕐 5am-7:10am*  <br>
*📍 Home* <br>
*✍️Commits: 14-16* <br>

* ✅ (37 min - Lec 34) Building a Custom Grid with Floats<br>
* ✅ (23 min - Lec 35) Building the About Section Part 1 –– in this lecture we learn how to think about components, how and why to use utility class, how to use the ```background-clip``` property, how to ```transform``` multiple properties simulatenously, how to use the ```outline-offset``` property together with ```outline```, how to style elements that are NOT hovered while others are.<br>
* ✅ (22 min - Lec 36) Building the About Section Part 2<br>
* ✅ (18 min - Lec 37) Building the About Section Part 3<br>
* ⏰ Total Time: 100 min → 1h 40 min<br>'

![Session3Gif](/assets/session3/session3.gif)

## Session 2 – [🔝](#all-sessions)
*🗓 T, Nov 19, 2018* <br>
*📍 Home + Haddon Township Library* <br>
*🕐 5am-4pm(interspersed with breaks)*  <br>
*✍️Commits: 4-13* <br>
*💬Lectures: 8-33* <br>
*📶Progress: 26% Complete* <br>
*📱Instagram Post [Link](https://www.instagram.com/p/BqaywmFBPIM/)* <br>

### Most important takeaways from today's learning session
➡️ TERMINOLOGY: Learned the CSS terminology (selector, declaration block, declaration, property, declared value)<br>
➡️ ANIMATIONS: @keyframe and transform property animations (learned some really cool button animations!)<br>
➡️ PSEUDO: pseudo elements and pseudo classes (e.g. ::after + :visited)<br>
➡️ REMs: instead of using px I'm now going to try to only use rem for determining sizes<br>
➡️ SASS: learned the fundamentals of SASS

*💭what needs to be optimized/changd next learning session:*
* in the future, always go to morning training--why? library doesn't open until 10am and in btw the time that YY goes to work and 10am you snack🍫
* in the future, avoid studying at home🏡 (except 4am-7am)--why? 1. will snack from fridge 2. high likelihood of falling  asleep on couch.

### Section 4: Introduction to Sass and NPM

Need to run ```npm run compile:sass``` in terminal. Watch [Lecture 27](https://www.udemy.com/advanced-css-and-sass/learn/v4/t/lecture/8274462?start=829) to learn how to install Sass and [Lecture 28](https://www.udemy.com/advanced-css-and-sass/learn/v4/t/lecture/8274464?start=0) to learn how to compile Sass in local project.

#### Main Sass Features

![sass](/assets/session2/sass.png)

#### Introduction to Sass [Codepen](https://codepen.io/juzdepomme/pen/xQpRqa?editors=1100)
![sass-intro-codepen](/assets/session2/sass-intro-codepen.png)

### Section 3: How CSS Works: A Look Behind the Scenes

Three Pillars of Writing Good HTML and CSS (Lecture 12)

![3 pillars](/assets/session2/3-pillars.png)

What actually happens to our CSS code when we load up a certain web page in a browser?

![rendercss](/assets/session2/rendercss.png)

CSS Terminology

![cssterm](/assets/session2/cssterm.png)

How the Cascade resolves conflicts

![cascade](/assets/session2/cascade.png)

Most important Cascade and Speciftakeaways

![takeaway](/assets/session2/takeaway.png)

How CSS values are processed

![process](/assets/session2/process.png)

How units are converted from relative to absolute (px)

![unit](/assets/session2/unit.png)

CSS Value Processing: What You Need To Know

![summary](/assets/session2/summary.png)

Inheritance: What You Need To Know

![inheritance](/assets/session2/inheritance.png)

Visual Formatting Model
![vfm](/assets/session2/vfm.png)

Box Types
![box types](/assets/session2/box-types.png)

Positioning Schemes
![position](/assets/session2/position.png)

Building with meaningful class names
![classnames](/assets/session2/classnames.png)

## Session 1 – [🔝](#all-sessions)

*🗓 S, Nov 17, 2018* <br>
*📍 Haddon Township Library* <br>
*🕐 2:50pm-5pm (2h10min)* <br>
*✍️Commits: 1,2,3* <br>
*💬Lectures: 1-7* <br>
*📶PProgress: 5%* <br>
*📱Instagram  Post [Link](https://www.instagram.com/p/BqUd9bwBoN5/)* <br>

* Downloaded the starter project for the [Natours](https://natours.netlify.com/) project.
* *(Lecture 6: Building the Header - Part 1)* Learned about [Clippy](https://bennettfeely.com/clippy/) – CSS clip-path maker

Course Material and FAQ for my Advanced CSS Course [Link](https://github.com/jonasschmedtmann/advanced-css-course)<br>
Instructor's Resource Page [Link](http://codingheroes.io/resources/)<br>
Jonas' [Codepen](https://codepen.io/jonasschmedtmann/pens/public/)<br>
VSCode [setup](https://github.com/jonasschmedtmann/advanced-css-course/blob/master/vscode-setup.md) used in the course<br>

![discord](/assets/session1/discord.png)

Joined the [Discord discussion group](https://discordapp.com/channels/146186188783484928/146192848750903296) for the class. Password for Discord account is in email. Also downloaded and installed the Discord app for Mac.

### Final Version of Course Projects
* [Natours](https://natours.netlify.com/) - advanced CSS, Sass and responsive design
* [Trillo](https://trillo.netlify.com/) - Flexbox
* [Nexter](https://nexter.netlify.com/) – CSS Grid



