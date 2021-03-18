# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Vinny Ngo**

Time spent: **4** hours spent in total

Link to project: [https://glitch.com/edit/#!/prework-vinny-ngo](https://glitch.com/edit/#!/prework-vinny-ngo)

## Required Functionality

The following **required** functionality is complete:

* [x] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [x] "Start" button toggles between "Start" and "Stop" when clicked. 
* [x] Game buttons each light up and play a sound when clicked. 
* [x] Computer plays back sequence of clues including sound and visual cue for each button
* [x] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [x] User wins the game after guessing a complete pattern
* [x] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [x] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [x] Buttons use a pitch (frequency) other than the ones in the tutorial
* [x] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [x] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough

Here's a walkthrough of implemented user stories:

![](https://i.imgur.com/evdk6A1.gif)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

    https://www.w3schools.com/cssref/css_colors.asp
    https://www.w3schools.com/js/js_random.asp
    https://www.w3schools.com/js/js_arrays.asp

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

    The only challenge that I encountered in creating this webiste would be handling the game logic. Throughout the entire program, I have just been following instructions and the game logic was the one part where I had to figure it out myself. My first tries at coding the game logic were filled with errors and I had to rewrite it multiple times. One of my tries included using a "for" loop to increment the guessCounter, which did not work out. After scrapping that idea, I revisited the problem and noticed that there was a hint about using nested conditional statements. After using "if" statements into "if" statements, my code was still putting up an error. I cut my code out and tried to figure out what went wrong. After a few moments, I noticed that I removed the end bracket "}" for the function. As a result of putting the end bracket back in, my code worked successfully. Overall, the program was mostly about following instructions and the only problem was solved using nested loops and rechecking the formatting.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

    A question I have about web development is how complex will the work be. Through this pre-work, I have been introduced to web development and my experience hasn't been too overwhelming. I am interested to learn what is possible when making a website and I am interested in the different ways I could improve my code to make it run faster and look cleaner. I also have a question about the "assets" folder that I saw while doing the pre-work in glitch.com. I wonder about the purpose of the folder and how to use it. 

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
    
    If I had a few more hours, I would spend my time adding additional features. Some additional features would adding a separate button for endless mode and a score counter. If I had more time, I could also make the website look cleaner by centering the text and the buttons. I could also add different levels of difficulty. For example, the easy difficulty would be characterized by 3 buttons and a pattern length of 5. The hard difficulty would be 7 buttons and a pattern length of 15. I could also add an easter egg where, without starting the game, the user clicks the buttons in a certain order and a surprise happens. 



## License

    Copyright [Vinny Ngo]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.