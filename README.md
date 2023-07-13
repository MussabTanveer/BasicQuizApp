# Quiz App

## Build a Quiz App with HTML, CSS, and JavaScript

### Tools Required
* Visual Studio Code (with 'Live Server by Ritwick Dey' extension installed)
* Chrome browser (Dev tools)
* Git

### App Design
**Main Screen**
* Create a form
* Take name input (required and only alphabets and spaces allowed)
* Click the 'Play' Button (enabled if name filled)

**Questions Screen**
* Questions one by one (Only single selection allowed)
* Select the answer and click on the 'Next' button

**Last Screen**
* Display the total points obtained and the name in a table having two columns and two rows

| Name  | Points |
| ------------- | ------------- |
| John Doe  | 4  |
* The 'Go Home' button will clear the user name and start all over again

### App Architecture
* `index.html` will be the homepage 
* `app.css` will contain the CSS
* `quiz.js` will contain all the JS code

**Notes**
* Keep the UI simple.
* Make use of background colors, font colors, button styles, center align the app content, etc.
* The questions for the quiz will be hard coded in a JSON format along with their answer choices, correct answer and points (see below).
* Make the app appealing by using a fair combination of colors .
* Checkout VS code Emmet Docs https://code.visualstudio.com/docs/editor/emmet for faster development.
* Create a new repository and push all the code to GitHub.

**Sample Quiz Questions**
```
// Quiz data in JSON format
const quizData = [
    {
        question: "What is the capital of France?",
        choices: ["London", "Berlin", "Madrid", "Paris"],
        correctAnswer: 3,
        points: 2
    },
    {
        question: "Which is the largest planet in our solar system?",
        choices: ["Venus", "Jupiter", "Saturn", "Mars"],
        correctAnswer: 1,
        points: 1
    },
    {
        question: "What is the symbol for Iron in the periodic table?",
        choices: ["Fe", "Ir", "In", "I"],
        correctAnswer: 0,
        points: 3
    }
];
```

