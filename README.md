# Tetris Souls Full Stack

A full-stack evolution of the original Tetris Souls project, combining a browser-based Tetris experience with the Yii PHP Framework to provide server-side functionality, persistent player data, and scalable web application architecture.

While preserving the fast-paced and highly challenging gameplay of the original version, this project extends the experience beyond the browser by integrating game data with a backend system capable of managing player information, progression, and application-level features.

## Overview

Tetris Souls Full Stack was developed to explore both game development and web application architecture within a single project.

The application combines a real-time JavaScript game engine with a PHP backend powered by Yii Framework, demonstrating how browser games can interact with server-side systems for data persistence and user management.

The project covers concepts from front-end game development as well as MVC architecture, database integration, and web application design.

## Technology Stack

### Front-End

* JavaScript
* HTML5
* CSS3

### Back-End

* PHP
* Yii Framework

### Data Layer

* MySQL

## Features

### Gameplay

* Classic Tetris-inspired mechanics
* Real-time piece movement
* Piece rotation system
* Collision detection
* Dynamic board rendering
* Progressive difficulty
* Score tracking
* Level progression

### Web Platform Features

* Yii Framework integration
* MVC architecture
* Persistent player data
* Database-driven storage
* Server-side processing
* Session management
* Structured application routing
* Scalable backend architecture

## Architecture

The project follows a separation between game logic and application infrastructure.

### Front-End Responsibilities

* Rendering game elements
* Managing user input
* Collision detection
* Piece generation
* Score calculation
* Visual updates

### Back-End Responsibilities

* User data management
* Persistent storage
* Application routing
* Session handling
* Database communication
* Business logic

## Technical Highlights

### Game Development

* Real-time game loop
* Grid-based architecture
* Dynamic DOM manipulation
* Event-driven interactions
* State management
* Collision detection algorithms

### Web Development

* MVC architecture with Yii Framework
* Database integration
* Backend and frontend communication
* Server-side data persistence
* Structured application organization
* Scalable web application design

## Project Structure

```text
project/
├── assets/
├── css/
├── js/
├── protected/
│   ├── controllers/
│   ├── models/
│   ├── views/
│   └── components/
├── themes/
├── index.php
└── README.md
```

## Requirements

### Server Requirements

* PHP 5.6+
* MySQL
* Apache or Nginx
* Yii Framework

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/tetris-souls-fullstack.git
```

Configure database access:

```php
return [
    'connectionString' => 'mysql:host=localhost;dbname=tetris_souls',
    'username' => 'root',
    'password' => '',
];
```

Start the local server and access the application through your browser.

## Educational Purpose

This project was developed to bridge the gap between browser-based game development and traditional web application development.

By combining JavaScript game mechanics with the Yii Framework, it demonstrates how interactive applications can leverage both client-side performance and server-side capabilities within a unified architecture.

## Author

Yan Matheus Gonçalves Fontão

Game Development • Full Stack Development • JavaScript • PHP • Yii Framework
