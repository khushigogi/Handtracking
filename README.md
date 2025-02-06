# Hand Tracking using OpenCV & Mediapipe

This project implements real-time hand tracking using **OpenCV** and **Mediapipe**. It detects hand landmarks and tracks their positions efficiently.

## Features
- Detects multiple hands in real-time
- Tracks individual hand landmarks
- Displays FPS (Frames Per Second)
- Press 'q' to exit the program

## Requirements
Make sure you have **Python 3.x** installed and install the required libraries:

```bash
pip install opencv-python mediapipe
```

## Usage
Clone the repository and run the script:

```bash
git clone https://github.com/your-username/hand-tracking.git
cd hand-tracking
python hand_tracking.py
```

## Code Overview
The main script `hand_tracking.py` consists of:

- `handDetector` class for detecting hands and extracting landmark positions
- `findHands()` method to detect and draw landmarks
- `findPosition()` method to extract landmark coordinates
- Main loop capturing video feed and processing hand tracking in real-time

## Example Output
When you run the script, the webcam will open and start detecting hands. The FPS count is displayed in the top-left corner.

## Contributing
Feel free to fork the repository and submit pull requests for improvements.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

---



