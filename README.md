![Sweet Noni Logo](/assets/images/logosweetnoni.png)

Welcome to the read me for Sweet Noni Classes.

This documents outlines the goals of the website and its functionality throughout.

------
## Core Aims

Sweet Noni Classes is intended to be a site where Giovana Giannoni, proprietor of Sweet Noni, can advertise baking and cake decoration classes, as well as display some of her work.

The core aim of the site is to make it easy for visitors to peruse some of Giovana's work, view upcoming course details, and express interest in joining one of those courses via the use of a Book Now form. The site is targeted towards people looking to improve their baking and cake decoration skills, in Dublin, Ireland.

![Am I Responsive](/assets/images/Responsive.JPG)

The site is fully responsive across all devices and maintains good resizing and positioning throughout.

------
## Features

<strong>Navigation</strong><br>
At the top of the page we feature a navigation composed of the site logo (positioned left) and three page links: Home, Courses, Book Now (positioned right).<br> 

Navigation is clear and easy to understand. The active page is highlighted with a white underline effect.<br>

Users can also click the logo to return to the home page too (index.html).<br>

The navigation is responsive in that it reduces itself to a hamburger menu on smaller devices. Users can click the hamburger to expand the menu again.<br>


<strong>Site Fonts</strong><br>
We use Lato as our primary font, and sans-serif as our backup, throughout the site.

<strong>Colors</strong><br> 
Background: teal
Text: white
Forms and course boxes: rgba(60, 60, 60, 0.6)

<strong>Header</strong><br> 
The header shows the site title and also includes a selection of keywords related to baking and cake decoration in Dublin, Ireland. It is clear who the site is targeted towards.

<strong>Flashing Text</strong><br> 
We have a small call to attention at the top of the site, emphasizing the theme of the site: Cake Decoration with Sweet Noni. We use a flashing effect so that it fades in and out repeatedly.

Flashing Hearts Section Dividers: We use three hearts, in descending sizes, one below the other to indicate the movement between sections of the homepage. We use a flashing effect on the hearts so they fade in and out continually.

<strong>Top Gallery Section</strong><br>  
We show a selection of six photos of Giovana's cakes. On larger screens it should appear as three columns, two rows. As devices shrink, the columns / rows respond accordingly.

<strong>Intro and Description Section</strong><br> 
This section gives a brief background on Giovana and her business. It also includes a picture of her in her kitchen. 

<strong>Book Now Button</strong><br> 
At the bottom of the home page we show a Book Now button. The button is designed with the site colours inverted, so the button is white and the text is teal. It also uses a white glowing effect, drawing the attention of the user.

<strong>Footer Section</strong><br> 
Our footer is centered at the bottom of the page. We display icons linking to Facebook, Twitter, Youtube, Instagram.


<strong>Courses Page</strong> 
We display all available courses here.
Each course is clearly separated into its own box effect. Refer to our colour scheme above for colour guide.
Each course shows: Class details, date, time, location and cost.
We also show a Book Now button at the bottom of each available course, with the same glowing effect as the Book Now Button on the home page.

<strong>Book Now</strong>: 
The Book Now page offers a simple for for the user to fill out, with the following required fields: First name, surname, email address and radio buttons to indicate the course(s) they are interested in. There is a 'Send' button which then sends the form to Giovana.

------
## Testing

I have tested the site across multiple devices of different sizes, and a variety of popular browsers. The site performs well across all.

<strong>Responsiveness</strong><br> Confirmed across multiple devices.<br>
<strong>Navigation and Links</strong><br> All are functional and easy to understand.<br>
<strong>Form</strong><br>The form is working in that a user cannot complete the form without filling in the required fields.<br>

<strong>Unfixed bugs</strong><br> I am having a problem displaying two columns on mobile. Currently it shrinks to one column, which is not ideal for gallery display.<br>

------
## Testing
![Lighthouse Score](/assets/images/lighthouse-score.png)
<strong>HTML</strong><br>No errors returned when passed through W3C validator.<br>
<strong>CSS</strong><br> No errors returned when passed through W3C validator.<br>
<strong>Accessibility</strong><br> We used google chrome's lighthouse tool and ranked as follows:<br>
    <strong>Performance:</strong> 52/100 (The main issue is the heaviness of how we are serving our high quality images)<br>
    <strong>Accessibility:</strong> 100/100<br>
    <strong>Best Practices:</strong> 92/100<br>
    <strong>SEO:</strong> 100/100<br>

------
## Deployment

The site is deployed to Github pages, accessible via: https://rggg1.github.io/SN/index.html<br>

To deploy to Github pages, navigate to Settings > Pages > Select 'main' for the master branch, then wait a few moments for the live URL to be generated.<br>

------
## Credits and Resources
I used the following resources to find solutions to various code problems I encountered:<br>
    https://freefrontend.com/ - used for reference on form styling<br>
    https://www.w3schools.com - to resolve various css issues and to create the flashing text / hearts<br>
    https://stackoverflow.com - to resolve html / css issues regarding image order and responsiveness, flexbox related<br>
    https://fontawesome.com - for social media iconography<br>
    https://code-boxx.com - for guide on how to create simple hamburger menu<br>
    https://learn.codeinstitute.net - for the Book Now form<br>
    http://www.sweetnoni.com/ - for references on images and details on Giovana (my wife).<br>


