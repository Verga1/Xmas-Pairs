# XMAS PAIRS

This project is a simple yet challenging memory game with a user-friendly design. The goal of the project is to create a game
that is both fun and challenging for users of all ages. The game will shuffle the cards at the start of each game and have a time limit to beat.

## UX

### **Goals:**
* To create simple matching pairs game accessible to anyone 

* To have a loss condition in order to encourage repeat engagement from players

### **User Stories**

> Gary: I like to play games as a time killer when commuting

> Amy: I play quick games while waiting on my bus to pass the time

All the users gave similar replies. For them a simple game like Xmas Pairs 
wasn't something they would commit a lot of time to but looked to play when they 
were trying to pass time. This informed the game design in that it made clear 
that the game needed to be easy to stop and started very easily and have a 
goal which could be achieved in a short space of time. 

* The overlay screen can be clicked to immediately start the game
* The timer starts to countdown from 60 Seconds upon activation
* The card is flipped to reveal a picture upon being clicked
* A second card is then flipped to see if picture matches
* If the picture matches the cards remain flipped and a sound of jingle bells play
* If the cards don't match they flip back over and can be chosen again
* Play continues until all macthes are made or the timer runs out

### **Strategy**

The aim was to create a very simple site that focused on the gameplay. A memory
game using Christmas themed cards to make it accessible to all ages.

### **Scope**

Originally there were going to be a choice in difficulty from easy, medium and hard. 
The aim was that this would appeal to a wider audience who could commit their time 
and energy to a difficulty that suited them at any moment. Due to time the harder
difficulties were ommited leaving the base game which is accessible to anyone.

### **Structure**

The site has three overlays and the main playing page. The initial overlay can be clicked in order for the game to begin.
This opens the game page. The page contains 16 cards with 8 matching pairs. A countdown timer and flip counter are also included.
There are two other End Game overlays if the player wins, or loses. Both can be clicked in order to restart the game.

### **Skeleton**

[Here](https://github.com/Verga1/Xmas-Pairs/tree/master/wireframes) are the designs I made for the site.

The wireframes were made using [Balsamiq](https://balsamiq.com/)

### **Surface**

- **Font**: I wanted to use a single font throughout the site, it needed to look "festive" to fit in with the Christmas theme, with this in mind I decided to use [Mountains of Christmas](https://fonts.google.com/specimen/Mountains+of+Christmas#glyphs) from [Google Fonts](https://fonts.google.com/).

- **Colours**: I used red, white and 2 different shades of green to keep a Christmas style throughout.



## FEATURES

 - Game Instructions: Tells users how to play the game.
 - Music: Xmas theme plays when you begin the game.
 - Game Timer: When the game starts a timer begins counting down from 60 when it hits zero the game is over.
 - Move Counter: Counts how many moves a user makes while playing.
 - Game Over Screen: When the timer hits zero the game over screen will appear allowing the users to try again.
 - Victory Screen: When the user has found all 8 matches before the time runs out the Victory screen will appear showing their score and allowing them to play again.
 - Defense Function: The game will not allow cards to be flipped if there is a card animation taking place.
 - Defense Function: The game will not allow a card to be flipped if it is part of a matched pair.
 - Defense Function: The game will allow the same card to be flipped back to hidden until a second card has been selected to check for a match.

 ## TECHNOLOGIES USED

- HTML:
This project uses HTML5 to provide the content and structure.
- CSS:
The project uses CSS3 for styling.
- Gitpod:
This project was developed using Gitpod as the IDE.
- GitHub:
The project uses GitHub to host the repository and for the live preview of the site
- Google Fonts:
The project uses Google fonts to style the website fonts.
- Javascript:
The project uses JavaScript for game functions.


 ## TESTING

 ## DEPLOYMENT

This project was developed using the Gitpod IDE, committed to git and pushed to GitHub using the built in function within Gitpod.

To deploy this page to GitHub Pages from its GitHub repository, the following steps were taken:

1. Log into GitHub.
2. In the list of repositories on the screen, select XMAS Pairs.
3. In the menu items near the top of the page, select Settings.
4. Scroll down to the GitHub Pages section.
5. Under Source select the drop-down menu labelled None and select Master Branch
6. The Master Branch automatically refreshes the page, the website has now been deployed.
7. Scroll down to the GitHub Pages section in order to retrieve the link to the deployed website.



### Run the project locally

Clone this project from GitHub:

1. Click for the [GitHub repository].
2. Near the top of the page, click the green button "Clone or download".
3. In the Clone with HTTPs section, copy the clone URL for the repository.
4. In your local IDE open Git Bash.
5. Change the current working directory to the location where you want the cloned directory to be made.
6. Type git clone, and then paste the URL you copied in Step 3.
7. Press Enter. Your local clone will be created.

Further details on cloning a repository can be found on [GitHub](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository).

## CREDITS

### Content

 - I achieved the base game functionality by following this tutorial by [PortEXE](https://youtu.be/3uuQ3g92oPQ).
 - The game uses the [Fisher-Yates shuffle](https://en.wikipedia.org/wiki/Fisher%E2%80%93Yates_shuffle) to shuffle the cards.

 ### Media

 - The background music was made by [Ashamaluevmusic](https://soundcloud.com/ashamaluevmusic).
 - Sound effects were made by [Soundbible](https//:www.soundbible.com) and [Shockwave-sound](https://www.shockwave-sound.com/).
 - The card icons were made by [Pixelperfect](https://www.flaticon.com/authors/pixel-perfect).

## Acknowledgements
 - I received inspiration for this project from [WebDevSimplified](https://www.youtube.com/channel/UCFbNIlppjAuEX4znoulh0Cw) and [PortEXE](https://portexe.com/) on their [Mix-Or-Match](https://youtu.be/3uuQ3g92oPQ) project.
