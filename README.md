# Voice AI with Hand Gesture Interaction

## Description

Voice AI with Hand Gesture Interaction is an innovative system that utilizes voice commands and hand gestures to execute various tasks such as voice volume adjustment, application launching, mouse controlling, and web browsing. Developed in Python, this project employs a microphone and webcam as input devices, interacting with the operating system for automation to enhance user experience and efficiency. The project leverages several libraries, including OpenCV, PyAutoGUI, MediaPipe, NumPy, and Speech Recognition.

## Features

- **Voice Commands**:
  - Open and close Windows applications
  - Execute hand gestures
- **Hand Gestures**:
  - Close applications
  - Shift and close tabs
  - Increase and decrease volume
  - Change PowerPoint slides
  - And more...

## Libraries Used

- `opencv-python`
- `pyautogui`
- `mediapipe`
- `numpy`
- `speech_recognition`

## File Structure

- `gesture.py`: Contains the implementation of hand gestures.
- `handtrackingmodule.py`: Handles hand tracking functionalities.
- `main.py`: Integrates all speech commands. Executes `gesture.py` when the user speaks the command "open hand gesture."

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/voice-ai-hand-gesture.git
    cd voice-ai-hand-gesture
    ```

2. Create a virtual environment (optional but recommended):

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```

3. Install the required libraries:

    ```bash
    pip install opencv-python pyautogui mediapipe numpy speechrecognition
    ```

## Usage

1. Ensure your microphone and webcam are connected and functioning.
2. Run the main script:

    ```bash
    python main.py
    ```

3. Use voice commands and hand gestures as described to interact with your system.

## Example Commands and Gestures

- **Voice Commands**:
  - "Open [application name]"
  - "Close [application name]"
  - "Open hand gesture"

- **Hand Gestures**:
  - Gesture to close the application
  - Gesture to shift and close tabs
  - Gesture to increase and decrease volume
  - Gesture to change PowerPoint slides
  - For detailed instructions and images of hand gestures, please refer to the [Hand Gesture Guide PDF](hand_gesture_guide PDF.pdf).

## Contribution

Contributions are welcome! Please open an issue or submit a pull request for any changes or enhancements.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [OpenCV](https://opencv.org/)
- [PyAutoGUI](https://pyautogui.readthedocs.io/en/latest/)
- [MediaPipe](https://google.github.io/mediapipe/)
- [NumPy](https://numpy.org/)
- [Speech Recognition](https://pypi.org/project/SpeechRecognition/)

---

Feel free to reach out for any questions or support!
