# __Spotilistbot__

### This application builds a unique playlist using spotify.

###### _Developed by Dylan Manley with partners Nate Powers, Kyle Wymer, George Acosta & Eliza Sohn._

## Description

This application creates a custom generated playlist based on user inputted Genre & Mood.
The user logs into Spotify, selects a genre and a mood range.
The program creates, updates and posts the playlist using calls to the Spotify Api.

## Setup/Installation Requirements

* Clone this repository. Enter [__git clone https://github.com/dylan12manley/spotifytest.git__] in the terminal.
* Move into project folder by entering [__$ cd spotilistbot__]
* Initialize the file and install the Webpack by entering [__$ webpack install__] in the terminal.
* Run the Webpack in developer mode [__$ NPM RUN START__] in the terminal.
* The application will open in your browser. Or, enter localhost:8080 in your browsers addressbar.
* To utilize the app, press the __Start__ button to begin.
* Follow the given prompts to create a playlist.

## Specs

* The application makes an Api call to the Spotify Api
* The Spotify Api authorizes the user and the Application by an 0Auth process of creating and passing a unique token
* The Application takes a user selected genre and inserts it into the Api call
* The Application takes a user selected valence, converts it into decimal form and inserts it into the Api call
* The application sends the Api call with the user generated genre & valence to the Spotify Api

 Example Input: _User selects "Metal" & a valence of "Shitting Fucking Rainbows"_

 Example Output: _Your Very Own SpottyFried Playlist!_

      1 - Witch Doctor - Remastered 1999 by Alvin & The Chipmunks,
      on the album Greatest Hits: Still Squeaky After All These Years
      2 - His Banner Over Me Is Love by Cedarmont Kids,
      on the album Gospel Action Songs
      3 - The Middle by Jimmy Eat World,
      on the album Bleed American
      4 - The Anthem by Good Charlotte,
      on the album Greatest Hits
      5 - Teenagers by My Chemical Romance,
      on the album The Black Parade
      6 - First Date by blink-182,
      on the album Take Off Your Pants And Jacket
      7 - Does Your Chewing Gum Lose Its Flavor On The Bedpost Overnight? by The Re-Bops,
      on the album Funny 50's & Silly 60's
      8 - Birthday Bite by Recess Monkey,
      on the album Tabby Road
      9 - Beat It - Studio Version Featuring John Mayer by Fall Out Boy,
      on the album Live In Phoenix
      10 - Basket Case by Green Day,
      on the album Dookie
      11 - Blood - Hidden Track by My Chemical Romance,
      on the album The Black Parade
      12 - Newspaper Mama by Peter Combe,
      on the album Wash Your Face in Orange Juice_

## Known Bugs

_No known bugs_

## Support and contact details

_Any questions, comments or contributions please contact Dylan Manley (dylan.manley@gmail.com), Eliza Sohn(eliza.sohn@gmail.com), George Acosta (georgeacostar@gmail.com), Kyle Wymer (wymerkd@gmail.com), or (Nate Powers (Russellsproutz@Gmail.com)_

## Technologies Used

_HTML, CSS, Bootstrap, Git, jQuery and Javascript, Webpack, Jest, Nodejs, Eslinter, P5.js, Ajax, Photoshop, a fistful of GiFs and one vintage cast iron frying pan_

### License

__The MIT License__


Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.*

Copyright (c) 2019 **Dylan Manley, Nate Powers, Kyle Wymer, George Acosta & Eliza Sohn_**

dylan.manley@gmail.com wymerkd@gmail.com georgeacostar@gmail.com eliza.sohn@gmail.com
