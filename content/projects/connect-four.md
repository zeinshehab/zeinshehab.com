{
  "title": "Connect 4 Engine",
  "date": "2022-05-10",
  "link": "https://github.com/zeinshehab/Connect-Four",
  "image": "/img/connect_four.png",
  "description": "A high-performance Connect 4 engine using Negamax, alpha-beta pruning, iterative deepening, and null-window search. Consistently beats online 'hard' bots.",
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

In practice, the engine plays very strongly and consistently beats online Connect-Four bots on hard difficulty, while remaining fast and responsive in a terminal UI.
