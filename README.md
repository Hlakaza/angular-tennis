# Angular Tennis

This is Angular Tennis, my first app build with AngularJS in order to start trying and learning it. I got the inspiration for it from the already known _Tennis Kata_.

In this app, we basically enter the names of the two players we have, select how many sets we want to play and click on Start Game, which will show us the interesting part of the app. We will see two green buttons (the ones with a racket in it) and every time we click on one of them it will score a point for the player on the side we clicked the button.

![Angular Tennis Screenshot](https://sergibyte.github.io/angular-tennis/image/screenshot.png)

The tricky bit here is counting the point because, as you know, tennis is a tricky sport when counting points. This app supports the following scenarios:

* Points within a game are 0-15-30-40
* If a player has 40 points and scores, he/she wins the game unless the opponent has 40 points too.
* If both players get at 40 points we have a _Deuce_ and the app will show a _Deuce_ Message.
* When on Deuce, scoring a point will mark advantage **A** to the player who scored.
* If a player has advantage and scores he/she wins the game, but id the opponent scores they return to a _Deuce_.
* If a player wins 6 or more games with an advantage of at least two games, he/she wins the set and we start the next set.
* If both players arrive to 6 games won, we enter a _Tie Break_ situation, and a message for that will be shown.
* The _Tie Break_ is won by the first player to score 7 points, with a least two of difference with its opponent.
* The player who wins 2 sets out of 3, or 3 sets out of 5 wins the game.

#License

### The MIT License (MIT)

Copyright © 2016 Sergi Pedraza

Permission is hereby granted, free of charge, to any person
obtaining a copy of this software and associated documentation
files (the “Software”), to deal in the Software without
restriction, including without limitation the rights to use,
copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the
Software is furnished to do so, subject to the following
conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES
OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT
HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY,
WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR
OTHER DEALINGS IN THE SOFTWARE.
