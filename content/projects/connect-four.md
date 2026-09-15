{
  "title": "Connect 4 Engine",
  "date": "2022-05-10",
  "link": "https://github.com/zeinshehab/Connect-Four",
  "image": "/img/connect_four.png",
  "description": "A high-performance Connect Four AI written in C using Negamax, iterative deepening, move ordering, and null-window search. Won an internal department competition against other student bots and also outperformed public online "hard" bots.",
  "tags": ["Algorithms", "Game AI", "Negamax", "Alpha-Beta", "Iterative Deepening", "C", "Artificial Intelligence"],
  "featured": false,
  "weight": 500
}

This project implements a super fast Connect 4 engine in C, written during my undergraduate studies.

The bot is based on classical game tree search techniques:

- **Negamax search** with a score convention that favors winning in fewer moves.
- **Optimized win checking** around the last move rather than scanning the whole board.
- **Alpha-beta style pruning** via a narrow (null) search window `[α, α+1]` to quickly discard inferior moves.
- **Iterative deepening over score bounds** progressively tightening the search interval.
- **Column ordering** that explores central columns first (where winning chances are higher), improving pruning efficiency.

In practice, the engine plays strongly while remaining fast and responsive in a terminal interface. It **won an internal department competition against other student bots** and also outperformed publicly available online Connect Four bots.
