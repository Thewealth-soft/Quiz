# Quiz Application

This is a simple quiz application built using HTML, CSS, and JavaScript. The application allows users to take a quiz, answer questions, and see their final score.

## Features

- **Quiz Questions:** The application presents a series of questions to the user, one at a time. The questions are defined in the `quizData` array in the JavaScript code.

- **Answer Options:** For each question, the user is provided with multiple answer options. The options are displayed in a grid format.

- **Scoring:** When the user selects an answer, the application checks if it's correct. If the answer is correct, the user's score increases. The current score is displayed on the screen.

- **Exiting and Restarting:** The user can choose to exit the quiz at any point by clicking the "Exit" button. Upon exiting, the user's final score is displayed. Clicking "Exit" again will reset the quiz and allow the user to start over.

- **User Confirmation:** Before starting the quiz, the user is prompted to enter a username. Once a valid username is provided, the quiz begins. This ensures that each user's score is associated with a username.

- **Loading Animation:** During certain transitions, such as starting the quiz or restarting after exiting, a loading animation is displayed to indicate that the application is processing.

- **Sign-In (Optional):** If the application is hosted on a path corresponding to `index.html`, there's an optional sign-in feature. Users can enter an email and password, which are saved in local storage for simplicity. After signing in, the user is directed to the main quiz page (`index2.html`).

## Usage

1. Clone the repository to your local machine.
2. Open `index.html` in a web browser to access the sign-in page (optional). Enter your email and password to proceed.
3. Upon successful sign-in or directly accessing `index2.html`, you'll be prompted to enter a username for the quiz.
4. Once you've provided a username, the quiz will start, and questions will be presented one by one. Select an answer for each question.
5. After completing the quiz or clicking "Exit," your final score will be displayed.
6. If you exit the quiz and choose to start again, your score will be reset.

## File Structure

- `index.html`: The sign-in page (optional).
- `index2.html`: The main quiz page.
- `styles.css`: The stylesheet for styling the application.
- `script.js`: The JavaScript code that powers the quiz application.

## Customization

- To modify quiz questions, answers, and correct answers, update the `quizData` array in the `script.js` file.
- You can adjust the appearance of the application by modifying the styles in the `styles.css` file.

## Notes

- This application is intended as a simple example and may not include advanced features like server-side user authentication or complex question types.
- The application uses local storage for storing user details and doesn't provide a secure authentication mechanism.
- The code provided may require further optimization and improvements for production use.
- Feel free to explore, modify, and enhance the application as needed for your own projects.
