# 4 - Coding Quiz

## Description
This application runs a multiple choice quiz to test the user's knowledge of Javascript. It keeps there high score scores for the current session.
### User Story
AS A coding boot camp student</br>
I WANT to take a timed quiz on JavaScript fundamentals that stores high scores</br>
SO THAT I can gauge my progress compared to my peers</br>

### Acceptance Criteria
GIVEN I am taking a code quiz</br>
WHEN I click the start button</br>
THEN a timer starts and I am presented with a question</br>
WHEN I answer a question</br>
THEN I am presented with another question</br>
WHEN I answer a question incorrectly</br>
THEN time is subtracted from the clock</br>
WHEN all questions are answered or the timer reaches 0</br>
THEN the game is over</br>
WHEN the game is over</br>
THEN I can save my initials and my score</br>

### Parameters
1) There will be 6 questions in the quiz, chosen randomly with question choices listed in random order each time</br>
2) The quiz will have a timer of 60 secs</br>
3) 5 seconds will be deducted from the timer for each incorrect answer</br>
4) Scores will be saved locally with the users intials</br>

### Pseudocode
1) Make an array of questions as objects.
2) Make an array of question choices with correct as a boolean to flag the right answer choice
3) Start a 60 second timer when the quiz is started
4) Pick a question from the question array
5) Load the appropriate question choices from the choices array
6) Display correct if right choice is selected
7) Display incorrect if incorrect choice is selected and decrease timer by 5 seconds.
9) Select next question and clear current question and choices
10) At end of quiz, all questions answered or timer expires, prompt for users initials
11) Write score based on remaining time and user initials to local storage
12) Display high scores from users' quizzes
13) Provide buttons to clear high scores or restart the quiz


## Installation

The code will reside on a Github repository at the location of: 
https://github.com/jlamb88/4-Coding-Quiz.git

URL: https://jlamb88.github.io/4-Coding-Quiz/

## Usage


![alt text](assets/images/screenshot.png) 

## Credits
Developer: Joseph Lamb

## Badges

![badmath](https://img.shields.io/github/languages/top/lernantino/badmath)

