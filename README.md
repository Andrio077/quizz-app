# quizz-app
Quiz App

Project Overview

This quiz app is a basic interactive quiz game built with HTML, CSS, and JavaScript. The app features quizzes on various subjects like Math, General Knowledge, HTML, CSS, and JavaScript. It provides a timer feature for each question, allowing the user to select the time range (10 to 45 seconds). After answering all the questions, the app displays the score and allows the user to restart the quiz.

HTML Structure

The HTML file contains the structure of the quiz app. It consists of:

A select dropdown for the user to choose a subject.

A section to display the questions, options, timer, and score.

Buttons for answering questions and navigating to the next question.

After the quiz ends, the result is displayed with the score, and a restart button allows the user to begin again.


Key Elements:

<div id="subject-select">: Contains the dropdown to select the subject.

<div id="quiz">: Contains the quiz content, including the question and options.

<div id="result">: Displays the score after the quiz ends.


CSS Styling

The CSS file is used to style the quiz app, making it visually appealing. It includes:

Layout styling to arrange elements on the page.

Colors, fonts, and hover effects to enhance user experience.

Smooth transitions and animations for button clicks and page elements.


Key Features:

Background gradient and button hover effects for better aesthetics.

Smooth transitions for when the quiz elements appear on the screen.

Timer and option buttons with animation to improve interactivity.


JavaScript Functionality

The JavaScript file is the heart of the quiz app. It handles:

Loading questions and options.

Tracking user answers and calculating the score.

Implementing a countdown timer for each question (10 to 45 seconds, depending on the user's choice).

Displaying the final score after all questions are answered.

Allowing users to restart the quiz or select a different subject.


Key Functions:

startQuiz(): Starts the quiz by hiding the subject selection and showing the quiz interface.

loadQuestion(): Loads the current question and its options.

selectAnswer(selectedIndex): Handles the user's answer selection.

nextQuestion(): Moves to the next question or ends the quiz if all questions are answered.

resetTimer(): Resets the timer for each question.
