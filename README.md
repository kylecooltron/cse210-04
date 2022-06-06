# Greed

Greed is a game in which the player seeks to gather as many falling gems as possible. The game continues as long as the player wants more!

## Getting Started

---

Make sure you have Python 3.8.0 or newer and Raylib Python CFFI 3.7 installed and running on your machine. You can install Raylib Python CFFI by opening a terminal and running the following command.

```
python3 -m pip install raylib
```

After you've installed the required libraries, open a terminal and browse to the project's root folder. Start the program by running the following command.```

python3 rfk

```
You can also run the program from an IDE like Visual Studio Code. Start your IDE and open the
project folder. Select the main module inside the hunter folder and click the "run" icon.

## Project Structure
---
The project files and folders are organized as follows:
```

root (project root folder)
+-- data (data files for game)
+-- game (specific game classes)
+-- **main**.py (entry point for program)
+-- README.md (general info)

```

## Required Technologies
---
* Python 3.8.0
* Raylib Python CFFI 3.7

## Authors
---
Kyle Coulon (kylejcoulon@gmail.com)
Rachel Knight (kni21003@byui.edu)

* # TODO: Add your name and email here ^
```

DESIGN DOCUMENT:
Most classes are unchanged versions from the RFK source

New Classes:
Meteoroid(Actor) - Meteoroids are either "rocks"s or "gem"s and keep track of their type
Meteormaker - Will randomly make a certain number of meteoroids at the top of the screen
Gravity - Returns a velocity vector that will be applied to all meteors

We are planning on changing the main class to not create artifacts on startup,
instead we will have something in the do_updates loop that will randomly have meteormaker create meteors
We will change starting position of robot
We will remove code for moving robot up and down

Rachel: will be handling the code for keeping track of score
Kyle: will Make the meteoroid and meteormaker classes
