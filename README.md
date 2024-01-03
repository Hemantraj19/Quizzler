# Quizzler App

## Overview
This is a simple quiz application named "Quizzler" that allows users to answer true/false questions. The application fetches quiz questions from the Open Trivia Database API and presents them in a graphical user interface (GUI) using the Tkinter library.

## Files
- `main.py`: The main script that sets up the quiz, creates instances of the necessary classes, and prints the final score.
- `ui.py`: The script containing the QuizInterface class, responsible for the GUI components using Tkinter.
- `quiz_brain.py`: The script with the QuizBrain class, which manages the quiz logic and questions.
- `question_model.py`: The script defining the Question class to represent individual quiz questions.
- `data.py`: The script fetching quiz data from the Open Trivia Database API.

## Usage
1. Run `main.py` to start the quiz.
2. Answer the true/false questions using the provided buttons.
3. View your score and feedback after each question.
4. The quiz ends when all questions are answered.

## Dependencies
- Python 3.x
- Tkinter library (usually included in Python installations)
- Requests library (install using `pip install requests`)

## External API
The quiz questions are fetched from the Open Trivia Database API using the `requests` library. The API provides a set of parameters to customize the quiz, such as the number of questions and question type.

## GUI Components
- **Score Label**: Displays the current score.
- **Canvas**: Displays the quiz question text.
- **True/False Buttons**: Buttons for answering the questions.
  
## Images
The true/false buttons use images (`true.png` and `false.png`) for a more visually appealing interface. Make sure the image files are present in the specified paths.

## Customization
Feel free to modify the code and customize the quiz by changing parameters, adding features, or improving the UI.

## Author
Hemant

## Acknowledgments
- This project is inspired by online quiz applications and tutorials on building GUI applications with Tkinter.
- Special thanks to the Open Trivia Database for providing the quiz questions.

Happy quizzing!
