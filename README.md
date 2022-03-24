# Pre-work - _Memory Game_

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program.

Submitted by: **Suhas Prasad**

Time spent: **3** hours spent in total

Link to project: https://glitch.com/edit/#!/handsome-wide-base

## Required Functionality

The following **required** functionality is complete:

- [X] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
- [X] "Start" button toggles between "Start" and "Stop" when clicked.
- [X] Game buttons each light up and play a sound when clicked.
- [X] Computer plays back sequence of clues including sound and visual cue for each button
- [X] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess.
- [X] User wins the game after guessing a complete pattern
- [X] User loses the game after an incorrect guess

The following **optional** features are implemented:

- [X] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
- [X] Buttons use a pitch (frequency) other than the ones in the tutorial
- [ ] More than 4 functional game buttons
- [ ] Playback speeds up on each turn
- [X] Computer picks a different pattern each time the game is played
- [ ] Player only loses after 3 mistakes (instead of on the first mistake)
- [ ] Game button appearance change goes beyond color (e.g. add an image)
- [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
- [ ] User has a limited amount of time to enter their guess on each turn


## Video Walkthrough (GIF)

//For some reason there is a lag in the GIFs that I can't get rid of -- it skips recorded clicks which might make it seem faulty, however 
my implementation is correct. Also, the Win/Loss dialog box is not captured due to it being outside the screen window.

If you recorded multiple GIFs for all the implemented features, you can add them here:
![](https://cdn.glitch.global/bd028b23-fb63-4672-80ee-c87b0cc909ce/game.gif?v=1648081059155)
![](https://cdn.glitch.global/bd028b23-fb63-4672-80ee-c87b0cc909ce/gameWin.gif?v=1648081268428)


## Reflection Questions

1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here.
   
   I did not use any outside resources

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words)
   
   The project was mostly straightforward, and I didn't encounter any significant difficulties. However, there were a couple areas I had to work around in order
   to get the game to work would be the randomization part -- an initial mistake I had made was calling the function that randomized the pattern inside a 
   recurring function in the program. As a result, the pattern would keep changing throughout the game which resulted in crash and made the game pointless. 
   A quick fix to this was to insert the call in the game initialization function so it would be called only once. Another such small error I initially made was
   when I 

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words)
   
   I understand that CSS and HTML requires a significantly more artistic and detailed form of typesetting compared to
   Javascript. However, the code can really get long and mindboggling to debug. I learned to use IDEs to debug Java programs
   by stepping into functions and setting breakpoints. Is there a similar precision approach to debugging errors in webdev?
   In particular, is there an easy way to view what each element does similar to the inspect element HTML page, where hovering over a segment highlights the impacted area?

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words)
   
   A couple additional features I would add are:
   
   1) Making a menu where you could choose difficulty level. Parameters that I would change based on difficulty would include the speed of the pattern replay, and 
   removing the incremental replay feature which would make the game more challenging.
   
   2) A game mode where the buttons scramble on each click, forcing you to remember the color played as opposed to memorizing the position.
   
   3) An HUD feature which would display the score, time elapsed, number of tries/lives left etc.



## Interview Recording URL Link

[My 5-minute Interview Recording](https://drive.google.com/file/d/1HHvCLXSd6K8dRAvrT_yYR0RaqFTY1047/view?usp=sharing)


## License

    Copyright Suhas Prasad

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
