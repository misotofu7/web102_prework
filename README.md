# WEB102 Prework - *Sea Monster Crowdfunding*

Submitted by: **Kaylie Chang**

**Sea Monster Crowdfunding** is a website for the company Sea Monster Crowdfunding that displays information about the games they have funded.

Time spent: **4** hours spent in total

## Required Features

The following **required** functionality is completed:

* [x] The introduction section explains the background of the company and how many games remain unfunded.
* [x] The Stats section includes information about the total contributions and dollars raised as well as the top two most funded games.
* [x] The Our Games section initially displays all games funded by Sea Monster Crowdfunding
* [x] The Our Games section has three buttons that allow the user to display only unfunded games, only funded games, or all games.

The following **optional** features are implemented:

* [x] Hovering over 🥇 Top Funded Game and 🥈 Runner Up will reveal the names of the top 2 games
* [x] Hovering over any game card below will reveal its ranking based on the amount of pledges (1 = highest rank)
* [x] Slight change in CSS formatting (h2 headers are made more readable by creating an off-white rounded background)

## Video Walkthrough

Here's a walkthrough of implemented features:

<img src='https://www.youtube.com/watch?v=yL3ot2U6lGM' title='CodePath Pre-work Walkthrough - WEB102 (Sea Monster Crowdfunding)' width='' alt='Video Walkthrough of Sea Monster Crowdfunding' />

<!-- Replace this with whatever GIF tool you used! -->
Video created with QuickTime Player (and iMovie for editing)
<!-- Recommended tools:
[Kap](https://getkap.co/) for macOS
[ScreenToGif](https://www.screentogif.com/) for Windows
[peek](https://github.com/phw/peek) for Linux. -->

## Notes

One challenge I faced was understanding what the instructions wanted me to do with the ternary operator. It took me a while to understand that I had to create text that was gramatically correct based on the number of funded/unfunded games.

Another challenge I faced was understanding why we had to call `deleteChildElements(gamesContainer)` in Challenge 5's section. I later learned that it was to prevent duplicate games from showing up when clicking through the buttons.

## License

    Copyright [yyyy] [name of copyright owner]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.