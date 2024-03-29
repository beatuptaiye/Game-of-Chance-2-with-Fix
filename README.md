# ROCK, PAPER, SCISSORS, LIZARD, SPOCK GAME
## Project Overview
* For enthusiasts of Big Bang Theory, this variation of the traditional rock, paper, scissors game, crafted with JavaScript, aims to offer entertainment for those seeking a brief respite, whether at home or work. The platform enables players to engage with Sheldon Cooper, incorporating 'lizard' and 'spock' as supplementary options.![fullscreen](https://github.com/beatuptaiye/game-of-chance/assets/64757307/6cf39740-84bf-4535-8849-6470eaf7ab99)
![Screen Shot 2024-03-29 at 12 24 53](https://github.com/beatuptaiye/game-of-chance/assets/64757307/415167d3-fd66-4578-933c-a71352c2789a)
![Screen Shot 2024-03-29 at 12 24 40](https://github.com/beatuptaiye/game-of-chance/assets/64757307/d05f00ed-80d2-471c-9d6c-3b2342b1e50e)


## TABLE OF CONTENTS
- [ROCK, PAPER, SCISSORS, LIZARD, SPOCK GAME](#rock-paper-scissors-lizard-spock-game)
  - [Project Overview](#project-overview)
  - [TABLE OF CONTENTS](#table-of-contents)
  - [UX](#ux)
    - [Project Goal](#project-goal)
  - [DESIGN CHOICES](#design-choices)
    - [Colors](#colors)
    - [Typography](#typography)
    - [Images/Icons](#imagesicons)
    - [Animations](#animations)
    - [Responsiveness](#responsiveness)
  - [FEATURES](#features)
    - [Play Area](#play-area)
    - [Game Score Area](#game-score-area)
    - [Game Controls](#game-controls)
    - [Game Rules](#game-rules)
    - [Feedback Form](#feedback-form)
    - [Footer](#footer)
    - [Error](#error)
    - [Features for Future Development](#features-for-future-development)
  - [TESTING](#testing)
    - [Validation Testing](#validation-testing)
    - [Testing User Stories from User Experience (UX) Section](#testing-user-stories-from-user-experience-ux-section)
    - [Outstanding Defects](#outstanding-defects)
    - [Defects of Note](#defects-of-note)
  - [ACCESSIBILITY](#accessibility)
    - [Lighthouse Audit](#lighthouse-audit)
    - [Keyboard Navigation](#keyboard-navigation)
  - [DEPLOYMENT](#deployment)
  - [CREDITS](#credits)
    - [Media](#media)
  - [ACKNOWLEDGEMENTS](#acknowledgements)


## UX

### Project Goal
* The project goal is to create a fully functioning and responsive game using JavaScript.

## DESIGN CHOICES

### Colors
- The space background image inspired the color palette of the website and links to the theme of the game. 
- The headings and body text are white to ensure clear contrast and readability for the user.
- Background of the header and footer is a light purple to ensure clear contrast and delineation between sections.
- All text and icon elements have a semi-transparent purple background to ensure the text has contrast from the background.
- The icons are green to add contrast from the purple palette.

### Typography
- The logo and headings use ZCOOL QingKe HuangYou and body text uses Open Sans with a fall-back font of san-serif.
- The choice of fonts were selected using [Google Fonts](https://fonts.google.com/).
- The headings decrease in size to ensure full responsiveness of the website.

### Images/Icons
- The background image matches with the space theme of the game and creates a sense of depth without disrupting the foreground.

<img width="638" alt="image" src="../game-of-chance/assets/images/pexels-jakub-novacek-924824-min.jpg">

- The rules video provides a clear diagram of the game moves and results.

- The icons are used consistently across the site for game controls and in the rules.
<iframe src="https://www.youtube.com/embed/aQ1Nmxp55ms?si=IX3Sthk0mNt6M54U" width="560" height="315" title="A Youtube Video explaining the rules of Rock, Paper, Scissors, Lizard, Spock Game" allowfullscreen></iframe>

### Animations
- The buttons across the site have a subtle grow effect when hovered over by the user.

### Responsiveness
- The website was designed using flexbox instead of float or grid to avoid fixed heights and ensure responsiveness throughout the website.

## FEATURES

### Play Area
- The users are greeted with a menu allowing them to either play the game or read the rules first.
- The close and quit buttons help to easily navigate between areas of the website.
### Game Score Area
- The game score area shows the icons of each user and their move. The score increments and a message is displayed to show the user the result of their move.


### Game Controls 
- The controls are buttons with hand icons to easily distinguish between each control.
- If on a smaller screen size, the buttons will respond by stacking on each other.


### Game Rules
- The user has a choice of image or info graphic table to refer to when learning the moves.



### Feedback Form
- This is to collect feedback from the user


### Footer
- This footer includes links to the relevant social media sites for game development group who created the site. The links will open to a new tab to allow easy navigation for the user.
- First time users and returning users will be able to connect with players via social media.


### Error
- This page was created in case of any broken links or issues. It is styled the same as the rest of the site for familiarity for the user.
- The page includes the navigation which will allow the user to go back to the home page or any page they were previously on.


### Features for Future Development
- Future opportunities for the game include adding a high score function to be able to compete with other users and allowing scores to be saved once a user returns to play again.
- Audio for the game when a user wins or loses can add more interest.
- Adjusting the 'It's a win/lose/tie' text to be insults from Sheldon Cooper himself.

## TESTING

### Validation Testing
- HTML
   - No errors were returned when passing through the official [HTML validator]("https://validator.w3.org/nu/?doc=https%3A%2F%2Fcaramcavinchey.github.io%2Frock-paper-scissors%2F")



- CSS
   - No errors were found when passing through the [CSS validator]("https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fcaramcavinchey.github.io%2Frock-paper-scissors%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en").


- JS validation
   -  No errors found when passing through the JS validator.



### Testing User Stories from User Experience (UX) Section

**First time visitor:**
1. As a first time visitor, I want to be able to play the game quickly and learn the rules fast. The rules need to be clear to understand and easy to refer back to.
   1. The welcome area with the menu will allow users to navigate the page quickly and easily as needed.
   2. The rules are displayed both as a visual and infographic grid.
  
**Returning visitor:**
1. As a returning visitor, I want to be able to start playing the game once I load the page with very few clicks. If I forget the rules, I want to be able to refer back to the rules quickly. 
   1. The close and quit buttons will help users navigate between the rules and game area.


### Outstanding Defects
- The footer doesn't remain fixed at the bottom of the site on all screen sizes, this isn't obvious to the user and doesn't clash with other elements. This will be fixed in future debugging.
- The Form scrolls down on all devices

### Defects of Note
1. The resizing of the game section for smaller screen sizes had many challenges. Flexbox solved most of the issues using media queries.

## ACCESSIBILITY

### Lighthouse Audit
- The deployed website was run through [web.dev measure](https://web.dev/measure/) to check performance, accessibility, best practices and SEO scores.
 


### Keyboard Navigation
- The user will be able to use the tab, arrow and enter keys if needed when navigating the website.

## DEPLOYMENT
The site was deployed to GitHub pages. The steps to deploy are as follows: In the GitHub repository, I navigated to the Settings tab From the source section drop-down menu, select the Master Branch Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. The live link can be found here (https://beatuptaiye.github.io/game-of-chance/)


## CREDITS
- This game was built with the guidance and source code from [Mehdi Aoussiad](https://javascript.plainenglish.io/building-a-rock-paper-scissors-game-with-javascript-bce23d39509d)
- and source code from [CaraMcAvinchey](https://github.com/CaraMcAvinchey/rock-paper-scissors).
- Code Institute Student Template: [gitpod full template](https://github.com/Code-Institute-Org/gitpod-full-template).
- I had help from had help from w3schools, stack overflow and the code institute lessons and ChatGPT and some youtube videos

### Media
- The pairing of ZCOOL QingKe HuangYou and Open Sans were chosen using [Google Fonts](https://fonts.google.com/). 
- The colors for the website was generated using [Coolers.co](https://coolors.co/image-picker).
- The background image was sourced using [Pexels](https://www.pexels.com).
- The game rules image was sourced using [Creative Commons Search](https://openclipart.org/detail/325665/rock-paper-scissors-lizard-spock).
- The icons for the favicon, footer, about page and location headings were taken from [Font Awesome](https://fontawesome.com/).
- The favicon image was converted using [Favicon.io](https://favicon.io/).
- Video was gotten from youtube [wikiHow] (https://youtu.be/aQ1Nmxp55ms?si=q8He1rw3CEKPrMfy)

## ACKNOWLEDGEMENTS
- Thank you to my mentor for continuous helpful feedback and support throughout the project.
- The tutors at Code Institute for their patience and support.
- The Code Institute Slack community for tips and guidance.

[Back to the beginning](#table-of-contents)
