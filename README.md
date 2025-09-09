# Platformer Game

This project is part of the freeCodeCamp curriculum for learning Intermediate Object-Oriented Programming (OOP) concepts by building a platformer game.

## Project Overview

A JavaScript-based platformer game that demonstrates key OOP principles through implementation of player movement, collision detection, and interactive game elements.

## Core OOP Concepts Demonstrated

### 1. Classes and Objects
- Player class: Handles player properties and behaviors
- Platform class: Creates platforms for the game environment
- CheckPoint class: Manages checkpoint functionality

### 2. Encapsulation
- Each class encapsulates its own properties and methods
- Data hiding through private-like implementation (using closures)

### 3. Game Architecture
- Main game loop using requestAnimationFrame
- Separation of concerns between rendering, physics, and game logic

## Key Components

### Player Mechanics
- Horizontal movement with arrow keys
- Jumping with spacebar
- Gravity physics implementation
- Collision detection with platforms

### Level Design
- Multiple platforms at varying heights
- Checkpoint system with progression
- Responsive canvas sizing

### Collision System
- Platform collision from all directions
- Checkpoint collision detection
- Boundary checking

## Technical Implementation

### Animation Loop
- Uses requestAnimationFrame for smooth rendering
- Clear redraw each frame
- Delta-time independent movement

### Physics System
- Gravity simulation with variable force
- Velocity-based movement
- Collision response handling

### Input Handling
- Keyboard event listeners
- State-based input tracking (key pressed/released)
- Multi-key support for complex movements

## freeCodeCamp Curriculum

This project is part of freeCodeCamp's JavaScript Algorithms and Data Structures certification, specifically focusing on:
- Intermediate Object-Oriented Programming patterns
- HTML5 Canvas manipulation
- Game development fundamentals
- Collision detection algorithms

## How to Run

1. Open index.html in a web browser
2. Click the "Start Game" button
3. Use arrow keys to move and spacebar to jump
4. Navigate to yellow checkpoints to progress

## Educational Value

This project teaches:
- Practical application of OOP principles
- Game development techniques
- Physics simulation basics
- Canvas rendering optimization

Created as part of the freeCodeCamp curriculum - an open-source learning platform that helps millions learn to code for free.
