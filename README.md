# War Card Game Simulation

This project is a C++ implementation of the classic card game **War**, where two players draw and compare cards from a shuffled deck. The game runs for a specified number of rounds, determining the winner based on the card values.

## Features
- **Deck Generation**: A full deck of 52 cards is created with ranks (2–A) and suits (♠ ♥ ♦ ♣).
- **Shuffling**: The deck is shuffled before gameplay begins.
- **Card Comparison**: Cards are compared based on rank; ties are resolved by suit.
- **Game Simulation**: Players compete in a specified number of rounds.
- **Final Statistics**: The program outputs win/loss/tie counts at the end.

## How to Run

1. **Compile the program**:
   ```sh
   g++ war.cpp -o war

2. **Run the Game**
   ./war


Purpose

This project demonstrates:

    Object-Oriented Programming (OOP) with Card and Deck classes.
    Use of STL Containers, such as vector and map.
    Exception Handling for handling an empty deck.
    Randomization for shuffling the deck.
