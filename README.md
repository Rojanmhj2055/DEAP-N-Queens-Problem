# Project 4: N Queens problem

The n-queens problem was first invented in the mid-1800s as a puzzle for people to solve in their spare
time, but now serves as a good tool for discussing computer search algorithms.**In chess, a queen is the
only piece that can attack in any direction. The puzzle is to place a number of queens on a board
in such a way that no queen is attacking any other.**
In this project, we use **DEAP** to solve the 8 queens puzzle. The 8 queens puzzle is the problem of
placing eight queens on an 8 × 8 chessboard so that no two queens attack each other. The eight
queens puzzle is an example of the more general N queens problem of placing n non-attacking queens
on an n ×n chessboard, for which **solutions exist for all natural numbers with the exception of n = 2
and n = 3.**
![chess Logo](/chess8x8.png)
## Installation

Use the package manager [pip](https://pypi.org/project/deap/) to install deap.

```bash
pip install deap
```

## Chess Board Represntation
In this project, let us compare two different board representations.

- **Position-indexed-based:** On an 8 × 8 board, each position will be represented as an integer
from 0 to 63.We use one integer to represent the position of a queen. Each board is a list of e
ight numbers (each number is taken from 0 to 63). For example: [14, 35, 51, 42, 12, 47, 62,
2]

- **Row-indexed-based:** Each row of the board is indexed from 0 to 7. We place different
queens on different rows from top to bottom. The sequence [a b c d .... ] means that in 0-
th row, a-th column, the queen is present and so on. Each board is a list of eight numbers
(each number is taken from 0 to 7). 
Please make sure to update tests as appropriate.

## Methodology

## Results
