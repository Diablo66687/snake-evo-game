# Snake Evolution

A modern console-based Snake game for .NET 8, featuring:

- Single player, Duel (2 players), and Duel AI modes
- Multiple languages (cs, en, de, es, pl, uk)
- Spectre.Console UI enhancements (menus, score charts, loading spinners)
- Color schemes: Default, Retro, HighContrast
- Special food types: Double Points, Slow, Shorten, Invisible, Reverse, Long
- Moving obstacles
- Highscore tracking and game logging

## Requirements
- .NET 8 SDK
- Windows console (UTF-8, colors)
- Spectre.Console
- SharpDX.XInput (optional, for gamepad support)

## How to Play
- Player 1: Arrow keys or WASD
- Player 2: IJKL
- P: Pause
- R: Restart
- Esc/Enter: Exit

Eat as much food as possible, avoid obstacles and yourself. Special food types:
- $ = +2 points
- S = slow
- - = shorten snake

## Features
- Adjustable speed and difficulty
- Colorful snake head (directional: > < ^ v) and body (=)
- Multiple color schemes
- Live score and highscore charts
- Game log (optional)
- Language selection

## Running
1. Build the project with `dotnet build`.
2. Run with `dotnet run --project ConsoleApp2`.
3. Use the menu to start the game, change settings, or view highscores.

## Credits
DevBrain ©

---

For more details, see the source code and in-game help (option 7 in menu).
