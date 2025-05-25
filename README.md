# Reach for the Stars: A Platformer Adventure

A classic 2D platformer built with HTML, CSS, and JavaScript, where your goal is to collect all the stars and reach the exit to advance through increasingly challenging levels. Each level brings new obstacles, faster gameplay, and unique, dynamic background elements to enhance the immersive experience.

<div align="center">
  <a href="https://htmlpreview.github.io/?https://raw.githubusercontent.com/tin2tin/reach_for_the_stars/master/index.html">PLAY</a><br><br>
  <img src="https://github.com/tin2tin/reach_for_the_stars/blob/main/stars.gif?raw=true" width="25%" />
</div>



## Table of Contents

*   [Features](#features)
*   [How to Play](#how-to-play)
*   [Dynamic Backgrounds](#dynamic-backgrounds)
*   [Setup & Running the Game](#setup--running-the-game)
*   [Development & Technologies](#development--technologies)
*   [Contributing](#contributing)
*   [License](#license)

## Features

*   **Classic Platforming:** Jump, run, and navigate treacherous platforms.
*   **Dynamic Level Generation:** Each level presents a new, procedurally generated layout of platforms, enemies, and stars.
*   **Challenging Obstacles:**
    *   **Moving Platforms:** Platforms that traverse horizontally.
    *   **Disappearing Platforms:** Platforms that vanish upon touch and reappear after a short duration.
    *   **Bouncy Platforms:** Give an extra high jump!
    *   **Conveyor Platforms:** Push the player in a specific direction.
    *   **Enemies:** Avoid red triangular enemies that patrol platforms.
    *   **Deadly Pit:** Don't fall off the screen!
*   **Collectibles:** Gather shiny stars to unlock the level's exit.
*   **Power-Ups:**
    *   **Invincibility:** Become temporarily immune to enemies and deadly platforms.
    *   **Speed Boost:** Move and jump faster for a limited time.
*   **Lives System:** You have a limited number of lives before Game Over.
*   **Score Tracking:** Accumulate points by collecting stars and completing levels.
*   **High Score:** Your best score is saved locally!
*   **Responsive Controls:** Play seamlessly on both desktop (keyboard) and mobile (touch screen).
*   **Immersive Sound & Music:** Simple, retro-style sound effects and background music (music is from an external source).
*   **Thematic Backgrounds:** Experience different atmospheric effects unique to each level's visual theme (see [Dynamic Backgrounds](#dynamic-backgrounds) below).

## How to Play

### Objective

Collect all the yellow stars in a level. Once all stars are collected, a green "EXIT" platform will appear. Reach this platform to complete the level and advance to the next!

### Controls

#### Desktop (Keyboard)

*   **Move Left:** `Left Arrow` or `A`
*   **Move Right:** `Right Arrow` or `D`
*   **Jump:** `Spacebar`
*   **Pause/Resume:** `P` or `Escape`
*   **Restart Game:** Click the "Restart Game" button on the top right.
*   **Mute Music:** Click the "Mute Music" button on the top right.

#### Mobile (Touch)

*   **Move Left:** Tap the `LEFT` button on the bottom left.
*   **Move Right:** Tap the `RIGHT` button on the bottom left.
*   **Jump:** Tap the `JUMP` button on the bottom right.
*   **Mute/Restart:** The "Mute Music" and "Restart Game" buttons are available on the top right.

### Gameplay Tips

*   Pay attention to platform types; they behave differently!
*   Enemies patrol platforms. You can avoid them or use invincibility.
*   Falling off the screen or touching a deadly platform costs a life.
*   Power-ups are temporary, so use them wisely!

## Dynamic Backgrounds

The game's background theme and accompanying moving elements change with each level, creating a unique atmosphere:

*   **Level 1, 6, 11... (Night/Space Theme)**:
    *   **Colors:** Deep blues, purples, and grays.
    *   **Moving Elements:** ✨ **Fireflies** - Small, glowing particles that drift and subtly flicker.
*   **Level 2, 7, 12... (Autumn/Sunset Theme)**:
    *   **Colors:** Warm yellows, oranges, and reds.
    *   **Moving Elements:** 🍂 **Leaves** - Drifting leaves in autumn colors, gently falling and rotating.
*   **Level 3, 8, 13... (Sky/Ocean Theme)**:
    *   **Colors:** Bright blues, teals, and light purples.
    *   **Moving Elements:** 🌧️ **Rain** - Light blue raindrops falling vertically with a slight drift.
*   **Level 4, 9, 14... (Spring/Sunrise Theme)**:
    *   **Colors:** Soft oranges, pinks, and magentas.
    *   **Moving Elements:** 🌸 **Flower Petals** - Various colored petals gracefully descending.
*   **Level 5, 10, 15... (Winter/Deep Night Theme)**:
    *   **Colors:** Dark blues, deep grays, and subtle whites.
    *   **Moving Elements:** ❄️ **Snowflakes** - White snowflakes gently falling and drifting.

## Setup & Running the Game

This game is a single HTML file and requires no complex setup.

1.  **Save the file:** Copy the entire code block and save it as `index.html` (or any `.html` filename) on your computer.
2.  **Open in Browser:** Double-click the saved `index.html` file, and it will open in your default web browser.

**Note:** The background music is loaded from an external GitHub URL. Ensure you have an internet connection for the music to play.

## Development & Technologies

*   **HTML:** Structures the game canvas and control buttons.
*   **CSS:** Styles the page, canvas, and implements responsive design for mobile controls.
*   **JavaScript:** Powers all game logic, physics, drawing on the canvas, level generation, audio, and managing game states.

## Contributing

Feel free to fork this repository, suggest improvements, or submit pull requests.

## License

This project is open-source and available under the [MIT License](LICENSE).

---
