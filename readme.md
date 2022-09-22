#Joseph Lamb

## Coding Quiz

##User Story
AS A coding boot camp student</br>
I WANT to take a timed quiz on JavaScript fundamentals that stores high scores</br>
SO THAT I can gauge my progress compared to my peers</br>

##Acceptance Criteria
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

##Development
#Parameters
1) There will be 5 questions in the quiz, chosen randomly with question choices listed in random order each time</br>
2) The quiz will have a timer of 60 secs</br>
3) 10 seconds will be deducted from the timer for each incorrect answer</br>
4) Scores will be saved locally with the users intials</br>

#Pseudocode
1) Make an array of questions as objects.
2) Make an array of question choices with correct as a boolean to flag the right answer choice
3) Start a 60 second timer when the quiz is started
4) Pick a question from the question array by generating a random number from 0 to question array size
5) Load the appropriate question choices from the choices array in a random order from 1 to 4
6) Display correct if right choice is selected and increase score by 1
7) Display incorrect if incorrect choice is selected and decrease timer by 10 seconds.
8) Write question array position to a "chosen" array to prevent repetition of questions
9) Select next question by generating a random number from 0 to question array size that is not in the chosen array
10) At end of quiz, all questions answered or timer expires, prompt for users initials
11) Write score and user initials to local storage
12) Display high score from user's quizzes

## Table of Contents (Optional)

If your README is long, add a table of contents to make it easy for users to find what they need.

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)

## Installation

What are the steps required to install your project? Provide a step-by-step description of how to get the development environment running.

## Usage

Provide instructions and examples for use. Include screenshots as needed.

To add a screenshot, create an `assets/images` folder in your repository and upload your screenshot to it. Then, using the relative filepath, add it to your README using the following syntax:

    ```md
    ![alt text](assets/images/screenshot.png)
    ```

## Credits

List your collaborators, if any, with links to their GitHub profiles.

If you used any third-party assets that require attribution, list the creators with links to their primary web presence in this section.

If you followed tutorials, include links to those here as well.

## License

The last section of a high-quality README file is the license. This lets other developers know what they can and cannot do with your project. If you need help choosing a license, refer to [https://choosealicense.com/](https://choosealicense.com/).

---

🏆 The previous sections are the bare minimum, and your project will ultimately determine the content of this document. You might also want to consider adding the following sections.

## Badges

![badmath](https://img.shields.io/github/languages/top/lernantino/badmath)

Badges aren't necessary, per se, but they demonstrate street cred. Badges let other developers know that you know what you're doing. Check out the badges hosted by [shields.io](https://shields.io/). You may not understand what they all represent now, but you will in time.

## Features

If your project has a lot of features, list them here.

## How to Contribute

If you created an application or package and would like other developers to contribute it, you can include guidelines for how to do so. The [Contributor Covenant](https://www.contributor-covenant.org/) is an industry standard, but you can always write your own if you'd prefer.

## Tests

Go the extra mile and write tests for your application. Then provide examples on how to run them here.