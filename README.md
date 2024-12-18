# Snake Game

The Snake Game is a timeless arcade game recreated using Python and the Pygame library. This project offers a simple yet engaging gameplay experience, while also serving as an excellent introduction to game development concepts.

---

## Features

1. **Classic Gameplay**: Players control a snake that grows in length as it consumes food, making navigation more challenging over time.
2. **User Controls**: The snake is maneuvered using keyboard inputs (arrow keys or WASD).
3. **Collision Detection**: The game ends when the snake collides with the boundaries or its own tail.
4. **Dynamic Difficulty**: As the snake grows, the challenge increases due to limited movement space.
5. **Score Tracking**: The player’s score increases with each piece of food collected, displayed in real-time.

---

## Project Structure

The project consists of the following components:

1. **Game Initialization**: Sets up the game window, defines colors, initializes variables, and prepares fonts for text rendering.
2. **Game Loop**: The main loop handles events, updates the game state, and renders the screen.
3. **Snake Movement**: The snake's movement is managed by tracking its position and updating it based on user input.
4. **Food Placement**: Food items are randomly placed on the screen using Python's random library.
5. **Collision Logic**: Detects collisions with boundaries or the snake's own body, triggering a game-over state.
6. **Score Display**: Continuously updates and displays the player’s score on the screen.

---

## Technologies Used

- **Python**: The programming language used for logic and gameplay mechanics.
- **Pygame**: A library for creating 2D games, handling graphics, events, and real-time updates.

---

## Figma Design

A Figma design has been created to visualize the layout and user interface of the Snake Game. This design provides a clear blueprint for the game’s aesthetic and user interactions. You can view the Figma design here:

[Snake Game Design on Figma](https://www.figma.com/design/3Q0oEzPZtm2YHl9Z38Fz4g/Snake-Game-Design-0?m=auto&t=raKqQuZrFAb2cdlG-6)

---

## How to Run the Project

1. **Install Pygame**:

   ```bash
   pip install pygame
   ```

2. **Clone the Repository**:

   ```bash
   git clone <repository_url>
   ```

3. **Navigate to the Project Directory**:

   ```bash
   cd snake-game
   ```

4. **Run the Game**:

   ```bash
   python snake_game.py
   ```

---

## How It Works

1. **Game Start**:

   - The game initializes with a small snake positioned at the center of the screen.
   - A piece of food appears randomly on the screen.

2. **Player Controls**:

   - The player uses the keyboard to guide the snake.
   - The snake’s movement is restricted to up, down, left, and right directions.

3. **Game Progression**:

   - Each time the snake eats food, it grows longer, and the player’s score increases.
   - New food appears at a random location on the screen.

4. **Game Over**:

   - The game ends when the snake collides with a wall or its own body.
   - The player is shown a "Game Over" message with an option to restart or quit.

---

## Code Overview

### Main Components

1. **Initialization**:

   - Sets up the game window size, colors, fonts, and other configurations.

2. **Game Loop**:

   - Continuously checks for player input, updates the snake’s position, and redraws the game screen.

3. **Functions**:

   - `message`: Displays text messages (e.g., Game Over screen).
   - `gameLoop`: The primary function that contains the game logic.

---

## Possible Extensions

1. **Levels**:
   - Add multiple levels with increasing difficulty, such as faster snake movement or obstacles.
2. **Leaderboard**:
   - Track and display high scores across multiple sessions.
3. **Graphics Enhancement**:
   - Replace basic rectangles with custom sprites for the snake and food.
4. **Sound Effects**:
   - Add audio cues for eating food and game-over events.
5. **Multiplayer Mode**:
   - Allow two players to compete in the same game.

---

## Learning Outcomes

This project demonstrates:

- Game development basics using Pygame.
- Handling user input and real-time events.
- Collision detection techniques.
- Implementation of a simple game loop.

---

## Acknowledgments

This project is inspired by the classic Snake game, a staple of early mobile and computer gaming.

---

Enjoy playing and customizing the Snake Game

