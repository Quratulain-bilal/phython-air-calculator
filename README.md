# Hand Gesture Calculator

## Overview
This project is a Hand Gesture Calculator that uses a webcam to detect hand gestures and perform arithmetic operations. It employs OpenCV, MediaPipe, and NumPy to recognize finger counts as input numbers and gestures for mathematical operations.

## Features
- Detects numbers based on the number of extended fingers.
- Recognizes basic arithmetic operators (+, -, *, /).
- Displays the ongoing expression and calculated result.
- Uses a fist gesture for confirmation.
- Hands-free arithmetic operations.

## Technologies Used
- Python
- OpenCV
- MediaPipe
- NumPy

## Installation
### Prerequisites
Ensure you have Python installed (Python 3 recommended).

### Install Dependencies
```bash
pip install opencv-python numpy mediapipe
```

## How to Run
1. Clone this repository or save the script as `hand_calculator.py`.
2. Open a terminal or command prompt.
3. Run the following command:
```bash
python hand_calculator.py
```
4. The webcam will open, and you can use hand gestures to input numbers and operators.

## How It Works
- Place your hand in the input box to enter numbers based on the number of fingers extended.
- Point to the operator buttons to select an arithmetic operation.
- Use the fist gesture in the confirm box to append the number/operator to the expression.
- A double fist gesture evaluates the expression and displays the result.
- Press 'q' to quit or 'r' to reset the expression.

## Controls
- **Number Input**: Extend fingers in the input box to represent numbers.
- **Operator Selection**: Point index finger at the operator buttons.
- **Confirm Input**: Show a fist in the confirmation box.
- **Evaluate Expression**: Show both fists.
- **Reset Expression**: Point to 'R' button or press 'r'.
- **Exit**: Press 'q'.

## Example Usage
1. Show 3 fingers in the left input box (Number: 3).
2. Point to `+` operator.
3. Show 2 fingers in the right input box (Number: 2).
4. Show a fist in the confirm box.
5. Show both fists to evaluate the expression (`3+2=5`).

## Future Improvements
- Enhance gesture recognition accuracy.
- Add support for more complex mathematical expressions.
- Implement voice-based interaction.

## License
This project is open-source and free to use.
