# Instructions about the project

## Navigating this repository

### code/index.html

To simplify the execution of this project, we've set up a basic webpage structure here. You don’t need to change anything here, since we already connected the JavaScript file with the HTML file with the `<script>` tag with a `src` attribute linked to `script.js`. By utilizing the `src` attribute, we specify that the JavaScript instructions are stored within a file named `script.js`.

### code/script.js

In order to simplify the execution of this project, we have provided you with a list of the steps you need to take in order to complete this project, as well as the first `alert()`. In this initial step of our learning journey with JavaScript, we're exploring the `alert()` method. This method is like a pop-up message box that appears on your screen. Imagine you've entered a virtual pizza place called the "JavaScript Pizzeria." The code you see is like a script that tells the computer to show you a message in that pop-up box.

The message itself is written between the parentheses of the `alert()` method. It's enclosed in backticks (``), which allow us to include multiple lines of text and even special placeholders like `${}` to insert dynamic content.

The message itself says, "Welcome to our JavaScript Pizzeria. Ready to begin? Click 'OK' to start."

So, when you run this code:

```
alert(
  `Welcome to our Javascript Pizzeria. Ready to Start? - Click 'OK' to begin.`
)
```

A pop-up will appear on your screen with this message, inviting you to start your journey in a fun and interactive way. This is just the beginning of using JavaScript to make things happen on a webpage!

## Steps

<aside>
💡 Don’t forget to commit and push after each step.

</aside>

### Step 1 - Welcome and introduction

a) In this iteration, you'll find a pre-written code snippet that generates a welcoming message and introduction for the user. This is done to give you a hint about how it can be implemented. The `alert()` method will greet the user. Open up the page in the browser to try it out.

b) After that, your task is to ask for the user’s name. Look into the `prompt()` method to do this. The great thing about the prompt method is that you can store the input in a variable. So, write a prompt to ask for the name and store the answer in a variable.

c) Create a new alert using the name variable to say something like “Hi, Diego!”

### Step 2 - Food choice

The goal of this iteration is to allow the user to select the type of food they want to order. If you check the provided working example, you can see that our Javascript Pizzeria offers:

- Pizza
- Pasta
- Salad

The program should use the `prompt()` method to present the user with a menu of options (Pizza, Pasta, Salad) and prompt them to enter a number corresponding to their choice. Based on the user's input, the program should determine the chosen food type (Pizza, Pasta, Salad) and display a message using the `alert()` method to confirm the user selection.

### Step 3 - Subtype choice

For this iteration, the focus is on enabling the user to choose a subtype of the selected food type. Depending on the previously chosen food type (Pizza, Pasta, Salad), the program should present the user with subtype options specific to that food type. The `prompt()` method should be used to get the user's input. The program should then determine the chosen subtype and provide feedback using the `alert()` method to confirm the selection. Tip: Use conditional statements for this.

### Step 4 - Age

In this iteration, the program should prompt the user to specify if the food is intended for a child or an adult. The `prompt()` method should be used to present the question and get the user's input. Based on the user's answer, an appropriate order message should be constructed. The program should use the `alert()` method to display the order message and the associated cost. The user's confirmation should be obtained using the `prompt()` method.

### Step 5 - Order confirmation

The final iteration involves confirming the user's order based on their previous choices. The program should evaluate the user's confirmation, and if the user confirms, a thank you message should be displayed using the `alert()` method, indicating that their meal will be prepared. If the user declines, a polite farewell message should be displayed using the `alert()` method, encouraging them to return for future orders.

## Stretch Goals

So you’ve completed all the steps above? Great job! Make sure you've committed and pushed a version of your project before starting on the stretch goals. Remember that the stretch goals are optional.

As a challenge to enhance your coding skills, consider refactoring the entire code by replacing the existing if, else-if, and else conditionals with a more streamlined and organized approach using JavaScript's switch case structure. By doing so, you'll improve code readability and maintainability, making it easier to manage various scenarios and outcomes in a more structured manner.

We recommend creating an extra `script.js` file under the name `switch.js` to have both code syntaxes available.

### How to approach the stretch goals:

- **Review the existing code:** Take a thorough look at your current code to understand the logic, conditions, and branches that determine the flow of the program based on user choices.
- **Identify cases:** Identify the different cases or options that lead to different actions or outcomes in the program. Each case should correspond to a specific choice the user makes.
- **Implement the switch statement:** Replace the existing if, else-if, and else statements with a switch statement. The switch statement allows you to evaluate a single expression against multiple possible case values.
- **Define cases:** For each case value, define the corresponding code block that should be executed when that case is matched.
- **Handle default case:** Include a default case to handle situations where none of the defined cases matches the expression. This serves as a catch-all to manage unexpected inputs.
- **Test and validate:** Thoroughly test your refactored code with various inputs to ensure that it behaves as expected and produces the correct outputs.

Refactoring the code using a switch case approach not only showcases your coding versatility but also contributes to writing cleaner and more efficient code. It's a valuable skill that can lead to more readable and maintainable programs in the long run.

