---
layout: default
---

# Projects

## Fantasy Auto Racer
![](/assets/img/fantasy_auto_racer_title_image.PNG)

[Live Demo](https://www.fantasyautoracer.com/ "www.fantasyautoracer.com")
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 
[GitHub Link](https://github.com/jake-small/auto-racer-code-only "jake-small/auto-racer-code-only")

Fantasy Auto Racer is an auto battler, a niche genre with elements of traditional deck builders. Instead of battling, this game re-imagines the genre as a series of races. It's split into two phases. The first phase is spent buying items to improve your character, and the second phase is where you watch your character race. Repeat these phases and continually improve your character until the game is over. How many 1st place finishes can you rack up?

This project was started in order to learn the ins-and-outs of the Godot game engine. It was inspired by [Super Auto Pets](https://teamwoodgames.com/)- a well put together casual auto battler. If you find this game interesting, I highly recommend checking out SAP. After finishing this game, I feel comfortable with Godot and look forward to using it in future projects.

All item data is stored in json and support Lua functions. This lets me easily modify, add, delete, and version items. It also leaves the door open to custom items created by users, though that's not supported with the web release right now.

Project management was done in [Trello](https://trello.com). The best advice I could give to other game developers is to take project management seriously. Spending time curating a backlog and tracking tasks was the biggest reason why I was able to get this game to a finished state.

- Made with the game engine [Godot](https://godotengine.org/)
- Multiplayer uses Google's [Firebase](https://firebase.google.com/) via the [Godot Firebase SDK](https://github.com/GodotNuts/GodotFirebase)
- Scripting uses [Lua](https://www.lua.org/) and is interpreted with [MoonSharp](https://www.moonsharp.org/)
- Written primarily in C# with some GDScript
- Pixel art by [FinalBossBlues](http://www.timefantasy.net/)
- UI elements by [Kenney](https://www.kenney.nl/)

<br />

## Rock Paper Scissors AI
![](/assets/img/rpsNinja.png)

[Live Demo](https://www.rockpaperscissors.ninja "www.rockpaperscissors.ninja")
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 
[GitHub Link](https://github.com/jake-small/rps-ninja "jake-small/rps")

This rock paper scissors bot is one of my go to projects when learning a new language. In this case it's built with javascript ES6 using React with the help of [create-react-app](https://github.com/facebook/create-react-app). The bot creates a [Markov Chain](https://deepai.org/machine-learning-glossary-and-terms/markov-chain) as it plays in order to predict what it thinks the opponent will play next. For example, the most basic version of the bot makes its decision like this: given that the opponent played Rock last turn, and that they usually play Scissors after Rock, I will choose Rock next game. The bot currently used by this site is a slightly more advanced version of that. If you're interested in how it works, check out the bots folder in the repository [here](https://github.com/jake-small/rps-ninja/tree/master/src/services/bots). Going forward I want to provide the ability for users to select which bots to play against and to select which rule set to use ([Rock Paper Scissors Lizard Spock](http://www.samkass.com/theories/RPSSL.html) for instance). In addition, I'd like to include an explanation section with a visualization of the current state of the Markov Chain.

<br />

## Spin the Green Circle
![](/assets/img/SpinTheGreenCircle.png)

[Live Demo](https://www.spinthegreencircle.com "www.spinthegreencircle.com")
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 
[GitHub Link](https://github.com/jake-small/spin "jake-small/spin")

Spin the Green Circle is a short, 2D Unity game built for web. It is based on an old flash game I used to play and I wanted to make my own version for the modern web. I picked Unity and WebGL because I enjoy C# and was curious about Unity's 2D engine. The project is setup in a way in which levels can quickly and easily be added. If you would like to add your own levels, pull the code from github, open in Unity, and duplicate the Basic Scene found in the templates directory. From there you can copy and paste the various pieces where you want them, and don't worry, all of the logic is already built in. In the future I plan to add more levels grouped by difficulty and improve the color scheme.

<br />

## 3d Printed Case for an Arduino Project
![](/assets/img/enhancedTrainingModeCase.jpg)

[Thingiverse Link](https://www.thingiverse.com/thing:3999596 "Enhanced Training Mode Case")

This is a case made to house an Arduino running [Linyoa's Enhanced Training Mode](https://github.com/Linyoa/Enhanced-Training-Mode). This mod improves the training dummy in Super Smash Bros Ultimate. Think of it like a ball machine in tennis. At the time, there was only one model for a case like this but it required you to feed the wire through before soldering. I wanted a case that would let me remove the Arduino easily so I created this version.

<br />

## Mist Android App
<img src="/assets/img/mist_1200x1200.png" width="300" />

<a href="/assets/pdf/mist_brochure.pdf">App Fair Brochure PDF</a>

Mist is an Android app made for a project in college back in 2015. It was designed to make finding movies easy. The name comes from combining the words Movie and List as the purporse of the app is to create lists of movies. Once you have some lists you can use the selector to pick a movie using some filter options. The main strength of the app is the social aspect. Friends generally share the same movie interests so, leveraging that, Mist lets users select movies from lists their friends made. For more info check out the trifold brochure that I made for my school's mobile app fair. I ended up winning ["Best in Show](/assets/img/BestInShow.jpg "awkward pic")! There are many improvements I would make if I revisited this project, starting with the UI. I need to give credit to [TheMovieDB](https://www.themoviedb.org/documentation/api?language=en-US) which supplied all of the movie info and pictures and I want to thank my brother Jimmy for creating the awesome logo!


<!-- Potential Future Additions: Arduino Chessboard, Chaos Game, Debris Game -->