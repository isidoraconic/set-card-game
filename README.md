# SET Card Game

Find link to game [here](https://warm-crag-30374.herokuapp.com/). Please allow a few seconds for loading.

## Project Description
The aim of this project was to create a single player card game called SET, with three different playing modes based on difficulty (easy, meadium, and hard). An overview of SET can be seen [here](https://en.wikipedia.org/wiki/Set_(card_game), but specific rules for this project will be discussed below. Further, rules for how to play the game are included in the application itself (see link above).

### Difficulty Modes
**Easy Mode:** An easy game only uses 3 of the 4 features of each card (so you might have colour, shape, and number all be variable, but all other cards are solid). Because of this, there are only 27 cards total (combination of 3 sets of 3 different attributes).

**Medium Mode:** In a medium game, the game will use the normal 81 cards (combination of 4 sets of 3 different attributes) and will automatically draw more cards if there is not an available set for the user to pick. In other words, if there does not exist a set within the 12 cards drawn, then 3 more cards are automatically drawn by the game (and so on until a set is possible).

**Hard Mode:** A hard game uses the normal 81 cards and will **not** automatically draw cards for the player.
