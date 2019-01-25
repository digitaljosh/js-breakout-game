# js-breakout-game
A simple MDN Breakout game written entirely in pure JavaScript and rendered on HTML5 &lt;canvas>.

The original game used "document.location.reload()" method when a player won or lost the game and would refresh the page. Since I wanted to embed this game in a landing page with other games and elements I didn't want a full page reload every time someone played. My workaround for this involved creating a reset() function that called a reloadVars() function that reset all global variables to their initial value and added the overlay to the canvas - which serves as the game title and a 'start game' button. 

I added a random color generator for the bricks and a random starting trajectory (right or left) for the ball. Since I used a custom image for the ball, I had to offset the x and y position to match the image. Originally the game's x and y position were at the center of the ball but I offset this to be at the top. As you play, you will notice this in how the ball behaves when it collides and "breaks" the bricks.

# [PLAY THE GAME](http://htmlpreview.github.io/?https://github.com/digitaljosh/js-breakout-game/blob/master/index.html) 

Tutorial Link:
https://developer.mozilla.org/en-US/docs/Games/Tutorials/2D_Breakout_game_pure_JavaScript

![bg-breakout-screenshot-1](https://user-images.githubusercontent.com/25624304/48646040-2b4ed200-e9ad-11e8-8eeb-75e015145097.JPG)

![bg-breakout-screenshot-2](https://user-images.githubusercontent.com/25624304/48646045-3144b300-e9ad-11e8-9a0f-1368a44533f2.JPG)

