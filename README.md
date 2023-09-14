# Hand Gesture Control using MediaPipe and PyAutoGUI

This project demonstrates hand gesture control of keyboard inputs using MediaPipe and PyAutoGUI libraries. It allows you to control certain keyboard commands by detecting hand gestures from a webcam feed.

## Installation

1. Install the required dependencies:
   - OpenCV: `pip install opencv-python`
   - Mediapipe: `pip install mediapipe`
   - PyAutoGUI: `pip install pyautogui`

2. Clone or download this repository.

## Usage

1. Connect a webcam to your computer.

2. Run the code:


3. A window will open showing the webcam feed. Position your hand in front of the camera.

4. Perform the following hand gestures to control the keyboard inputs:
- 1 finger: Presses the "right" arrow key.
- 2 fingers: Presses the "left" arrow key.
- 3 fingers: Presses the "up" arrow key.
- 4 fingers: Presses the "down" arrow key.
- 5 fingers: Presses the "space" key.

The program will detect the gestures in real-time and simulate the corresponding keyboard inputs.

## Notes

- The code assumes that only one hand is present in the camera frame. It will track the landmarks and gestures of the first detected hand.
- The gesture recognition may not be 100% accurate and may require some adjustments or fine-tuning for different lighting conditions or hand shapes.
- Press the "Esc" key to exit the program.

## Contributing

Contributions to this project are welcome. If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request on GitHub.

## License

This project is licensed under the [MIT License](LICENSE).
