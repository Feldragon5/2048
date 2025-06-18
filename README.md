# 2048 Game

This project is a modern and elegantly themed implementation of the classic 2048 puzzle game.  
You can view a live demo of the project here:
`https://Feldragon5.github.io/2048/`

## How to Play

The goal is to combine numbered tiles to create the 2048 tile.

-   **Desktop**: Use the **arrow keys** (`↑`, `↓`, `←`, `→`) to move all tiles on the board.
-   **Mobile**: **Swipe** up, down, left, or right on the game board to move the tiles.
-   When two tiles with the same number touch, they **merge** into one tile with the combined value.
-   After every move, a new tile (either a 2 or a 4) will appear in a random empty spot.
-   The game is over when the board is full and no more moves can be made. Try to get the highest score!

## Expansion Ideas

-   **High Score Tracking**: Save the user's high score in their browser using `localStorage` so it persists between sessions.
-   **Sound Effects**: Add sound effects for tile slides, successful merges, and the "Game Over" screen.
-   **Undo Button**: Implement a feature to undo the last move, giving the player a chance to correct a mistake.
-   **Settings Menu**: Create a settings panel to allow users to toggle sounds, change themes, or perhaps even adjust the grid size (e.g., 3x3 or 5x5).
-   **Customizable Themes**: Add a light-mode theme and a toggle to switch between the current theme and the new one.
-   **Auto-Play**: Make the game play itself using an algorithm or AI
