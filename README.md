# Calculator App

This is a simple calculator application built using React Native. It allows users to perform basic arithmetic operations such as addition, subtraction, multiplication, and division.

## Features

- Perform basic arithmetic operations: addition (+), subtraction (-), multiplication (*), and division (/).
- Clear the input and result using the "C" button.
- Display the result of calculations using the "=" button.
- Stylish user interface with responsive layout.

### Prerequisites

- Node.js installed on your system.
- React Native environment set up. Refer to the [React Native CLI Quickstart](https://reactnative.dev/docs/environment-setup) for guidance.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/calculator-app.git
   cd calculator-app
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the application:
   - For Android:
     ```bash
     npx react-native run-android
     
### Key Components:

1. **Display Section**: Displays the user's input and the calculated result.
   - `input` stores the arithmetic expression entered by the user.
   - `result` stores the evaluation of the input.

2. **Button Grid**: Contains buttons for digits, operators, and actions like clear (`C`) and equals (`=`).
   - Buttons are dynamically rendered using a 2D array for rows and columns.

3. **Footer**: Displays the text "Calc by [Your Name]" at the bottom of the screen.

4. **Styles**: Custom styles for layout and button appearance, including the green background for the "=" button.

### Styling Highlights

- The `equalButton` style ensures the "=" button has a distinct green background.
- The `footer` section at the bottom provides a personalized touch with the developer's name.

## Usage

1. Enter numbers and operators using the buttons.
2. Press the "=" button to compute the result.
3. Use the "C" button to clear the input and result.
4. The footer at the bottom displays the text "Calc by [Your Name]".

## Screenshots

![image](https://github.com/user-attachments/assets/9688b02b-7af5-41ea-a342-de8ced841130)
