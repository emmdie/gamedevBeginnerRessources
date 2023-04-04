# Making Video games
## Introduction
### What this is and is not
* Not a tutorial
* A collection of tools and strategies to get started
## Getting started
### Philosophy
* Being bad means improving fast
   * Don't make long games, the gain in knowledge will make it worth it to start over in a week
   * cycle of never finishing
* Make a game in an hour, a day, a week, a month [0h gamejam](https://itch.io/jam/0h-game-jam-2022)
* Constraining is hard (scopecreep), just one more feature
* Gamejams (itch.io) for connecting with people and pressure to actually finish
* Don't spend time making decisions about your tools as a beginner, skills will translate and you don't really know what you will eventually need from your tools
* **You learn making games by making games and nothing else**

## Art
### Tips
* There are a lot of difficult concepts with art
    * light
    * material
    * empty space/ detailing
    * => workarounds might be necessary
* Consistency is key 
    *  Common mistake: doing pixel art and then having different sized pixels on the screen
    * "Ugly" but incredibly consistent in style: [Cruelty squad](https://www.youtube.com/watch?v=CHm2d3wf8EU)
* Make up imits to limit and shield you from more difficult concepts and possibilities to mess up
    * Color Palettes: pallette pickers, e.g. [color-hex](https://www.color-hex.com/color-palettes/)
       * save you from messing up colors. DONT MAKE EXCEPTIONS FOR "JUST THAT ONE MORE COLOR FOR THAT ONE THING"
    * High contrast/ outlines for consistent style: [example, celeste](https://games-b26f.kxcdn.com/wp-content/uploads/2019/06/celeste-770x470.png)
    * Shapes: [Patapon](https://www.youtube.com/watch?v=D3Hz4hIjeDs)
    * Great simplification and abstraction of a similar game and theme: 
      * [Subnautica](https://store.steampowered.com/app/264710/Subnautica/) vs. [In Other Waters](https://store.steampowered.com/app/890720/In_Other_Waters/)
    * Go ultra minimal/Embrace the medium: [Anuto TD](https://www.youtube.com/watch?v=gJ10UZJy-IA), [FAITH](https://www.youtube.com/watch?v=io2cGEiUGWg)
* Juice
    * Short game that "feels" great >>> super big game that feels meh
    * [12 Principles of animation](https://www.youtube.com/watch?v=uDqjIdI4bF4)
    * Juice [more](https://www.youtube.com/watch?v=xSYVQc7cH-4)
* Check out asset packs for premade art
    * [KennyNL](https://www.kenney.nl/assets)
* Shaders

### Tools
No exhaustive list
* PixelArt
    * Aseprite (FOSS)
    * MS Paint
* Drawing
    * Krita
    * Photoshop
* Voxel
* Claymation
* Watercolor, Chalk, text base....
    * Clean up in Gimp/Photoshop and import
* AI tools

## Programming
* Avoid visual scripting, steal literally all your code if necessary (as a CS student)
* There is a tutorial for literally everything (depending on your language of choice)

### Engines
Please don't spend more than 10 minutes choosing one. You don't know what features you will need yet, most skills will transfer anyway.
* [Pico 8](https://www.lexaloffle.com/pico-8.php)
    * 15$
    * Fantasy console
    * Limited palette
    * Includes Sprite editor, IDE, music editor
    * Engine of the [original Celeste](https://www.lexaloffle.com/bbs/?tid=2145)
* [Godot](https://godotengine.org/)
    * Free and open source
    * Powerful and feature rich
    * Lack of very advanced tutorials
    * Great native 2D
    * Console ports expensive
       * That's the kind of thing you shouldn't think about if you are in a position to be reading this.
* [Unity](https://unity.com/)
    * Commercial/subscription based with a free tier and closed Source
    * Giant amount of tutorials /shaders /assets...
    * 2D can be awkward
* [Unreal](https://www.unrealengine.com)
    * Most powerful 3D engine
    * Not too beginner friendly
    * Go to for realistic graphics and rendering
* [Construct](https://www.construct.net/en)
    * Closed Source, subscription with a free tier
    * Web based
    * Features for quick production [send people a link for quick testin, premade snippets]
* [Game Maker](https://gamemaker.io/en)
    * Closed Source, commercial with a free tier
    * very acessible
* [Playdate](https://play.date/)
    * Free emulator/180$ console
    * Consoles and online emulator for developing
    * **has a crank**
* You do not need an engine
    * [Making games with Python (free ebook)](https://inventwithpython.com/#pygame)
    * [Game in HTML and Javascrip](https://www.w3schools.com/graphics/game_intro.asp)

# Useful/Interesting Links 
## Art
### Talks/Videos
* [How to Make Your Game Look Good if You're Not a Good Artist](https://www.youtube.com/watch?v=xMgNBP8yJeU)
* [The Art of FAITH: Horror at 192x160 Pixels](https://www.youtube.com/watch?v=RLh7xO-LRy4)
* Extensive Pixel art Tutorials: AdamCYounis
    * [Pixel Art Class - What's The Right Canvas Size?](https://www.youtube.com/watch?v=upEGBGCiWEw)
    * [An Aseprite Crashcourse in 20 Minutes](https://www.youtube.com/watch?v=59Y6OTzNrhk)
    * [Pixel Art Class - Create More Engaging Character Sprites](https://www.youtube.com/watch?v=mdoycEGHye0)
* [Long, Specific Krita Tutorials: David Revoy](https://www.youtube.com/c/DavidRevoy)
* [How to paint in Krita](https://www.youtube.com/watch?v=Z06RRp81iDM)

### Ressources 
* [KennyNl Assets](https://www.kenney.nl/)
* [Color-hex palettes](https://www.color-hex.com/color-palettes/)
* When looking for any assets, search in the gamedev subreddit: [/r/gamedev](http://reddit.com/r/gamedev)
 
### Tutorials 
Be aware of tutorial hell. Tutorials are great for getting an overview of your tools and workflows. They will not enable you to reproduce things and make you dependent on them in order to reliably produce results. Follow a two hour one for a whole game, then do your own game with INDIVIDUAL tutorials for different things [player controller, bullets, score...]. That way, you will understand how systems interact and will have to change them to match, rather than things working together without understanding why things are set up a certain way. 
* Godot 
    * [Short, basic tutorial: Your first 2D game](https://docs.godotengine.org/en/stable/getting_started/first_2d_game/index.html)
    * [Pixel Platformer Tutorial / Code Along (Character Basics) - Godot Engine](https://www.youtube.com/watch?v=f3WGFwCduY0)
## Gamedesign
### Youtube Channels
* Vimlark
    * Professional Gamejammer
    * [Making a Dice Base Rogue-like in 48 Hours - GMTK Game Jam 2022 Devlog](https://www.youtube.com/watch?v=BCVEa-0297Q)
    * [I Made Cursed Flappy Bird in 3 Hours - TriJam Devlog](https://www.youtube.com/watch?v=ZCc9UqZ5KsY)

* [Adam Millard - Architect of games](https://www.youtube.com/user/Thefearalcarrot)
    * [What Does "Immersion" Actually Mean?](https://www.youtube.com/watch?v=5DANwfC0GWI)
    * [Leveling Up Progression Systems](https://www.youtube.com/watch?v=gDQX3jk5xxc)
    * [Why Tunic Hides Its Tutorial](https://www.youtube.com/watch?v=Jzqv0bKLz2o)
* AI and games
    * [The AI of Half-Life: Finite State Machines | AI 101](https://www.youtube.com/watch?v=JyF0oyarz4U)
    * [The AI of Alien: Isolation | AI and Games] (https://www.youtube.com/watch?v=Nt1XmiDwxhY)
