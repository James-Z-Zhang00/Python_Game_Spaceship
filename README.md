# Python_Game_Spaceship

A simple desktop game built by Pygame and sprite

## General Information

The main screen, click play button to start

Numbers on the top right are current scores and level, the number at the top middle is score too

Spaceship icons on the top left are extra lives, your spaceship will be destoried once it touched by aliens

Use arrow button left and right to control the spaceshipk, space bar for firing

<img width="1792" alt="Screen Shot 2024-05-26 at 3 18 06 PM" src="https://github.com/James-Z-Zhang00/Python_Game_Spaceship/assets/144994336/4df765ee-9cde-4a97-8316-d901af4163dd">

## Object Oriented Design Concepts

The game was made by objects/classes:
- alien.py                to build single alien objects
- alien_invasion.py       the starting point of the game, including UI, game setting, states updating and event listeners (keyboard control)
- bullet.py               the bullet every time the spaceship will fire, with trajectory computation, I added the sound effect while shooting too
- button.py               for UI
- game_stats.py           to initialize values at the beginning of the game, e.g. spaceship position and extra lives
- scoreboard.py           to save/hold live game information e.g. current score & level with proper calculation and the highest record
- settings.py             to provide fundamental information about the game, e.g. window size, bullet travel speed, spaceship sensitivity
- ship.py                 to create the spaceship object, including parse the provided image and updating its positon on UI

<img width="1323" alt="Screen Shot 2024-05-26 at 4 22 05 PM" src="https://github.com/James-Z-Zhang00/Python_Game_Spaceship/assets/144994336/45d2cff4-8dca-4f19-a7f8-4e681e7a4032">




