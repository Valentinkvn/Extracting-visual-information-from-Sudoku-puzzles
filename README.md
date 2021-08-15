# Extracting-visual-information-from-Sudoku-puzzles

This project is part of the assignments presented by professor Bogdan Alexe (Faculty of Mathematics and Computer Science, University of Bucharest) for the Computer Vision course. 

The project was structured having three tasks:
1. Determine the configuration of a Classic Sudoku puzzle by determining which cells contain digits and which not.
2. Determine the configuration of a Jigsaw Sudoku puzzle by determining which cells contain digits and which not and also the irregular shape regions of the puzzle.
3. Having three different faces of a Cube Sudoku puzzle, find them in the image, determine their configuration and then warp them to a cube.

More details on the methods used are present in the [PDF file containing the documentation of the project](Extracting-visual-information-from-Sudoku-puzzles.pdf)

The final results (accuracy) on the train and test data were:

| Task | Train | Test |
|------|:-----:|:----:|
| 1    |  94%  |  96% |
| 2    |  93%  |  95% |
| 3    |  100% | 100% |
