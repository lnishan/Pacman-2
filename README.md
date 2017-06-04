# Pacman-2

Assignment 2: Reflex Agent, Minimax, Alpha-Beta Pruning

Introduction to Artificial Intelligence, Spring 2017, National Chiao Tung University

## Commands

Implemented in [`multiAgents.py`](multiAgents.py).

- P3-1 Reflex Agent  
```bash
python pacman.py -p ReflexAgent-lopenClassic
```
- P3-2 Minimax  
```bash
python pacman.py -p MinimaxAgent -l minimaxClassic -a depth=4
```
- P3-3 Alpha-Beta Pruning  
```bash
python pacman.py -p AlphaBetaAgent -l smallClassic-a depth=3
```
- P3-4 Better Evaluation  
```bash
python pacman.py -p AlphaBetaAgent -l smallClassic -a depth=3,evalFn=better
```
