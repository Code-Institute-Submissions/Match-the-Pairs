Milestone Project 2

# Match the Pairs

This website is my second project after the culmination of studying the fundamentals of JavaScript and interactive frontend development including jQuery. 

## UX

This website was developed in order to allow the user to play a classic game of matching the pairs. I selected a Pokemon theme as the images for my cards, as it allowed me to have images on the front and back of the cards that were linked.

[Link to images folder to view wireframe initial sketches](https://github.com/JonWil91/Milestone-project-1/tree/master/images)

The final design of the website follows the original sketches made at the start of the development process. As it was only a website with one page I did not wish to overcomplicate it, and it was evident that the design worked well for desktop, and the sidebar feature layout had to be amended approriately for mobile and tablet users.

## User stories:

As a user I want each click of a card to provide a response.

As a user I want the page to have a clear purpose, and be engaging and dynamic.

As a user I want the cards to be arranged differently each time I use the website to keep the game entertaining.

## Features

The layout for the single page for the website is responsive to mobile, tablet and desktop users to ensure the most enjoyable experience.

### Sidebar:

The sidebar has a title image of the popular Pokemon series, this was not created by myself and was taken from google; the source will be referenced at the bottom of the readMe file. Below this title is a text box which contains a brief explanation of the goal of the game, giving instruction on how to play. Once the user has clicked the Start Game option a timer would then begin until they finish the game. Below this button is also a refresh button if the user wishes to start the game again at any point during play.

### Game body:

The game body consists of 16 cards, these are spread evenly across the page with the Pokeball image on the back facing side, and a number of Pokemon images on the other side which are revealed when clicked. When clicking cards to find pairs it is only possible for two cards to be selected in turn, if these cards are a pair they remain turned over, if not the card is turned back around. When the final pair is matched a victory div covers the screen, stating the time taken to complete the game and the option to click to restart the game.

### Additional features to be implemented:

* I would like to add audio to the page to play the well known Pokemon theme tune, there would be an option to mute this audio.
* I would like to add the option to select three different difficulties to vary the game
* There is currently a bug which allows users to select both cards with a double click which needs to be debugged, the game functions appropriately with a single click however
* 

## Technologies Used

1. HTML
2. CSS
3. JavaScript
4. GitPod was the IDE used in the development of building this website.
5. Bootstrap4 was used to aid the development process in the layout and responsiveness of the website.
6. jQuery framework was used in conjunction with Bootstrap4 to refer to JavaScript technologies used to improve the efficiency of the website. It was used to make the navbar dropdown and the accordion effect on the seaonal page responsive for mobile users.
7. Google Fonts
8. Font Awesome

## Deployment

The website was developed using the GitPod IDE, a new repository was created using the Code Institute reccomended template for GitPod. From GitPod it was possible to make commits and push changes onto GitHub.

1. Log into Github.
2. Select Milestone2-ii from JonWil91 repository
3. Select the settings option from the top right
4. Sroll down to GitHub pages, and select master branch as Source
5. Upon giving GitHub a few moments to complete the task, the website was refreshed and it was possible to select the live link for the website under GitHub Pages.
