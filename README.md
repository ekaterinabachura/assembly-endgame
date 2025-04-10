# Assembly: Endgame

**React-based word-guessing game to save the programming world from Assembly**

---

## Table of Contents
1. [About The Project](#about-the-project)  
   [Built With](#built-with)  
2. [How to Play](#how-to-play)  
3. [Getting Started](#getting-started)  

---

## About The Project

A React implementation of a word-guessing game where players attempt to guess a hidden programming-related word within 8 attempts. Failure results in the world being overtaken by Assembly language. Features confetti animations on victory and progressive language elimination mechanics.

### Built With
- **React**  
- **Vite**  
- **CLSX** (class utility)  
- **react-confetti** (victory animation)  

---

## How to Play
1. Guess letters using the on-screen keyboard  
2. Correct letters reveal their positions in the word  
3. Incorrect guesses eliminate programming languages  
4. 8 wrong guesses trigger a "Game Over"  
5. Win by revealing all letters before attempts run out  

Key mechanics:  
- Dynamic language chips with custom colors  
- Hidden word visualization  
- Farewell messages for eliminated languages  
- Responsive keyboard with state tracking  

---

## Getting Started
Install the dependencies and run the project
```
npm install
npm start
```

---

## App Screenshots
![Empty game start](/images/game-empty-start.png)
![Game started](/images/game-started.png)
![Game completed (win)](/images/game-completed-win.png)
![Game completed (lost)](/images/game-completed-lost.png)