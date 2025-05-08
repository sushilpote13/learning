---

# Hand Cricket Game in C++

Welcome to the Hand Cricket Game! This is a simple C++ console application that simulates a hand cricket game between a user and a computer. The user can toss a coin to decide who bats first, then the user or computer can choose to bat or bowl in each round. The objective is to score more runs than the opponent.

## Features

* **Toss**: A coin toss to decide who bats first.
* **Batting and Bowling**: Player and computer can alternate between batting and bowling.
* **Scoring**: Score is calculated based on random runs between 0 and 6.
* **Out Condition**: If the user or computer chooses the same number as the opponent, they get out.

## How to Play

1. The game starts by prompting you for a toss choice (odd or even).
2. Once the toss is decided, you'll be asked whether you'd like to bat or bowl first.
3. Batting involves guessing a number between 0 and 6. If you match the computer's guess, you're out. Otherwise, your runs are added.
4. The game continues until the runs are calculated, and a winner is decided based on who scored the most runs.
5. After each game, you can choose to play again or quit.

## How to Run

1. **Clone the repository**:

   ```bash
   git clone https://github.com/your-username/HandCricketGame_CPP.git
   ```

2. **Compile the C++ code**:
   Make sure you have a C++ compiler (like `g++`).

   ```bash
   g++ -o HandCricketGame HandCricketGame.cpp
   ```

3. **Run the game**:

   ```bash
   ./HandCricketGame
   ```

## Sample Output

```text
Welcome to the game
******************************
Let's make a toss for selecting who will bat first
Enter your choice
o for odd
e for even
===============> o
you win the toss
choice the following
**************************
b for batting
f for bowling
===================> b
********************your batting is started********************
enter any number between 0 to 6
your choice ======> 3
computer's choice====> 2
your score: 3
...

******************YOU HAVE WIN THE GAME******************
```

## Project Structure

```
HandCricketGame_CPP/
├── HandCricketGame.cpp      # Main game logic
├── README.md                # This file
```

## Contributing

Feel free to fork this project, make improvements, and open a pull request!

## License

This project is open-source and available under the MIT License.

---

