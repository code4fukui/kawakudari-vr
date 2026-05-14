# kawakudari-vr

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

A simple VR game where the player avoids obstacles in a downward-scrolling environment. The name "kawakudari" (川下り) is Japanese for "river rafting."

## Gameplay

Play the live demo: **[https://fukuno.jig.jp/app/kawakudari-vr/](https://fukuno.jig.jp/app/kawakudari-vr/)**

In this first-person game, you fly forward at a constant speed through a dark void filled with white, block-like obstacles. The world wraps around horizontally, allowing you to move seamlessly from one side to the other to find a safe path.

## How to Play

**Objective:** Reach the end of the course (a distance of 520 units) without hitting any obstacles.

**Controls:**
- **Desktop:** Use the left and right arrow keys to move sideways.
- **VR:** Use head movements to steer.

The game ends if you collide with an obstacle, turning the screen red. If you reach the end, the screen turns white and a "CLEAR!" message appears.

## Features
- Built with [A-Frame](https://aframe.io/) for a lightweight, browser-based VR experience.
- A challenging course of 100 randomly positioned obstacles.
- Constant forward motion that creates a sense of speed.
- Infinite horizontal "wraparound" space for navigation.
- Single HTML file with no build process required.

## Running Locally
1. Clone or download this repository.
2. Open the `index.html` file directly in a modern web browser.

## License
MIT License — see [LICENSE](LICENSE).