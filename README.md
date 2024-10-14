# Brick Breaker Space

A space-themed 2D arcade game developed in Unity, inspired by the classic *Brick Breaker Star: Space King*. Control a paddle, bounce the ball, and break all the bricks to progress through procedurally generated levels. This version brings custom assets, power-ups, and smooth gameplay to both desktop and mobile platforms.

## Demo

Play the demo on Vercel using the following link: [Brick Breaker Space - Demo](https://your-vercel-demo-link.vercel.app)

---

## How to Play

- **Objective**: Destroy all the bricks using the ball while preventing the ball from falling out of bounds by controlling the paddle.
- **Controls**: Use the mouse (or touch on mobile) to move the paddle horizontally and bounce the ball back into play.
- **Power-Ups**: Collect special items like multi-ball and fireball to enhance your gameplay.
- **Levels**: Each level is procedurally generated, becoming progressively more challenging.

---

## Features

1. **Custom Assets**:
   - Hand-drawn visuals created using Aseprite.
   - Unique sprite designs for bricks, paddles, and power-ups.

2. **Tilemap-Based Level Editor**:
   - Fast level creation using a custom tilemap editor that converts tiles into independent objects for optimal gameplay.

3. **Power-Ups**:
   - Multi-ball: Spawns additional balls to break bricks faster.
   - Fireball: Turns the ball into a fireball that destroys everything in its path.

4. **Advanced Physics**:
   - Smooth ball and paddle mechanics with responsive controls.
   - Fixed ball behavior upon paddle contact, ensuring a seamless experience.

5. **Procedurally Generated Levels**:
   - Each level is randomly generated, offering endless replayability with increasing difficulty.

6. **Camera Resizer**:
   - The game automatically adjusts the camera to fit all screen resolutions for consistent play on mobile and desktop.

---

## Technologies and Concepts Used

### 1. **Unity Engine (2021.3 or higher)**
   - 2D game development using Unity's physics engine and tilemap system.
   
### 2. **C# Programming**
   - Scripts handle player input, ball movement, and power-up management.

### 3. **Aseprite for Custom Art**
   - All visual assets were hand-drawn using Aseprite, including animations for power-ups and brick destruction.

### 4. **Procedural Generation**
   - The level generation algorithm ensures no two playthroughs are the same.

### 5. **WebGL Deployment on Vercel**
   - The game is deployed as a WebGL build for online play.

---

## Future Improvements

- **Additional Power-Ups**: Introducing more power-ups for added gameplay variety.
- **Win/Loss Conditions**: Enhancing the game's win condition logic and level progression.
- **Mobile-Specific Optimizations**: Further optimizing for smoother gameplay on mobile devices.
- **Score and Leaderboards**: Adding scoring and global leaderboards for competitive play.

---

## Installation and Setup

### Requirements

- Unity Editor (2021.3 or higher recommended)
- Visual Studio or any preferred code editor

### How to Play Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/YourUsername/brick-breaker-space.git
