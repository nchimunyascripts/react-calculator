# Calculator App

This is a simple calculator application built with React. It utilizes the `useReducer` hook for state management and provides basic arithmetic operations such as addition, subtraction, multiplication, and division.

## Features

- Add, subtract, multiply, and divide numbers
- Clear the calculator display
- Delete the last digit
- Handle decimal numbers
- Responsive design

## Technologies Used

- React
- CSS

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/calculator-app.git
   cd calculator-app
   ```

2. **Install dependencies:**

   ```bash
   npm install
   ```

3. **Start the development server:**

   ```bash
   npm start
   ```

   Your application should now be running at `http://localhost:3000`.

## Usage

- Click on the digits to input numbers.
- Use the operation buttons to perform calculations.
- The `AC` button clears the calculator, while the `DEL` button deletes the last digit.
- Press `=` to evaluate the current expression.

## Code Structure

- **App.js:** Main component that handles the calculator logic and UI.
- **DigitButton.js:** Component for rendering digit buttons.
- **OperationButton.js:** Component for rendering operation buttons.
- **App.css:** Contains the styles for the calculator layout.

## State Management

The application uses the `useReducer` hook to manage the state of the calculator, which includes:

- `currentOperand`: The number currently being inputted.
- `previousOperand`: The last number inputted before an operation.
- `operation`: The current operation selected.

### Actions

The following actions are defined for the reducer:

- `ADD_DIGIT`: Adds a digit to the current operand.
- `CHOOSE_OPERATION`: Chooses an arithmetic operation.
- `CLEAR`: Clears the calculator state.
- `DELETE_DIGIT`: Deletes the last digit of the current operand.
- `EVALUATE`: Evaluates the current expression.

## Contributing

Contributions are welcome! If you'd like to improve this project, feel free to fork the repository and submit a pull request.

## License

This project is open-source and available under the [MIT License](LICENSE).

## Acknowledgments

- Inspired by various calculator implementations in the React community.
