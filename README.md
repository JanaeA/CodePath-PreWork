# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Janae Anderson**

Time spent: **2** hours spent in total

Link to project: https://amenable-petal-existence.glitch.me/

## Required Functionality

The following **required** functionality is complete:

* [■] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [■] "Start" button toggles between "Start" and "Stop" when clicked. 
* [■] Game buttons each light up and play a sound when clicked. 
* [■] Computer plays back sequence of clues including sound and visual cue for each button
* [■] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [■] User wins the game after guessing a complete pattern
* [■] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [ ] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
* [ ] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [ ] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough

Here's a walkthrough of implemented user stories:
![](https://i.imgur.com/2wBO5FO.gif)
![](https://i.imgur.com/RluftUO.gif)



## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
[N/A]

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
[One challenge I encountered was misunderstanding the guess function. I was stuck on this part for a few minutes as I had taken on the challenge of writing the guess function on my own. One issue I had not considered was that the guessCounter variable resets after each play clue sequence. I was missing an entire chunk of the guess function. However, I was able to figure it out after reviewing the code, and my code matched up your version of the guess function.]

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
[Some questions I have about web development are what general user experiences do you have to keep in mind when creating web pages? As I am currently developing VR games, I have to take into consideration user comfort, and ensure that the VR program does not cause discomfort or motion sickness. Although web development is not as interactive and immersive as VR, what are some of the challenges web developers face when creating web pages?]

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
[If I had a few more hours to work on this project, I would add more difficulties and an anti-cheat method. I discovered that you are able to click the buttons as they light up and it counts. I would add a boolean that disables the buttons when they are in the process of lighting up. Overall, I would redesign the webpage to something towards my personal style.]



## License

    Copyright Janae Anderson

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.