# Pre-work - *Memory Game*

**Light And Sound Memory Game Simon** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Ramyar Daneshgar**

Time spent: **6** hours spent in total

Link to project's live site: https://zigzag-meadow-client.glitch.me
Link to project's code: https://glitch.com/edit/#!/zigzag-meadow-client

## Required Functionality

The following **required** functionality is complete:

* [x] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [x] "Start" button toggles between "Start" and "Stop" when clicked. 
* [x] Game buttons each light up and play a sound when clicked. 
* [x] Computer plays back sequence of clues including sound and visual cue for each button
* [x] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [x] User wins the game after guessing a complete pattern
* [x] User loses the game after an incorrect guess


The following **additional** features are implemented:

- [x] Change background, headling, and body text color within the game.

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
![](gif1-link-here)
![](gif2-link-here)
![](gif3-link-here)
![](gif4-link-here)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

  Outsuide resources I used to help complete my submission are Stackoverflow and Glitch documentation.

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

As this was my first time using HTML, CSS, and Javascript, I spent more time understanding the algorithm of the game by reading the code written in the instructions. For example, I was interested in how the “playCueSquence()” function worked. I now understand that variable “delay” is initialized for wait time between increments as we don’t want all clues to play at the same time. A for-loop is used to increment the sequence with a “pattern” array referencing the “i” element to determine the next clue. Additionally, I took interest in understanding syntax and how HTML, CSS, and Javascript work together in the context of web development. I learned that HTML provides the structure, CSS provides styling / formatting, and JavaScript provides behavior to specified elements. This was especially evident when I was creating the start/stop and the four in-game buttons. Specifically, I saw how the “lightButton” function calls arguments, passes them to function with arguments value replacing the parameter variable, then body of function executing respectively.  At the end of the project, I look into debugging using console logging in browsers developer tools. In doing so, I was able to better understand what is happening in real time as the program executes. 


3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

After completing my submission, I'm now interested in learning the server-side of web development which uses various technologies such as. NET, PHP, Ruby, and Node. js. I would like to gain further understanding of frameworks associated with front-end and back-end web development. Additionally, I would like to further take into account how code can be used to help optimize for page speed/performance, security, and ease of use. Importantly, I would like to further learn how to approach web development with accessibility for users with disabilities in mind. This ensures that the game remains “perceivable, operable, understandable, and robust” as indicated by the Web Content Accessibility Guidelines. 


4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

If I had more hours to work on this project, I would spend time implementing control options where the user can adjust game dynamics to their preference. This could include multiplayer capacity that encourages users to challenge their friends. By inspiring competition and indicating progressive achievement through a leaderboard system, the website could potentially grow on it’s own through network effects. The intrinsic motivation of rewards could also help with user retention correspondingly, as the goal of winning the “next level” of the game seems achievable the more the user continues to play the game. Additional features could include allowing users to play in dark or light mode modality.



## Interview Recording URL Link

[My 5-minute Interview Recording](your-link-here)


## License

    Copyright [Ramyar Daneshgar]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
