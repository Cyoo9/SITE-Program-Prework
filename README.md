# Pre-work - _Memory Game_

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program.

Submitted by: **Caleb Yoo**

Time spent: **8** hours spent in total

Link to project: (insert your link here, should start with https://glitch.com...)

## Required Functionality

The following **required** functionality is complete:

- [x] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
- [x] "Start" button toggles between "Start" and "Stop" when clicked.
- [x] Game buttons each light up and play a sound when clicked.
- [x] Computer plays back sequence of clues including sound and visual cue for each button
- [x] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess.
- [x] User wins the game after guessing a complete pattern
- [x] User loses the game after an incorrect guess

The following **optional** features are implemented:

- [x] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
- [x] Buttons use a pitch (frequency) other than the ones in the tutorial
- [x] More than 4 functional game buttons
- [x] Playback speeds up on each turn
- [x] Computer picks a different pattern each time the game is played
- [x] Player only loses after 3 mistakes (instead of on the first mistake)
- [x] Game button appearance change goes beyond color (e.g. add an image)
- [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
- [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough

Here's a walkthrough of implemented user stories:
https://github.com/Cyoo9/SITE-Program-Prework/blob/main/lightsoundmemorygame.gif
## Reflection Questions

1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here.
   [https://www.w3schools.com/cssref/css_colors.asp][https://stackoverflow.com/]

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it?
   [My game kept bugging when I used Math.random() with Math.floor to get numbers between 1 - 6. The keys wouldn't play
   and it was very annoying to work with. I ended up getting rid of random patterns because my game wouldn't run correctly.
   Manually inputting the pattern fixed all the bugs so there was a problem with how the Math.random() and Math.floor() functions
   were interacting with my program. I later realized this caused another problem, I was losing every 3 rounds. I spent hours looking
   at what I did wrong and it was in the guess() function. I had an immature understanding of guessCount. When I first saw the algorithm
   in the guess() function, I didn't think guessCount meant the index of the CORRECT box. I just thought it was counting the number
   of user guesses when really, it was keeping track if the user was selecting the correct button. After fixing this, I ran into another
   problem where my notes were speeding up too fast and cutting off. I fixed this by decreasing the intervals I was using to shorten the
   hold time. I also had a problem displaying a coffee image I wanted since it was too big and out of frame to fit in the box. I used another
   image that split into different shards which was enough for me. ]

3. What questions about web development do you have after completing your submission?
   [I am curious if HTML, CSS, and Javascript are really the perfect triplet and if those are all we need (excluding frameworks). It seems that
   a lot of high processing websites require more than just these three, but at the same time it is amazing to see what mark up languages and 1 programming language can do.
   I am also curious about how algorithms play in speed and efficiency in web development. I am very new to web development and started taking a course on database management systems which
   is helping me grasp knowledge of query languages such as SQL. I know that websites reqiure their data to be stored and query languages such as SQL does the job in the backend. This project, however, was more of a
   front-end project and I really liked how I was able to see the interaction between HTML, CSS, and Javascript. I am still quite confused on how Javascript, HTML, and CSS interact together. Especially HTML and Javascript
   because the id in HTML somehow gets noticed by Javascript kind of like referencing objects in OOP programming languages, but in a different aspect. ]

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words)
   [I would definitely add additional features by studying the JS documentation for certain capabilities of the language. I will also do this with HTML and CSS to make the design better and organized.
   Organization can also be done by refactoring certain functions in script.sql. Specifically, I would design each box differently, maybe add some text inside, and possibly create a 2-player game with this if given enough time.
   I would also keep a scoreboard to see who used the least amount of chances and create a lot of levels. For instance, at the max level, the pattern will be so fast it will be hard to memorize it. 

## License

    Copyright [Caleb Yoo]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
