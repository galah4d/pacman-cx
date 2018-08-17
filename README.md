# PacMan CX - Version 1.0

![pacman cx](https://github.com/galah4d/pacman-cx/blob/master/screenshots/screenshot-main.png)

PacMan CX is a simple 2D game powered by the CX programming language.
This game is being developed with the following objectives:

  - Demostrate the capabilities of CX
  - Obtain feedback on the language
  - Increase awareness for the Skycoin Project (developers of CX)

# What is CX?
CX is a general purpose, interpreted and compiled programming language, with a very strict type system and a syntax similar to Golang's. CX provides a new programming paradigm based on the concept of affordances, where the user can ask the programming language at runtime what can be done with a CX object (functions, expressions, packages, etc.), and interactively or automatically choose one of the affordances to be applied.

You can find more info on:
  - The github page on CX - https://github.com/skycoin/cx
  - The official website of Skycoin - https://www.skycoin.net/

# Installation
Breakout CX  requires the latest version of [CX](https://github.com/skycoin/cx) to run.

Install the dependencies and devDependencies and start the server.
After installing [CX](https://github.com/skycoin/cx) and all its dependencies clone this repository by running:

```sh
$ git clone https://github.com/galah4d/pacman-cx.git
```

Wait for the cloning process to finish and navigate to the cloned directory...

```sh
$ cd pacman-cx/
```

The game should be ready to run.

# Running the game
In order to run the game type the following command:

```sh
$ cx graphical2d.cx pac-man.cx
```

Use the arrows to move the player.

# To Do...
The code is currently very disorganized due to the fact that this was my first experience with CX and I had to play around some bugs. I will make sure to clean things up as soon as possible.
 - Currently under development:
   - Add teleport blocks (causes a game freezing bug when a ghost steps in there).
   - Implement differnt ghost movement patterns.
   - Add the support for multiple levels.
   - Polish movement mechanics.

# Disclamer
I am not part of the team responsible for the development of the CX programming language neither do I claim some sort of affiliation with the [Skycoin Project](https://www.skycoin.net/).
