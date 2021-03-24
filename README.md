# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Shaoqi Wang**

Time spent: **5** hours spent in total

Link to project: https://glitch.com/edit/#!/comet-sordid-cotija

## Required Functionality

The following **required** functionality is complete:

* [x] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [x] "Start" button toggles between "Start" and "Stop" when clicked. 
* [x] Game buttons each light up and play a sound when clicked. 
* [x] Computer plays back sequence of clues including sound and visual cue for each button
* [x] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [x] User wins the game after guessing a complete pattern
* [x] User loses the game after an incorrect guess (changed to loss after 3 incorrect guesses)

The following **optional** features are implemented:

* [x] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [x] Buttons use a pitch (frequency) other than the ones in the tutorial
* [x] More than 4 functional game buttons
* [x] Playback speeds up on each turn
* [x] Computer picks a different pattern each time the game is played
* [x] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:
* [x] User can see how many lives they have left.
* [x] Made 7 buttons correspond to 7 solfege's name and frequncy.


## Video Walkthrough

Here's a walkthrough of implemented user stories:

This gif shows game button's light up and the randomness of clue's pattern: https://cdn.glitch.com/335acbec-a8c9-449a-a3fa-0687c822d76d%2Fintro1.gif?v=1616492449964

This gif shows the display of palyer's live left, update of live count, lost game after made 3 mistakes in total, and reset live to 3 when click on start button: https://cdn.glitch.com/335acbec-a8c9-449a-a3fa-0687c822d76d%2Fintro2.gif?v=1616492452734

Below are 3 gifs for going through a winning game and the rest of features, they were recording as a one and half minutues video:

<a href="https://cdn.glitch.com/335acbec-a8c9-449a-a3fa-0687c822d76d%2Fwon1.gif?v=1616492458982" target="_blank">Process1 link</a>
<a href="https://cdn.glitch.com/335acbec-a8c9-449a-a3fa-0687c822d76d%2Fwon2.gif?v=1616492462577" target="_blank">Process2 link</a>
<a href="https://cdn.glitch.com/335acbec-a8c9-449a-a3fa-0687c822d76d%2Fwon3.gif?v=1616492466406" target="_blank">Process3 link</a>

As you can see, the play back speeds up on each turn, and I made a mistake but eventaully won.


## Reflection Questions
**1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. **

I used W3School to help me with some optional features.

**2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) **

The video recording was kind of difficult. I use windows system so I do not have quick time. 
I used windows's game center. I took some time to read through instructions about windows screen recording.
I also had to record several times because there are always somethings going off in every recording. 
I solved it by split the demonstration into pieces to record, so I only need to record a small part if something goes wrong on that part. 

I followed website instruction, so I copy paste README.md to glitch repository, but the instructor on video opened hackmd.
The instructor was able to just drag the gif to upload it to his README.md on hackmd, but I need to search up how to upload gif in glitch and follow instructions.
I did not know that ezgif would have maximum time limit for converting gif so I had to cut my video. As you can see, I have 2 gif link for some features written above, and I cut the process of winning into 3 gif hyperlinks.
I used github before, so I did not meet any challenge for this step. 
All in all, instructions provided were very helpful and detailed, thank you!



**3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) **

I used document.getElementById("liveCount").innerHTML to do the user live count update, but there is some delay. 
For example, when the user lost all 3 lives, the alert would pop before updating user they have 0 live now. 
I know how to fix similar issue in react, but I don't know how to fix this in glitch. 

I also want to learn more details about how the game button sounds came from. 
For example, what context.createOscillator() and context.createGain() each does, and how we used them to make sounds. 
setTargetAtTime and setValueAtTime seem have something to do with time, what are their similarities and differences from setTimeout?

**4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) **

I would probability spend more time on researching short music piece and use them as my pattern since the random generated pattern doesn't sounds that good.
I don't play any instrument so it was hard for me to come up any music piece with less than 8 cues. 

I also want to do the feature that user has a limited amount of time to enter their guess on each turn if I have more time. 
I tried several times by using setInterval and clearInterval, but the come come was not ideal, so I deleted this feature. 
I also tried to do game button appearance change goes beyond color (e.g. add an image) feature, it worked out but doesn't look pretty so I deleted it. 
If I had more time, I would probability search for a set of simple music node for different cue and use them as my game button appearance change.



## License

    Copyright [Shaoqi Wang]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
