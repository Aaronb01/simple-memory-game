**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program.

Submitted by: Aaron Barker

Time spent: 9 hours spent in total

Link to project: https://glitch.com/edit/#!/marred-plump-sceptre
Link to site: https://marred-plump-sceptre.glitch.me/

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
- [ ] Game button appearance change goes beyond color (e.g. add an image)
- [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
- [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:

### Starting the game

![](https://cdn.glitch.global/8f086169-729f-4a39-a182-25aaf71a6f9e/ezgif.com-gif-maker.gif?v=1647820551615)

### Winning the game

![](<https://cdn.glitch.global/8f086169-729f-4a39-a182-25aaf71a6f9e/ezgif.com-gif-maker%20(1).gif?v=1647821269972>)

### Losing the game

![](<https://cdn.glitch.global/8f086169-729f-4a39-a182-25aaf71a6f9e/ezgif.com-gif-maker%20(2).gif?v=1647821894678>)

## Reflection Questions

1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here.

   https://html-color.codes, https://www.w3schools.com

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words)

   There were a few challenges I faced while developing this game, most of them being easily fixed. There were
   mostly syntax errors while in CSS from either spelling a keyword incorrectly or forgetting a semi-colon. The syntax
   errors that happened while I was in CSS were always easy to fix, all I had to do was take a closer look at the line that caused
   the error to occur and fix the minor mistake. While using HTML I didn’t have many issues besides all of the extra code the glitch
   website added that I had no use for. When I first started on the webpage, I didn’t delete all of the added code which caused a major
   bug in my program while trying to run the game. The error was that the program was only taking the last two buttons pressed as
   the correct answer to that pattern, so when the game got to the third pattern where you were supposed to click the three buttons that
   lit up it would end the game if you didn’t press the last 2 buttons of the pattern and did this all the way through the game. This was
   a major bug and I wasn’t sure why it was happening and it took me a few hours to fix. After going through every line of code I wrote
   to find where I made a mistake I found nothing. My only thought was that there had to be something wrong with the original HTML the
   website gave me that I just added my code to so I rewrote the entire program without all the extra layers to the html. This worked and
   from there the only issue I encountered was doing the optional add ons where I struggled to make a
   random array for the pattern then after a few minutes and a google search I was able to figure it out.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words)

   I have a lot of questions about web development. I am very passionate about coding but just feel like I’m not as
   knowledgable as I should be at this point in my education. However this assignment wasn’t too much new material so
   I didn’t have many questions besides the code used to get the pitch frequency for the buttons. There was a lot of new material
   in there that I haven’t seen before so my question is how do the sound initialization functions work? Another question
   I have after doing this assignment is, will we only be coding using
   HTML, CSS, and Javascript or will there be other languages in the program as well?

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words)

   If I were given a few more hours to work on this project, I would take that time to make the background look real unique with a
   custom look instead of just having a bland color. Along with changing the background I would change the
   layout of how the functions were written, for peak readability. This will allow another developer to come
   and easily maintain the code. Another thing I would add are different levels to the game and have it keep track of
   how many wins the player receives then increases the level after each win, with each level getting
   gradually harder. I’d have it get gradually harder by increasing the length of the pattern and adding more buttons to the sequence.

## Interview Recording URL Link

[My 5-minute Interview Recording](https://www.kapwing.com/videos/623bbaa17ed491007dac3c9a)

## License

    Copyright [Aaron Barker]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
