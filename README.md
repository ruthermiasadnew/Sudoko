Sudoku Solver Project

This project presents several approaches to solving Sudoku puzzles using Python, including classical backtracking, stochastic methods, and a graphical user interface (GUI). It demonstrates algorithmic thinking, recursive problem solving, and user interaction design through interactive notebooks and visualizations.

Project Overview
	•	Backtracking Solver: A recursive algorithm to solve 9x9 puzzles by exploring valid number placements and backtracking when constraints are violated.
	•	Stochastic Solver: A randomized approach for solving smaller puzzles (4x4 and 9x9) by applying trial-and-error with probability-based logic.
	•	Graphical Interface (GUI): A visual tool for displaying Sudoku boards and observing solver progress.
	•	Custom Graphics Engine: Visual rendering of Sudoku boards using Python for intuitive interaction.

Features
	•	Multiple solving strategies (backtracking and stochastic)
	•	Supports different board sizes (4x4 and 9x9)
	•	GUI notebooks for visualization and interactivity
	•	Preloaded test puzzles of varying difficulty: easy, medium, and hard

Algorithms Implemented

Backtracking (Deterministic)

A classic depth-first search technique that attempts to place values in empty cells one by one, checking validity at each step. If a conflict arises, the algorithm backtracks and tries a different value.

Primary files: backtracking.ipynb, sudoku_solver_final.ipynb

Stochastic (Probabilistic)

A method using randomized guesses with conflict resolution, ideal for experimenting with smaller grids or partially filled puzzles.

Primary files: Stochastic_Solving_4x4.ipynb, Stochastic_Solving_9x9.ipynb

GUI and Visualization

The graphical interface allows users to interact with the puzzle and observe the solving process step-by-step.

Primary files: GUI.ipynb, Graphics.ipynb

Input Files

The repository includes several text files containing Sudoku puzzles:
	•	easy.txt
	•	medium.txt
	•	hard.txt

Each file represents a Sudoku grid using zeroes (0) for empty cells and digits 1–9 for filled values.

Getting Started

To run the project:
	1.	Clone the repository.
	2.	Open the .ipynb files using Jupyter Notebook, JupyterLab, or Google Colab.
	3.	Run the notebooks to solve, visualize, and experiment with different solving techniques.
