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

Header
The header shows the site title and also includes a selection of keywords related to baking and cake decoration in Dublin, Ireland. It is clear who the site is targeted towards.

Colors
Background: teal
Text: white
Forms and course boxes: rgba(60, 60, 60, 0.6)

Top Gallery
We show a selection of six photos of Giovana's cakes. On larger screens it should appear as three columns, two rows. As devices shrink, the columns / rows respond accordingly.





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
