# Pre-work - _Memory Game_

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program.

Submitted by: Maya Kaplan

Time spent: 4 hours spent in total

Link to project: https://glitch.com/edit/#!/coherent-strong-pegasus

## Required Functionality

The following **required** functionality is complete:

- [ ] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
- [ ] "Start" button toggles between "Start" and "Stop" when clicked.
- [ ] Game buttons each light up and play a sound when clicked.
- [ ] Computer plays back sequence of clues including sound and visual cue for each button
- [ ] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess.
- [ ] User wins the game after guessing a complete pattern
- [ ] User loses the game after an incorrect guess

The following **optional** features are implemented:

- [ ] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
- [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
- [ ] More than 4 functional game buttons
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
![](https://i.imgur.com/QLvU6Qv.gif)

## Reflection Questions

1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here.
   [n/a]

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words)
   [I initially found two problems with my game: I found was that even when I would input the correct pattern,
   it would say that I had lost the game, and also that the stop/start buttons would not become hidden when they were supposed to.
   To try to fix this, I tried to debug my code and see which variables
   were changing (or not changing) when different buttons were pressed.
   I immediately found using the debugger that I had typed out the name of a method incorrectly
   and not capitalized something I should have,
   and also that the "guessCounter" variable was not updating because I had accidently initialized it two different places.
   In addition, one of the bugs that took me a longer time to realize were present was regarding color changes,
   because although I was winning and loosing the game correctly, I neglected to notice that one of the buttons
   wasn't changing color. It was only after a long time of playing and debugging the game that I noticed that
   all the colors would change color except for the yellow button, which I was able to fix
   after inspecting my CSS code and finding a syntax error in the code for button4
   (I had written "buttons" instead of "button4").]

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words)
   [I would like to know if there are certain tricks to debugging with web development. At the moment I am
   reliant on printing to the console to see what I am doing wrong, so I would love to learn about other
   ways that may be more efficient to debug.
   I also would love to know more about how to use HTML and CSS to create visual cues for users that
   make it easier for users to interact with an interface (for instance, having the
   buttons in this project that got darker when you pressed down, in addition to stop and start buttons that disappeared,
   I thought were nice visual cues/tools that made it easier for users to interact with the game).
   I also would love to learn more about DOMs and how to use them, because it seems like they give the page a lot of functionality
   that I would love to be able to utilize more.]

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words)
   [If I had a few more hours to work on this project, I would have liked to add more features that would
   make the game more similar to a piano. For instance, I would have liked to make the bottons
   look more similar to piano keys by changing their shapes, color pattern, and placement to match that of piano keys.
   I would also have liked to change the tones that were played by each button so that
   the "piano keys"/buttons would have tones that correspond to their particular note on the piano.
   In addition, it would have been interesting if the tones played did not make random noises,
   but instead were matching the melody of a song the player would be familiar with.]

## License

    Copyright [Maya Kaplan]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
