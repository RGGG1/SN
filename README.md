![Sweet Noni Logo](/assets/images/logosweetnoni.png)

Welcome to the read me for Sweet Noni Classes.

This is the Read Me document for Sweet Noni, outlining the aim of the website and its functionality throughout.
------
## Core Aims

Sweet Noni Classes is intended to be a site where Giovana Giannoni, proprieter of Sweet Noni, can advertise baking and cake decoration classes, as well as display some of her work.

The core aim of the site is to make it easy for visitors to peruse some of Giovana's work, view upcoming course details, and express interest in joining one of those courses via the use of a Book Now form. The site is targeted towards people looking to improve their baking and cake decoration skills, in Dublin, Ireland.

The site is fully responsive across all devices and maintains good resizing and positioning throughout. (Viewable here: https://ui.dev/amiresponsive?url=https://rggg1.github.io/SN/index.html)


------
## Features

Navigation
At the top of the page we feature a navigation composed of the site logo (positioned left) and three page links: Home, Courses, Book Now (positioned right). Navigation is clear and easy to understand. The active page is highlighted with a white underline effect. Users can also click the logo to return to the home page too (index.html).

The navigation is responsive in that it reduces itself to a hamburger menu on smaller devices. Users can click the hamburger to expand the menu again.


Site Fonts
We use Lato as our primary font, and sans-serif as our backup, throughout the site.

Colors
Background: teal
Text: white
Forms and course boxes: rgba(60, 60, 60, 0.6)

Header
The header shows the site title and also includes a selection of keywords related to baking and cake decoration in Dublin, Ireland. It is clear who the site is targeted towards.

Flashing Text
We have a small call to attention at the top of the site, emphasizing the theme of the site: Cake Decoration with Sweet Noni. We use a flashing effect so that it fades in and out repeatedly.

Flashing Hearts Section Dividers: We use three hearts, in descending sizes, one below the other to indicate the movement between sections of the homepage. We use a flashing effect on the hearts so they fade in and out continually.

Top Gallery Section
We show a selection of six photos of Giovana's cakes. On larger screens it should appear as three columns, two rows. As devices shrink, the columns / rows respond accordingly.

Intro and Description Section 
This section gives a brief background on Giovana and her business. It also includes a picture of her in her kitchen. 

Book Now Button
At the bottom of the home page we show a Book Now button. The button is designed with the site colours inverted, so the button is white and the text is teal. It also uses a white glowing effect, drawing the attention of the user.

Footer Section
Our footer is centered at the bottom of the page. We display icons linking to Facebook, Twitter, Youtube, Instagram.


Courses Page
We display all available courses here.
Each course is clearly separated into its own box effect. Refer to our colour scheme above for colour guide.
Each course shows: Class details, date, time, location and cost.
We also show a Book Now button at the bottom of each available course, with the same glowing effect as the Book Now Button on the home page.

Book Now
The Book Now page offers a simple for for the user to fill out, with the following required fields: First name, surname, email address and radio buttons to indicate the course(s) they are interested in. There is a 'Send' button which then sends the form to Giovana.

------
## Testing

I have tested the site across multiple devices of different sizes, and a variety of popular browsers. The site performs well across all.

Responsiveness: Confirmed
Navigation and Links throughout site: All are functional and easy to understand.
Form: The form is working in that a user cannot complete the form without filling in the required fields.

Unfixed bugs: I am having a problem displaying two columns on mobile. Currently it shrinks to one column, which is not ideal for gallery display.

------
## Testing

HTML: No errors returned when passed through W3C validator.
CSS: No errors returned when passed through W3C validator.
Accessibility: We used google chrome's lighthouse tool and ranked as follows:
    Performance: 52/100 (The main issue is the heaviness of how we are serving our high quality images)
    Accessibility: 100/100
    Best Practices: 92/100
    SEO: 100/100

------
## Deployment

The site is deployed to Github pages, accessible via: https://rggg1.github.io/SN/index.html

To deploy to Github pages, navigate to Settings > Pages > Select 'main' for the master branch, then wait a few moments for the live URL to be generated.

------
## Credits and Resources
I used the following resources to find solutions to various code problems I encountered:
    https://freefrontend.com/ - used for reference on form styling
    https://www.w3schools.com - to resolve various css issues and to create the flashing text / hearts
    https://stackoverflow.com - to resolve html / css issues regarding image order and responsiveness, flexbox related
    https://fontawesome.com - for social media iconography
    https://code-boxx.com - for guide on how to create simple hamburger menu




We continually tweak and adjust this template to help give you the best experience. Here is the version history:

**September 1 2021:** Remove `PGHOSTADDR` environment variable.

**July 19 2021:** Remove `font_fix` script now that the terminal font issue is fixed.

**July 2 2021:** Remove extensions that are not available in Open VSX.

**June 30 2021:** Combined the P4 and P5 templates into one file, added the uptime script. See the FAQ at the end of this file.

**June 10 2021:** Added: `font_fix` script and alias to fix the Terminal font issue

**May 10 2021:** Added `heroku_config` script to allow Heroku API key to be stored as an environment variable.

**April 7 2021:** Upgraded the template for VS Code instead of Theia.

**October 21 2020:** Versions of the HTMLHint, Prettier, Bootstrap4 CDN and Auto Close extensions updated. The Python extension needs to stay the same version for now.

**October 08 2020:** Additional large Gitpod files (`core.mongo*` and `core.python*`) are now hidden in the Explorer, and have been added to the `.gitignore` by default.

**September 22 2020:** Gitpod occasionally creates large `core.Microsoft` files. These are now hidden in the Explorer. A `.gitignore` file has been created to make sure these files will not be committed, along with other common files.

**April 16 2020:** The template now automatically installs MySQL instead of relying on the Gitpod MySQL image. The message about a Python linter not being installed has been dealt with, and the set-up files are now hidden in the Gitpod file explorer.

**April 13 2020:** Added the _Prettier_ code beautifier extension instead of the code formatter built-in to Gitpod.

**February 2020:** The initialisation files now _do not_ auto-delete. They will remain in your project. You can safely ignore them. They just make sure that your workspace is configured correctly each time you open it. It will also prevent the Gitpod configuration popup from appearing.

**December 2019:** Added Eventyret's Bootstrap 4 extension. Type `!bscdn` in a HTML file to add the Bootstrap boilerplate. Check out the <a href="https://github.com/Eventyret/vscode-bcdn" target="_blank">README.md file at the official repo</a> for more options.

------

## FAQ about the uptime script

**Why have you added this script?**

It will help us to calculate how many running workspaces there are at any one time, which greatly helps us with cost and capacity planning. It will help us decide on the future direction of our cloud-based IDE strategy.

**How will this affect me?**

For everyday usage of Gitpod, it doesn’t have any effect at all. The script only captures the following data:

- An ID that is randomly generated each time the workspace is started.
- The current date and time
- The workspace status of “started” or “running”, which is sent every 5 minutes.

It is not possible for us or anyone else to trace the random ID back to an individual, and no personal data is being captured. It will not slow down the workspace or affect your work.

**So….?**

We want to tell you this so that we are being completely transparent about the data we collect and what we do with it.

**Can I opt out?**

Yes, you can. Since no personally identifiable information is being captured, we'd appreciate it if you let the script run; however if you are unhappy with the idea, simply run the following commands from the terminal window after creating the workspace, and this will remove the uptime script:

```
pkill uptime.sh
rm .vscode/uptime.sh
```

**Anything more?**

Yes! We'd strongly encourage you to look at the source code of the `uptime.sh` file so that you know what it's doing. As future software developers, it will be great practice to see how these shell scripts work.

---

Happy coding!
