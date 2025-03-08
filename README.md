# InvisiClick - Gesture-Based Virtual Mouse Control

**InvisiClick** is a Python-based project that enables hands-free control of your computer's mouse using hand gestures. By leveraging the power of computer vision libraries such as OpenCV, MediaPipe, and PyAutoGUI, InvisiClick tracks finger movements to move the cursor and uses a pinch gesture (index + middle finger) to simulate a mouse click.
## Features

- **Index Finger Tracking**: Move the cursor on the screen by tracking the position of your index finger.
- **Pinch to Click**: Perform a mouse click by pinching your index and middle fingers together.
- **Smooth Cursor Control**: Real-time control with minimal latency for a responsive user experience.
- **Low-End PC Optimization**: Optimized for low-resource systems to maintain smooth performance (20-30 FPS).
## Tech Stack

- **OpenCV**: Computer vision library used for video capture and image processing.
- **MediaPipe**: Hand and finger tracking model that detects and tracks finger landmarks.
- **PyAutoGUI**: Python library for GUI automation, used to simulate mouse movement and clicks.


## Installation

### Prerequisites

- Python 3.x
- pip (Python package installer)

### Steps to Install

1. **Clone the repository**:

   ```bash
   git clone https://github.com/yourusername/InvisiClick.git
   cd InvisiClick

2. **Install required dependencies:**

    ```bash
    pip install -r requirements.txt
The ``requirements.txt`` should include the following libraries:

    opencv-python
    mediapipe
    pyautogui
    
3. **Run the project:**

    ```bash
    python invisi_click.py
Once the script is running, it will open your webcam and start tracking your hand gestures.
## Usage

- **Move the Cursor:** Move your index finger in front of the camera to control the cursor position on the screen.
- **Click:** Perform a pinch gesture by bringing your index and middle fingers together to simulate a mouse click.
- **Exit:** Press `q` to quit the program.


## Demo

Watch the demo video of the project in action:

[![InvisiClick Demo](https://github.com/myself-aas/InvisiClick/blob/main/InvisiClick.mp4)](https://github.com/myself-aas/InvisiClick/blob/main/InvisiClick.mp4)

## Optimizations for Low-End PCs

- Reduced frame processing resolution (e.g., 640x480) to maintain smooth performance.
- Uses bounding boxes for simpler hand detection instead of full landmark tracking to reduce processing power.
- Operates at a reduced frame rate (20-30 FPS) to keep the system responsive on lower-end hardware.

## Future Enhancements

- **Multi-gesture Support:** Implement more gestures for additional control (e.g., right-click, scroll).
- **Hand Gesture Calibration:** Improve hand recognition under varying lighting conditions and user distances.
- **Mobile Compatibility:** Extend support for mobile platforms, allowing gesture control via a smartphone camera.
## Contributing

We welcome contributions! If you'd like to improve the project, please fork the repository, create a new branch, and submit a pull request with your changes.
## License

This project is licensed under the MIT License - see the [LICENSE](https://choosealicense.com/licenses/mit/)  file for details.


## Acknowledgements

- **OpenCV:** For providing the essential computer vision tools to capture and process the video feed.
- **MediaPipe:** For accurate and real-time hand tracking.
- **PyAutoGUI:** For automating the mouse control with ease.
## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://myself-aas.github.io/portfolio/)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/me-aas/)
[![twitter](https://img.shields.io/badge/twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://x.com/myself_aas/)
