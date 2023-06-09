# SnakesLadders 
(Developer:  Deirdre McCarthy, May 2023)

# Table of Contents:
1. [About](#about)
2. [Project Goals: ](#project-goals)
    1. [UX Design - Strategy ](#ux-design-strategy) 
    2. [UX Design - Strategy - Competitor Portals](#ux-design-strategy-analysis-of-competitor-offerings)
    3. [UX Design - Strategy - Target Audience](#ux-design-strategy-target-audience)
3. [UX Design - Scope](#ux-design-scope)
    1. [UX Design - Scope - User Requirements and Expectations](#ux-design-scope-user-requirements-and-expectations)
    2. [UX Design - Scope - Data](#ux-design-scope-data)
    3. [UX Design - Scope - Viewing Device](#ux-design-scope-viewing-device)
4. [User goals/ user stories: ](#user-goals-user-stories)
    1. [Site Owner Goals](#site-owner-goals)
    2. [First-time User Goals](#first-time-user-goals)
    3. [Returning User Goals](#returning-user-goals)
    4. [Other stakeholder Goals](#other-stakeholder-goals)
    5. [Future Site owner and Administrator Goals](#future-site-owner-and-administrator-goals)
5. [Further UX Design: ](#ux-design-decisions)
    1. [Skeleton - Wireframes; ](#wireframes)
    2. [Surface - Fonts; ](#fonts-chosen)
    3. [Surface - Colours](#colour-scheme)
    4. [Surface - Imagery](#design-images)
6. [Features](#features)
    1. [Included](#features-in-scope)
    2. [Future Development](#features-left-to-implement)
    3. [Requirements Tracing](#RTM)
7. [Technology](#technologies)
    1. [Languages](#langugages)
    2. [Frameworks and Tools](#frameworks--tools)
8. [Validation](#validation)
    1. [HTML Validation](#html-validation)
    2. [CSS Validation](#css-validation)
    3. [Accessibility](#accessibility)
    4. [Performance](#performance)
    5. [Multi-device Testing](#multi-device-testing)
    6. [Multi-browser Testing](#multi-browser-testing)
    7. [Testing user stories](#testing-user-stories)
    6. [Feature testing(#rtm-proof)]
    6. [Unfixed Bugs](#unfixed-bugs)
9. [Accessibility](#accessibility)
10. [Performance](#performance)
11. [Deployment](#deployment)
12. [Credits](#credits)
    1. [Content](#content)
    2. [Media](#media)
    3. [Code](#code)
    4. [References](#references)
    5. [Acknowledgements](#acknowledgements)

## About
---------
This website offers the user a fun way to learn about how to problem-solve for a particular context, using a game that many are already familiar with.
The game is snakes and ladders, and it normally involves an element of chance (rolling a dice) which progresses the player from position 1 on a numbered board
to (eventually) position 100.  The squares are arranged on a reverse-wrapped grid, and the second element of chance is that the player may land in a square which shows the foot of a ladder, in which case they can progress to the top of the ladder (a square further on in the grid), skipping all the squares in between. Alternatively, they may land on the head of a snake, in which case they slide back to a previous position (a lower-numbered square in the grid).  Eventually, battle scarred and covered in snake slime, the player manages to reach the end.  Normally this is played with multiple players, and the first one home wins. 

So this website is based around that familiar concept.

It occured to me, when doing project mangement work, that some projects were like a 'game of snakes and ladders' in that seemingly random events (good or bad luck, small decisions that had far-reaching consequences) could positively or negatively impact the project progress.  So I wondered whether the snakes-and-ladder concept could be extended to different types of scenarios, with some decisions or chance events, which have a defined start and end point.
Maybe the player could answer a multi-choice question at certain squares and, depending on their response, a snake (wrong answer) or a ladder (right answer) could appear.   This could maybe apply to different start->goal scenarios such as:
* Project management - start to end of a project
* Financial Independence Retire Early - financial decisions taken within a working life, which impact on the retirement age (this could be combined with a data repository maybe something like the 'game of life in snakes and ladders'.
* Code Institute PP development & documentation - following the necessary steps (we could all relate to this).

At the abstract level, the board could be visually attractive, the snakes and ladders could be pre-positioned, and the questions could be pre-loaded.
To make this a feasible project it would make sense 

Another dimension could be aded which is 'remaining-life-force', where e.g.
Project management - remaining budget/ time to complete
FIRE - savings target/ retirement age, debit levels... Code institute - days to complete

Another dimension might be the idea of 'phase' - perhaps one phase per grid row, e.g. 
Project management - process steps (PLAN - planning & setting up project structures, creating document controls; BUILD - assembling the elements, including execution, monitoring; TEST/VALIDATE; IMPLEMENT; MONITOR);

FIRE - childhood, young adult (plenty of earnings), life partner, parenting, empty nest -> retirement (golden years);

Code institute - planning project (PLAN - researching the topic, wireframes, readme template, descriptive text); BUILD -  building project (coding); VALIDATE - validating project (lots of snakes here as accessibility validation could mean a retest of css/html -> take you back to previous steps for re-testing), user testing, device testing, responsiveness testing (hmm lots of potential squares here); DOCUMENT; CELEBRATE  
hmmmmmmm......... OK lets start with the snakes and ladders idea then proceed from there... maybe the concept could be something like when you land on a snake (setback) or a ladder (opportunity) you get to answer a question which decides how you can proceed from there.  

### Responsive Mockup
https://ui.dev/amiresponsive?url=https://deemccart.github.io/CI_PP2_SnakesLadders/

### Live webpage link
https://deemccart.github.io/CI_PP21_SnakesLadders

## Project Goals
----------------
1. To produce a 25-square snakes and ladders game 
2. in a mobile-first development environment.  
3. which can be applied to different progressive situations.
  
### UX Design Strategy
The aim of this specific website is develop a snakes-and-ladders game which can be played in simple (just as snakes and ladders) or more complex (snakes and ladders learning game for a particular topic) form

The audience is:<br>
a. People who want to play a game and who want to have a reliable consistent experience through out the game (in other words, they want an opportunity to finish the game by reaching the end, and they want to be able to trust the process (ie they can understand how they move forward or backwards, and they dont feel it is unfair or impossible to complete).

b. People who want to learn about a particular domain area, for example they want to learn about project submissions for Code Institute, or they want to learn about project mangagement, or about investment decisions in life.
(branded snakes and ladders)

### UX Design Strategy Analysis - Existing Online Stakes and Ladders Games
https://toytheater.com/snakes-and-ladders/ A colourful game of 100 squares where you can play against the computer.  Music background and animation.
https://www.cbc.ca/kids/games/all/snakes-and-ladders (actually the same game as above, screen is slightly different but music graphics etc the same)
https://www.crazygames.com/game/snakes-and-ladders same as above, just auto-muted

(Comparative analysis (jpg or png) to follow here are other downloadable games which i will investigate a bit later, they seem to be firmly in the kids sphere) 

A competitive analysis of these offerings can be seen here https://deemccart.github.io/CI_PP1_ArklowTrails/assets/readme_images/Strategy-competitive-analysis.pdf
<br>
From this analysis, a set of possible requirements was identified for a new portal.
<br><br>
<br>
<br>
<br>

### UX Design Strategy Target Audience
* Game players
* who want to check their knowledge on one of the topics offered
* and have a bit of fun doing it

## UX Design Scope
----------------

### UX Design Scope User Requirements and Expectations
The basic requirement for users is to have access to a 'fair' game where they have a possibility of reaching the goal.

* The target audience needs to complete a process/set of tasks
* They have a checklist which contains many activities, there are many things that can go wrong (or right)
* The game helps them to complete their real-life tasks by warning them of potential pitfalls and alerting them to opportunities
* The game is a fun way of embedding real-world knowledge 

### UX Design Scope - Data
For this project to deliver both goals:
* game
* mapping to real-life problem
a set of data had to be developed for the real-life problem.  This took the form of scenarios and change events with 3 possible outcomes

scenario/ chance event                                                      Bad       medium      good
You are validating your accessbility and it warns you that input = textarea nt valid what do you do
* bad - correct it and continue
* good  - correct it and continue 
* very good - correct it and revalidate html & css

You are checking responsiveness and I am responsive appears fine what do you do next
* bad - happy days save the link and continue
* good - test using iphone 5S on the MS developer platform
* very good - physically check on different devices

You are uploading images and they appear to load OK what do you do next
* bed - nothing the website looks grand
* good - check performance
* very good - check performance and monitor image sizes, reduce if needed


### UX Design Scope Viewing Device 
This is a game, so primary (fun) site usage is expected to be via mobile devices - at a time thats convenient.
However people sometimes get bored at work so might accidentally on purpose browse to this and lose themselves for a couple of hours
Support for a range of device types, and responsiveness to the size of the user's screen are highly important for the successful implementation of this website

## User Goals/ User Stories
----------------

### Site owner Goals
* SO_01 As site owner I want to provide a fun, satisfying game
* SO_02 As site owner I want to ebmbed a learning experience into this game
* SO_03 As site owner I want to increase the body of knowledge in the area of .....
*
### First-time User Goals
* FTU_01 I am curious about what this does, and may just want to play a game
* FTU_02 As a first time user I would like to be able to navigate the site and quickly learn its functionality
* FTU_03 I might be curious about the 'applied' options (think about what to call these) and wish to explore these
* FTU_04 As a first time user I want to learn about the topic, but in an accessible, fun way.

### Returning User Goals
* RU_01 As a returning user I wish to play the game, just because I enjoy it
* RU_02 As a returning user I might like to challenge or inform myself on the branded game
* RU_03 As a returning user I might wish to suggest questions to add into the databank
*  
### Other stakeholder Goals
* OT_01 As a parent I might wish my child would STOP PLAYING THOSE BLOODY COMPUTER GAMES AND DO YOUR HOMEWORK
* OT_02 As an educator I might recognise the opportunity to build in some learning
* OT_03 As an educator I might wish to design questions and suporting information for the user (maybe along the lines of question - answer - suporting information )

### Future Site owner and Administrator Goals
* FUT_01 NB In the future, the current site owner role may evolve into two roles - Site Owner and Site Administrator.  One or more Site Administrators would take on the roles listed above for specific geographic territories, and a new Site Owner role with overall responsibilities for hosting a bank of trails websites (and possibly for digitising new walks at the site Administrators request)    
* FUT_02 In order to process user feedback, a future rule of site moderator (Administrator) will be needed to review and approve submitted reviews and photos, and add them to the trails website databank.

## UX Design Decisions
----------------

### Wireframes
<details><summary>Landing Page</summary>
The landing page WF is shown here with 4 sceen resolutions as I found when testing that the Motorola G(7) was truncating to the right hand side for 2-column pictures display, therefore I added an additional responsiveness section to cater for 320-400 pixel screen size.   This was really just an issue for the landing page, the remaining screens sized OK for the content.
  
<img src="https://deemccart.github.io/CI_PP2_SnakesandLadders/assets/readme_images/WF01-landing-page.jpg">
</details>

<details><summary>Walk Details</summary>
<img src="https://deemccart.github.io/CI_PP1_ArklowTrails/assets/readme_images/WF02-Walk-Details.jpg">
</details>

<details><summary>Gallery</summary>
<img src="https://deemccart.github.io/CI_PP1_ArklowTrails/assets/readme_images/WF03-gallery.jpg">
</details>

<details><summary>Feedback</summary>
<img src="https://deemccart.github.io/CI_PP1_ArklowTrails/assets/readme_images/WF04-feedback.jpg">
>
</details>


### Fonts Chosen
Libre Franklin and Libre Baskerville are chosen because they are readable on large screens or smaller mobile devices.  This font is recommended for sites that may be content-heavy but which are regarded as fun friendly and approachable/inclusive.  These are identified by Google as good pairing.
Fallback fronts are used in both cases

### Colour Scheme
The colour combinations will be driven by the snakes and ladders game for clear visibility

For this particular site the foreground images tend to have strong and meaningful colours.  For example the central Google map redendering at the initial scale to show the 6 walks, has a lot of strong blue (sea) and strong green (countryside).   Wakls are mapped against the Google map background using strong, vibrant colours which stand out against the map background.  The same colour coding is used for the border of each walk flipchart to act as a visual reminder to users of the link between the map and the Arklow Trails website itself.

Colours used for flipchart boundaries per walks:
blue-border:    rgb(2, 136, 209)
fuschia-border: rgb(136, 14, 79)
orange-border: rgb(230, 81, 0)
yellow-border: rgb(255, 234, 0)
sludgegreen-border: rgb(129, 119, 23)
purple-border: rgb(103, 58, 183);

This corresponds with the colours which are available within Google maps digitising capabilities, so the rbg values of the mapped walk and its flipcard are consistent.

<details><summary>Digitising options in Google Maps</summary>
![Colour choices when digitising in Google Maps](./assets/readme_images/ux-design-choices-accessing-style-in-google-maps.jpg?raw=true "Google maps colour choices").
</details>

 
### Design Images
This site is reasonably image-heavy, a lot of the interest for users is in creating, uploading or browsing the walk images.  Because of the nature of the landscape in the location of Arklow (lots of waterbodies - sea, rivers; lots of green - woods), the images are given sufficient size for the user to be able to view and enjoy.  (ref user stories SO_04, FTU_04, RU_03, RU_05)

However a very fundamental aspect of this site is the categorisation of walks, it is not something that shouts out from the site, as the walk gallery photos take a lot of user attention, but in fact the cateogorisation is absolutely key to this site meeting its fundamental user requirement..  (ref user stories SO_02, FTU02, FTU_07) 

The approach taken is to use standardised categories, with freely downloadable font-awesome icons throughout the site (most particularly on walk summary flipcards, and on the walk details pages).   The range of icons available was not 100% correct, however a reaonsable compromise (e.g. using a 'crow' symbol to represent birdwatching)  was found in most cases.

![walk category symbols](./assets/readme_images/F06-Feature-Walk-Details-use-of-categorisation-icons.jpg?raw=true "Example of Walk Category Symbols used")


## Features 
 
### F01 Google Maps used as the anchor image on the landing page
The use of Google Map was a deliberate design decision. Google maps is widely used by people of all demographics, internationally as well as within Ireland, as a navigation tool.  Familiarity reduces the overall learning curve for new users of the Arklow Trails website.   Digitising tools available within the Google MyMaps interface, while outside the scope of this document, mean that trails data is presented visually in an attractive, comprehensible way which is meaningful to site users (corresponds to user stories SO_01, SO_03, FTU_01, FTU_07, RU_01 )

![Landing Page showing Google Map at centre](./assets/readme_images/230418%20Landing%20Page.jpg?raw=true "Landing Page")

### F02 Color-coded mapped walks
Six colour-coded mapped trails are shown.  The range of colours means they can be clearly distinguished from one another, and the same colour is used in the flipcard boundary. 

![Six colour-coded walks on Google Maps background](./assets/readme_images/F02-Feature-colour-coded-walks.jpg?raw=true "Mapped Walks")

The main objective of using consistent colour-coding is to make the site learnable, and act as a visual reminder for users when navigating between mapped walks and their corresponding flipcard.   This addresses elements of user stories FTU_01, FTU_07, RU_01

![Colour-coded walks Google Maps large screen](./assets/readme_images/F02-Feature-Google-Map-maximised-to-show-walk-data.jpg?raw=true "Colour-coded walks Google Maps large screen")

### F03 Colour-edged Photo Flipcards
The landing page map is surrounded by colour-edged flipcards, one per walks.
The border colour of each flipcard corresponds to the #rgb colour of its associated trail.
Each flipcard shows an attractive or intruiging photo, encouraging the user to hover over the image trail information.  This cnotributes to user stories SO_04, SO_05, FTU_04, FYU_07, RU_01

![Flipcard attractive photo example](./assets/readme_images/F03_a-Flipcard-images-photos.jpg?raw=true "Flipcard Attractive Photo").

On larger screens the flipcards are positioned to the left and the right of the main map.  On smaller screens, the main map appears first, with the flipcards appearing in either two, or, at smallest, one column below the map.

Hovering over a walk card 'flips' the display to show a walk name and summary detail.

### F04 The colour-edged photos flip to reveal walk summary
If the user's mouse moves over (desktop) or clicks (mobile) a colour-edged photo, it performs a pleasing shimmy and reveals summary trail data.
The user can then select a 'More details' link to access a point within the detailed 'Walks' page:
  - Each card identifies the walk by name and some key features of each walk.
  - Clicking on a particular card opens a link to the relevant walk detail  

- Icons are used within the category cards to categorise distance, trail type (forest/nature/seaside) etc..... 
- The consistent and repeated use of certain icons aids user learning 
- The use of icons improves readability and navigation, particularly for returning users

![Flipcard walks summary card](./assets/readme_images/F04_b-Flipcard-images-walk-summary.jpg?raw=true "Flipcard Attractive Photo")

Standard symbols are used for walk categorisation e.g. birds, sea, swimming, river, forest:

![Flipcard walks summary with category symbols](./assets/readme_images/F04-Feature-Fipcard-use-of-categorisation-icons.jpg?raw=true "Flipcard summary with category symbols")

Each flipcard has a 'More details...' link to encourage the user to access the walk details page:

![Flipcard walks summary more details link](./assets/readme_images/F04Feature-Flipcard-More-Details.jpg?raw=true "Flipcard summary with link to more details")

The flip-card detail is really a navigational aid, to encourage the user to traverse through images on the site, and progressively reveal details of the walks below.   On checking summary information the user might immediately think 'oh that walk is too long/short for me, it's not for me' and can quickly move along to the next image and scan the summary there.  So its a very nice feature because the user hasn't actually left the landing page and is just moving their mouse around to quickly investigate.
Ref user stories  


### F05 More details for each trail
The user can see more details per trail in one of three ways:
* By clicking on the 'more details' link from a flipcard (link to more details for a specific trail)
* By clicking on the URL linked to each trail in Google Maps (link to more details for a specific trail)
* Using the navbar to go directly to the 'Walks' page and scroll to find a walk of interest

Note that there are hyperlinks within page to position at each walk (walk01, walk02, etc )

![More details of a walk](./assets/readme_images/F05-Feature-Walk-Details-Page.jpg?raw=true "More details of a walk")

### F06 Feature consistent icons and categorisation
As per the walks summary flipcard the same symbols are used to help with learning the website
![Consistent Use of icons and categories](./assets/readme_images/F06-Feature-Walk-Details-use-of-categorisation-icons.jpg?raw=true "Icons and categories walks detail")
- clicking on a walk card brings the user to a separate walk details window which provides more information on each walk.  
- an explanation of the icons and categories is given on the 'About' page
![WalkCatCards](image3.png)
![HelpIconCategories](image4.png)

### F07-Average Reviews stars
Ability to view average ratings on scale 1-5 per walk, where 1 = terrible and 5 = fantastic, represented using star symbols (also echoed in the feedback form where the user can enter their own walk ratings) 
![Average trail reviews per walk](./assets/readme_images/F07-Feature-Walk-Details-average-trail-reviews.jpg?raw=true "Average trail reviews stars out of 5")

### F08 Walk Details Descriptive text
Helpful descriptions to describe the walk and help the reader determine if it is suitable or of interest to them.  This is in accordance with the 'progressive disclosure' principle whereby the user now has chosen to access full details of the walk.
![Six colour-coded walks on Google Maps background](./assets/readme_images/F08-Feature-Walk-Details-descriptive-text.jpg?raw=true "Mapped Walks")

### F09 Image carousel
An animated gallery of images is available per walk.
This is a simple html/css animation using a deck of 4 photos per walk with the viewing window transitioning between them.
(This became more complex to implement when I realised that the animation must be iniated by the user rather than auto-play!!).
![A clickable image carousel is shown](./assets/readme_images/F09-Feature-album-carousel.jpg?raw=true "Image carousel")

### F10 Responsive Navbar
The navigation bar appears on all pages, and is attractively laid out.  Four links are available - Home - Walks - Gallery - Feedback
The navbar is visible at the top of each screen, and is identical in each page/ screen size combination to allow for easy navigation.
It is fully responsive so will change positioning at 320, 400, 800 pixel screen widths. 
This section will allow the user to easily navigate from page to page across all devices without having to revert back to the previous page via the ‘back’ button.

![Responsive navbar](./assets/readme_images/F10-Feature-Navbar.jpg?raw=true "Responsive navbar")


### F11 Partner social media links (footer)
As this website is structured to operate more like to a peer-to-peer than a hierarchical structre, the footer bar is not currently used for broadcasting from a single site owner's social links, instead it is a set of 'partner' links to groups or websites which are relevant.    

  The links will open to a new tab to allow easy navigation for the user. 
  The footer is valuable to the user as it encourages them to keep connected via social media and to engage in a deeper way with the community sponsors of this project

Currently configured to point to:
* Social media/fabebook - Arklow Trail Trotters walking group, with details of their meeting times.
* Visit Wicklow website
* generic youtube
* generic instagram
![Footer partner links](./assets/readme_images/F11-Feature-Footer-bar.jpg?raw=true "Partner links")


### F12 Google Maps app functionality preserved on Arklow Trails website
Although this is fundamental to the successful operation of the site, it is not software that was developed within the Arklow Trails site, and has therefore been left towards the end of the list of 'Arklow Trails' features.  Arklow Trails has been designed and implemented so that standard Google maps features (navigation, pan, zoom, choice of mapping background, local points of interest) are still available to the user.

(This presented an implementation challenge as ideally the flipcards would have slightly overlapped the Google Maps screen, and it was intended to implement using z-positioning to overlay.... however when testing it was found that the Google Maps functionality was disabled as the focus was on the flipcards to the forefront... therefore an implementation decision to separate map and flipcards into different screen areas was taken)

![More details of a walk](./assets/readme_images/F12-Feature-Google-Map-integrated-data.jpg?raw=true "More details of a walk")
![Six colour-coded walks on Google Maps background](./assets/readme_images/F07-Feature-Google-Map-direction-finder1?raw=true "Mapped Walks")
![More details of a walk](./assets/readme_images/F05-Feature-Walk-Details-Page.jpg?raw=true "More details of a walk")

### F13 Google My Maps Data
As many potential site users are already familiar with Google map usages, the data created for the Arklow Trails website allows users to utilise it compatibly in the Google Maps interface.   clicking on either a route or its associated start-point (generally indicated by a colour-coded P on the map) triggers two actions:
![Google Map at centre](./assets/readme_images/GM-click-on-a-walk.jpg?raw=true "Using the Central Map as a start point")
![More details of a walk](./assets/readme_images/F13-Feature-Google-Map-direction-finder2.jpg?raw=true "More details of a walk")

Data created for the Arklow Trails website with Google MyMaps included:
* colour-coded walk polylines
* colour-coded startpoints, indicated by a P on the map which are a navigable element within Google
* hyperlinks to walk details within Arklow Trails website, this opens the 'walks detail' page at the relevant section in a new window.
(Note that, in implementing, I had intended to use a 3rd party URL shortener however I found that the shortened URL was intermittently disabled/blocked for my test users, so reinstated the longer URL.) 

### Features in Scope - refer to excel sheet for details of user stories (requirements) features and RTM.
This website includes 5 pages and 13 features 
Features are as listed in previous section.
The pages - which effectively bring these features together - are:
* Landing Page (image link)
* Walks detail page (image link)
* Gallery page (image link)
* Feedback page (image link)
* About page (image link)

- __Landing Page__
The initial website page shows a responsive google map at centre, surrounded by category cards for each of the walks.
This section introduces the user to the geographic territory of arklow and the map is useful to give an overview of the walk locations e.g.  seaside vs  inland.
There is very little text (header bar) displayed initially which means that language barriers are reduced and the site becomes very accessible to visually confident users.
This page has been designed to be responsive and to display correctly on different screen sizes.  

![Landing Page](./assets/readme_images/P01-Landing-Page.jpg?raw=true "Central Google Map with 3 walk flipcards either side")

- __Walks Page__
This page shows details of each walk, and is structured with hyperlinks so that focus can be moved directly to a walk of interest (for example when taking 'more details' from a flipcard, or from a google map.)
* Each walk shows a legend with consistent cateogries (distance, features, terrain, average review score)
* Each walk contains text-paragraphs description explaining some of the features of the walk, how it feels to walk it, what a person might see when they are following the route, any items of historical interest etc
* A photo carousel is shown per walk, this allows the user to click to start animation display of a number of stored photos.
* 'Latest review' with star rating is shown.

![Walks Page](./assets/readme_images/P02-Walk_Details.jpg?raw=true "Page with details for each walk")


- __Gallery Page__
- The gallery displays an attractive set of images taken from various walks - these are not matched against a particular walk, so it acts as a general gallery which showcases the entire locality.   This is valuable to all user personas.

Note that images shown in the gallery don't include people but instead highlight the landscape and walk features. 
It is intended that this be adopted as a policy, both to avoid any data protection issues and also to promote the walks themselves, rather than the people partaking in them.

![Gallery Page](./assets/readme_images/P03-Walk_Details.jpg?raw=true "Gallery")

- __Feedback page__ 
This page gives a first-time or returning-user the opportunity to contribute to the content of this site.  They can do this by uploading images, ratings or comments (or all 3!) for an existing or indeed a proposed new walk.

- - This page encourages the user to add their own reviews relating to various walks
  - and to upload their photos
  - and to add a star rating
  - the user must provide a username and email address in order to be permitted to upload photos.  They must also accept the terms and conditions.

![Feedback Page](./assets/readme_images/P04-Feedback.jpg?raw=true "Feedback")

### Features Left to Implement
Some of the user stories could be addressed more directly in the future: 
* Include suitability of various walks for dogs? - this has not really been expanded in the current setup, other than mentioning dogs on the walks details text.
* Include details to access guided walks and walking/running groups in the area?
* Moderation of user feedback - text and photos; and ability to upload this into the site content
* Scaling of site - this is currently implemented for a particular geogrpahic location, however the design and implementation principles followed mean that it would be possible to re-use much of the code, and, by creating fresh Google MyMaps digitised routes and updated walk details, to re-use this solution for a different territory.  This is definitely something i would like to investigate in the near future. 

### RTM
Requirements traceability matrix showing link between user stories and implemented/ future-release features

![stories vs features](./assets/readme_images/user-stories-checked-against-features.jpg?raw=true "Checklist of user stories and the features that implement them")

## Technologies

### Langugages
- HTML 
- CSS

### Frameworks & Tools
* Github
* Git
* Gitpod
* Balsamiq
* Google Fonts
* Font Awesome

## Validation 

### HTML Validation 
- HTML
  - No errors returned on the four website html pages when checked in the W3C validator:
  - [W3C validator - index page](https://validator.w3.org/nu/?doc=https%3A%2F%2Fdeemccart.github.io%2FCI_PP1_ArklowTrails%2Findex.html) 
  - [W3C validator - walks page](https://validator.w3.org/nu/?doc=https%3A%2F%2Fdeemccart.github.io%2FCI_PP1_ArklowTrails%2Fwalks.html) 
  - [W3C validator - gallery page](https://validator.w3.org/nu/?doc=https%3A%2F%2Fdeemccart.github.io%2FCI_PP1_ArklowTrails%2Fgallery.html) 
  - [W3C validator - feedback page](https://validator.w3.org/nu/?doc=https%3A%2F%2Fdeemccart.github.io%2FCI_PP1_ArklowTrails%2Ffeedback.html)
  
### CSS Validation
  - No errors returned when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https://deemccart.github.io/CI_PP1_ArklowTrails/&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)

### Accessibility
The site was tested using the WAVE WebAIM accessibility evaluation tool.
All pages pass with 0 errors
- [Accessability: index page](https://wave.webaim.org/report#/https://8000-deemccart-cipp1arklowtr-sigag7qpuok.ws-eu95.gitpod.io/index.html)
- [Accessibility: walks page](https://wave.webaim.org/report#/https://8000-deemccart-cipp1arklowtr-sigag7qpuok.ws-eu95.gitpod.io/walks.html)
- [Accessibility: gallery page](https://wave.webaim.org/report#/https://8000-deemccart-cipp1arklowtr-sigag7qpuok.ws-eu95.gitpod.io/gallery.html)
- [Accessibility:  feedback page](https://wave.webaim.org/report#/https://8000-deemccart-cipp1arklowtr-sigag7qpuok.ws-eu95.gitpod.io/feedback.html)

Running the accessibility checks against the index page identified a problem with the flipcards, which showed text and icons in white against a mid-blue background.  This was deemed insufficient contrast so was modified to black text against an aqua background (the same rgb as the header and footer). 
On the feedback page, there were file upload buttons which had no form label (multiple photo update buttons)
After making these changes there were no errors.

### Performance
Performance for all pages was tested using the Lighthouse tool within Google Chrome.  After adjusting image sizes, performance was at or above 90% for all pages.

<details><summary>Performance: Index page</summary>
<img src="https://deemccart.github.io/CI_PP1_ArklowTrails/assets/readme_images/performance-results-index-page.jpg">
</details>
<details><summary>Performance: Walks page</summary>
<img src="https://deemccart.github.io/CI_PP1_ArklowTrails/assets/readme_images/performance-results-walks-page.jpg">
</details>
<details><summary>Performance: Gallery page</summary>
<img src="https://deemccart.github.io/CI_PP1_ArklowTrails/assets/readme_images/performance-results-gallery-page.jpg">
</details>
<details><summary>Performance: Feedback page</summary>
<img src="https://deemccart.github.io/CI_PP1_ArklowTrails/assets/readme_images//performance-results-feedback-page.jpg">
</details>

### Device Testing
The website was tested on the following devices:
* HP laptop
* Samsung Galaxy S10 tablet
* Motorola G(7) android phone

### Multi-browser Testing
The website was tested on the following browsers:
* Google Chrome v112.0.5615.138 (HP laptop)
* Google Chrome v112.0.5615.136 (Samsung Galaxy tablet)
* Mozilla Firefox v112.1.0 (Motorola g(7) phone)

### Testing User Stories
![User story testing](./assets/readme_images/user-stories-checked-against-features.jpg?raw=true "testing user stories")



### Feature Testing
User Story Testing
The user feature testing is documented in a pdf file:
 https://deemccart.github.io/CI_PP1_ArklowTrails/assets/readme_images/user-feature-test.pdf

In addition, you should mention in this sectioning how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.


Requirements traceability matrix showing link between requirements and features
Provide proofs of successful testing of each user story### Unfixed Bugs
To be completed... mention unfixed bugs and why they were not fixed. This section should include shortcomings of the frameworks or technologies used. Although time can be a big variable to consider, paucity of time and difficulty understanding implementation is not a valid reason to leave bugs unfixed. 


## Deployment
This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub) 

* The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab - pages 
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

The live link can be found here - https://deemccart.github.io/CI_PP1_ArklowTrails/index.html


## Credits 
Multiple sources were used in assembling this site.

### Content 
* Text for the Glenart Woods walk was re-used from https://www.coillte.ie/site/glenart-wood/ some text lifted from here also
* Text for Arklow Nature Reserve walk was re-used from https://www.visitarklow.ie/post/4-family-friendly-trails-in-arklow-town-great-for-a-walk-cycle-or-scoot
* Inspiration and content for walks reviews was taken from https://www.alltrails.com/ireland/county-wicklow/arklow 
* The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)


### Media
Images not credited are developer's own.
* Moneylands Farm walk photos came from https://www.moneylandsfarm.com/
* Glenart photos from the following site were re-used https://www.coillte.ie/site/glenart-wood/
 
### Code
* Inspiration for the flipcards came from Elaine B Roche's Thrive project at https://elainebroche-dev.github.io/ms1-thrive/
* How to implement flip card functionality: sourced from W3schools ref https://www.w3schools.com/howto/howto_css_flip_card.asp*/
* For instructions on how to embed a responsive google map into html https://blog.hubspot.com/website/how-to-embed-google-map-in-html 
* Google mymaps for specific code to embed in the website
* https://www.w3schools.com/css/css_image_gallery.asp How to create an image gallery
* https://www.w3schools.com/howto/howto_css_flip_card.asp How to create a flip card using CSS
* https://www.w3schools.com/howto/howto_css_star_rating.asp creating review stars
* https://css-tricks.com/five-methods-for-five-star-ratings/ Used for representing review stars
* https://nikitahl.com/star-rating-with-css Simple star rating with pure CSS
* https://stackoverflow.com/questions/12316501/including-google-fonts-link-or-import


### References
Building this website involved a lot of learning for the developer, the following sites were used to assist with this:
* Understanding wireframes:  https://visme.co/blog/what-is-a-wireframe/
* How to wireframe a website https://www.youtube.com/watch?v=ZAYgDPtohYw Lily Creative
* What is the end-to-end UX process: https://uxdesign.cc/ui-ux-case-study-a-step-by-step-guide-to-the-process-of-designing-a-pet-diet-app-d635b911b648
* Embedding a google map: https://stackoverflow.com/questions/29441617/wordpress-google-map-in-background-overlay
* Understanding flex:  https://flexboxfroggy.com/
* CSS Grid vs Flexbox Acemind https://www.youtube.com/watch?v=RSIclWvNTdQ 
* Create a jump-link  https://blog.hubspot.com/marketing/jump-link-same-page 
* https://www.youtube.com/watch?v=p0bGHP-PXD4 Build a Responsive Website | HTML, CSS Grid, Flexbox & More   
* https://bulldogjob.com/readme/how-to-write-a-good-readme-for-your-github-project
* https://chat.openai.com/chat 'What should a readme file for a website include?'
* https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Organizing Tips to keep your CSS tidy

For ideas on hosting a trails website and for certain photos and images:
* For some ideas on local attractions:  https://www.arklowmaritimeheritage.ie/
* For examples of feedback from users: https://www.sportireland.ie/outdoors/walking/trails/ 
 
### Acknowledgements
* I would like to sincerely thank my mentor, Mo Shami for his patience and support throughout.
* I would also like to thank Derek for his support and keeping everything running at home.
