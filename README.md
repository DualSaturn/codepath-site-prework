# Pre-work - _Memory Game_

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program.

Submitted by: **Varun Singh**

Time spent: **2** hours spent in total

Link to project: (https://glitch.com/~curse-cerulean-anteater)

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
- [ ] Playback speeds up on each turn
- [ ] Computer picks a different pattern each time the game is played
- [ ] Player only loses after 3 mistakes (instead of on the first mistake)
- [ ] Game button appearance change goes beyond color (e.g. add an image)
- [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
- [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough

Here's a walkthrough of implemented user stories:
![](https://cdn.glitch.com/950a7040-ad67-4b0b-8ace-26b4b9d83e20%2Fpre-work-demo.gif)

## Reflection Questions

1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here.
   Consulted the Mozilla MDN tutorials for greater knowledge about HTML and CSS.

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words)
   The most challenging part of creating the submission was debugging the submission. At one point while following the guide,
   I'd forgotten to link the function for playing the clue sequence to the start button. I didn't realize this, and went onwards following
   the guide for the rest of the submission. I ended up going back, step-by-step, and making sure that every function worked as needed, and
   that I'd included every function described in the guide. Only after using console.log and reading through my code meticulously did I realize
   what had happened.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words)
   After the submission, I am extremely curious on how larger projects are developed, tested, and debugged. The complexity
   of a codebase seems to grow so quickly, and it seems like it would be a monumental task to maintain code for huge projects
   like Glitch, for example.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words)
   I would add more features, perhaps a settings page to allow the user to customize different aspects of the game. I would also implement a random pattern for each game.
   A score display is another feature that would be a nice addition, and we could save a high score in localStorage.

## License

    Copyright Varun Singh

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
