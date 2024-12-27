
Wordle Optimization Algorithm

This repository contains code for a Wordle-solving algorithm developed as part of a collaborative project with The New York Times. The algorithm improves gameplay efficiency and was instrumental in the development of WordleBot 2.0.

Features
- Efficient Wordle Solver: Uses advanced techniques to analyze and solve Wordle puzzles quickly and effectively.
- Gameplay Analysis: Provides insights into gameplay patterns and optimization strategies.
- Simulation-Driven Development: Capable of running large-scale simulations to fine-tune gameplay strategies.

Files Included
- `solutionNYT.txt`: A list of Wordle solutions used in the algorithm.
- `wordleNYT.txt`: A list of valid Wordle guesses.
- `wordle.java`: The main Java code containing the Wordle-solving algorithm.

Requirements
- Java: Ensure you have Java 8 or higher installed on your system.
- Input Files: Include the `solutionNYT.txt` and `wordleNYT.txt` files in the same directory as the `wordle.java` file.

How to Run
1. Clone the repository or download the project files.
2. Compile the `wordle.java` file using a Java compiler:
   javac wordle.java
3. Run the compiled program:
   java wordle
4. Observe the output, including the simulated Wordle solutions and guesses.

About the Algorithm
The algorithm leverages the following:
- Cosine Similarity: To identify the most likely correct words based on letter positioning and frequency.
- Frequency Analysis: Calculates the most common letters in the remaining possible words.
- Iterative Refinement: Removes invalid guesses and adjusts strategies dynamically.

Developer
- Latherial Calbert

License
This project is licensed under the MIT License. See LICENSE for details.
