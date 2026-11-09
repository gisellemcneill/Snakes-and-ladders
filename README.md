# Snakes & Ladders 🚢

A fishing-themed take on the classic board game, built in Unity for **Games for Love's October game**.

Forked from [GamesForLoveBigTeam2/Snakes-and-ladders](https://github.com/GamesForLoveBigTeam2/Snakes-and-ladders).

## About the Game

Four players race to reach the final square by rolling a die. Land at the bottom of a fishing lure to climb ahead, but land on an anchor, and you'll slide back down. First to the top wins!

- 10×10 board with 100 squares
- Roll a 6 for an extra turn
- Must land exactly on the final square to win
- Made for kids and casual players

## The Team

Built in **one month** by a large team made up of **four sub-teams** working together on a single mini game.

## My Contribution — Audio

I built the game's **AudioManager** and connected sound effects to gameplay:

- **AudioManager**: a persistent singleton that plays sounds by type, with per-sound volume and a saved master volume
- **Sound variations**: each sound can hold multiple clips and picks one at random, so repeated sounds like footsteps don't feel repetitive
- **Designer-friendly setup**: sounds are assigned in the Unity Inspector, with Console warnings for missing clips
- **Gameplay sounds**: dice rolls (with unique sounds for 1 and 6), piece movement, ladder climbs, snake slides with a ship horn, and victory

## Built With

- Unity 6 (6000.5.3f1)
- C#
