# Robust Human Activity and Pose Detection

## Project Overview

This project demonstrates a robust human activity and pose detection system using Python, OpenCV, and MediaPipe. The system is capable of detecting various human activities based on motion intensity and performing real-time pose estimation.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Requirements](#requirements)
- [Usage](#usage)
- [File Structure](#file-structure)
- [Contributing](#contributing)

## Features

- Real-time Activity Detection : Detects activities such as walking, running, crawling, sitting, standing, eating, dancing, jumping, and stretching based on motion intensity.
- Pose Estimation : Uses MediaPipe to estimate and visualize human poses in real-time.
- Flexible Input Modes : Supports live camera feed and uploaded video files.

## Requirements

- Python 3.x
- OpenCV
- MediaPipe
- NumPy
- Camera

## Usage

1. Run the main script to start the activity and pose detection:

    ```bash
    python new.py
    ```

2. Choose the input mode:

    - For live camera feed, no additional input is needed.
    - For video file, specify the file path in the `process_feed` function call.

3. Interact with the real-time video feed:
    - The system will display detected activities and pose estimation.
    - Press `q` to quit the video feed.

## File Structure

```plaintext
robust-human-activity-pose-detection/
│
├── data/
│   └── sample_video.mp4  # Sample video file for testing
│
├── new.py
├── README.md
```

## Contributing
Contributions are welcome! Please open an issue or submit a pull request if you have any suggestions or improvements.

