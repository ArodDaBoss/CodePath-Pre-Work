1. f you used any outside resources to help complete your submission (websites, books, people, etc) list them here.

HTML color codes. HTML Color Codes. (2015, September 3). Retrieved March 22, 2022, from https://htmlcolorcodes.com/

Math.random() - javascript: MDN. JavaScript | MDN. (n.d.). Retrieved March 22, 2022, from https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/random

ELEMENT.INNERHTML - web apis: MDN. Web APIs | MDN. (n.d.). Retrieved March 22, 2022, from https://developer.mozilla.org/en-US/docs/Web/API/Element/innerHTML

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words)
   Since I had some recent experience with programming languages, it wasn't that much of an obstacle to understanding the
   function and logic implemented. Although puzzling at first sight, the supplemental instructions on each function and how
   they're implemented helped tremendously with comprehension. The most troubling encounter I had with this entire project was
   using the console.log to verify outputs, for some reason glitch wouldn't give me access to the web console. As a result, I
   had to test code from an alternative program: Visual Studios.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words)
   While attepmting this project, I started to wonder what types of unspoken convention are expected when web-developing. While designing,

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words)
   With the past experience I had with javascript, css, and html, I took it upon myself to employ these skills to make an even better game that employed more interactive features!

Randomize patterns -
To achieve this goal I had to make a random number function bounded by the interval [1,5] for one single element.Next I implemented the random number function into another function that would generate a pattern array of length 8 filled with a random number bounded by [1,5].

Add another button to the game -
I used a sample of the code from the base game to make a 5th button. Such as the button tags and style. I then add a 5th key into the freqMap directory. Very simple.

Live counter -
I wanted to give the player multiple try to attempt the pattern For that, I knew I had to keep in track of the number of guess. As such, I made a variable named numOfLIves. Once the game is started I set the numOfLives to 3. Then I created a function named liveCnt, which is called whenever the player guesses incorrectly and keeps track of how many lives the player has.
To display the number of lives a player has, I had to make a new empty paragraph tag with an id name numOfLives. I then used the getElementById("numOfLives").innerHTML to display the number of lives to the players.
