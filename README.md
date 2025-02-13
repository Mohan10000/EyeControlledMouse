# EyeControlledMouse
# Gaze Tracking and Mouse Control System

## Overview
This project is an advanced gaze tracking and mouse control system using Mediapipe's Face Mesh, OpenCV, and PyAutoGUI. It enables hands-free cursor movement based on eye gaze direction, with additional features like blink-based clicking, adaptive speed control, and gaze heatmaps.

## Features
- **Gaze-Based Cursor Movement**: Moves the mouse cursor based on eye gaze direction.
- **Adaptive Speed Control**: Adjusts cursor speed based on user calibration.
- **Blink-Based Clicking**: Simulates mouse clicks when blinking.
- **Focus Zones**: Defines interactive screen areas based on gaze.
- **Gaze Heatmap**: Tracks and visualizes user gaze patterns.
- **Momentum-Based Smoothing**: Reduces cursor jitter for smooth motion.

## Installation
### Prerequisites
Ensure you have Python installed on your system. Then, install the required dependencies:
```sh
pip install mediapipe opencv-python pyautogui numpy matplotlib
```

## Usage
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/gaze-tracking-mouse-control.git
   cd gaze-tracking-mouse-control
   ```
2. Run the main script:
   ```sh
   python gaze_tracking.py
   ```
3. Follow on-screen instructions to calibrate the system.
4. Move your eyes to control the cursor and blink to click.

## Configuration
You can tweak the following parameters in `config.py`:
- Cursor speed multiplier
- Blink detection threshold
- Heatmap update frequency

## Contributing
Contributions are welcome! Feel free to submit issues and pull requests.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- [Mediapipe](https://mediapipe.dev/)
- [OpenCV](https://opencv.org/)
- [PyAutoGUI](https://pyautogui.readthedocs.io/)

