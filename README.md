# Hangman

Welcome to **Hangman**, a classic word-guessing game where you try to guess the hidden word by guessing one letter at a time. If you make too many incorrect guesses, you lose!

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Technologies](#technologies)
- [Game Rules](#game-rules)

## Features

- Over 200 words to guess from
- Intuitive and responsive UI
- Real-time feedback on correct and incorrect guesses
- Track remaining attempts visually with the hangman figure
- Built with modern web technologies

## Installation

To get a local copy up and running, follow these simple steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/hangman.git
   ```
Navigate to the project directory:

   ```bash
   cd hangman
   ```
Install dependencies:

   ```bash
   npm install
   ```
Start the development server:

   ```bash
   npm run dev
   ```
The application will be available at http://localhost:5173.

## Technologies

- **Vite**: Fast build tool and development server
- **React**: JavaScript library for building user interfaces
- **TypeScript**: Strongly typed programming language that builds on JavaScript
- **CSS**: For styling the application

## Game Rules

- The game selects a random word from a list of 200 words.
- You must guess the word by suggesting letters one at a time.
- Each incorrect guess draws a part of the hangman.
- You have a limited number of incorrect guesses before the game ends.
- If you guess all the letters in the word before running out of attempts, you win!

## Demo 

You can access the live demo here : https://hangman-game-react-ts-vite.netlify.app/