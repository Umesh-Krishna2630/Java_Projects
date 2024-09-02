# Quiz Application
The Quiz Application is a multiple-choice quiz program written in Java. It allows you to load questions from a file, present them to the user, and keep track of the score.

## Features
- Loads questions from a text file
- Presents questions one by one with multiple-choice options
- Keeps track of the user's score
- Provides a summary of the quiz results at the end

## Usage
1. Ensure you have Java installed on your machine.
2. Clone or download the Quiz Application repository.
3. Prepare the questions file:
   - Create a text file named "questions.txt" in the same directory as the Java file.
   - Populate the file with questions in the specified format (see example in the repository).
4. Open a terminal or command prompt and navigate to the project directory.
5. Compile the Java file:
```javac QuizApplication.java```
6. Run the application:
```java QuizApplication```
7. Follow the prompts in the console to answer the quiz questions.
8. After answering all the questions, the application will display a summary of the results.

## Customization
You can customize the Quiz Application according to your needs:
- Modify the `questions.txt` file to include your own set of questions.
- Adjust the scoring system by modifying the `SCORE_PER_QUESTION` constant in the Java file.
- Enhance the user interface by adding additional formatting or interaction features
- ========================================================================================================================================================
# Tic Tac Toe in Java
This is a simple implementation of the Tic Tac Toe game in Java, where two players take turns to place their mark (X or O) on a 3x3 board. The game ends when one player gets three marks in a row, column, or diagonal, or when the board is filled with marks without a winner.

## Usage
- To play the game, simply run the TicTacToe class in your Java IDE or command line.
- You will see an empty board with a prompt for the first player to enter their move. 
- Enter the row and column numbers (0-2) for your mark, and the game will update the board and prompt the other player to make their move. 
- The game will continue until there is a winner or a draw, at which point the program will display the final board and exit.

## Implementation
The game is implemented using a 2D char array to represent the board, with '-' representing empty spots, 'X' for player 1, and 'O' for player 2. The program uses a simple algorithm to check for wins and draws, by checking each row, column, and diagonal for matching marks.

The program also includes basic error handling to ensure that players cannot place their mark on an already filled spot or outside the board boundaries.

