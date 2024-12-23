# Crossword-Puzzle-Generator-and-Solver
A C++ project that generates and solves crossword puzzles using data structures like tries and grids. Users can input custom clues and words, and the program validates, places, and solves words interactively. Ideal for understanding the application of data structures and algorithms in puzzle-solving.


Features
Custom Crossword Generation: Users can input their own clues and corresponding words.
Interactive Solver: Prompts the user to solve the crossword puzzle by matching clues to words.
Word Validation: Utilizes a trie data structure to validate word existence and ensure placement compatibility.
Dynamic Grid: A 10x10 grid dynamically updated with each placed word.
Error Handling: Provides feedback for incorrect words or invalid placements.



Project Details
Language: C++
Key Concepts: Trie data structure, 2D grid manipulation, word validation, and interactive user input.



How It Works
Input Clues and Words:

The user inputs clues (sentences) and corresponding words.
Words are stored in a trie for validation.
Dynamic Word Placement:

Words are placed in a 10x10 grid, horizontally or vertically.
The program checks for valid placement before adding words to the grid.
Interactive Solver:

The user is prompted with clues to input corresponding words.
Words are validated against the trie and placed on the grid if correct.
Feedback:

Provides real-time feedback for correct/incorrect answers and grid updates.

Follow the Instructions:
Enter clues and corresponding words.
Solve the crossword interactively by matching clues to words.


Example Input and Output
Input:
Enter a clue: "The capital of France"
Enter the word: "PARIS"
Enter another clue? (y/n): y
Enter a clue: "The largest ocean"
Enter the word: "PACIFIC"
Output:
Clue: "The capital of France"
User Input: "PARIS"
Response: "Correct! Placed 'PARIS' on the grid."



Data Structures and Algorithms
Trie: Efficient word storage and validation.
2D Grid: Grid manipulation for word placement.
Backtracking: Handles word placement and conflicts dynamically.





