# War History Online
#### by Andrew Harding




## Showcase
![responsive-screenshot](assets/images/testing/war-history-online.jpg)

A deployed live version of my War History Online website can be found [here](https://andrewh1188.github.io/war-history-online/)







## Table of Contents
1. [User Experience UX](#user-experience-ux)
    * [User Stories](#user-stories)
    * [Site Goals](#site-goals)
2. [Construction Planes](#construction-planes)
    * [Strategy](#strategy)
    * [Scope](#scope)
    * [Structure](#structure)
    * [Skeleton](#skeleton)
    * [Surface](#surface)
3. [Design](#design)
    * [Wireframes](#wireframes)
    * [Imagery](#imagery)
4. [Features](#features)
    * [Existing-features](#existing-features)
    * [Future-features](#future-features)
5. [Technologies and Languages Used](#technologies)
    * [Libraries Frameworks and Online Resources Used](#libraries)
    * [Tools](#tools)
    * [Programmes](#programmes)
    * [Other Resources](#other-resources)
    * [Social Media](#social-media)
    * [Portfolio Sites](#portfolio-sites)
6. [Testing](#testing)
7. [Bugs](#bugs)
    * [Bugs Fixed](#bugs-fixed)
    * [Known Bugs](#known-bugs)
8. [Deployment](#deployment)
9. [Credits](#credits)
    * [Content](#content)
    * [Media](#media)
    * [Acknowledgments](#acknowledgments)










## Design



The original mock designs that I produced in [Adobe InDesign](https://www.adobe.com/uk/products/indesign.html) can be found below:

#### Home / Index page
![Home](/assets/images/designs/war-history-online-by-andrew-harding.jpg)

#### Campaigns page

#### Contact















## Bugs
### Main Image and CSS
On the Live view I was able to see the image and the layout on my page, although once this was pushed to GitHub Pages, I saw the following: ![Bug1](/assets/images/bugs/bug1.png)

Using Google Dev Tools to inspect my page the issue was soon identified as a stray / before assets in both the CSS and imgsrc. Once the stray / was removed and the page recommitted and checked I was able to see the page display as initially intended:
![Bug1 Fixed](/assets/images/bugs/after-bugfix1.png)





### Navbar dropdown arrow
I would like the dropdown arrow to sit next to the current History tab, although at the moment this is not displaying as I had intended it to:
![Navbar dropdown arrow](/assets/images/bugs/navbar-dropdown-arrow.png)
Using Google Dev Tools to inspect I changed the styling from:
![Navbar dropdown arrow before](/assets/images/bugs/styling-before.png)
To: ![Navbar dropdown arrow after](/assets/images/bugs/styling-after.png)
After changing this I was able to achieve the layout that I was aiming for:
![Navbar dropdown arrow view](/assets/images/bugs/navbar-fixed.png)


