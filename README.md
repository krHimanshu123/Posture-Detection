# Posture Detection

[![License](https://img.shields.io/github/license/krHimanshu123/Posture-Detection?style=flat-square)](LICENSE)
[![Issues](https://img.shields.io/github/issues/krHimanshu123/Posture-Detection?style=flat-square)](https://github.com/krHimanshu123/Posture-Detection/issues)
[![Python](https://img.shields.io/badge/Python-3.7%2B-blue?style=flat-square)](https://www.python.org/)

## Overview

**Posture Detection** is a computer vision project that monitors and analyzes human posture in real time. The system provides actionable feedback to help users correct poor posture, prevent long-term musculoskeletal issues, and promote healthier habits. The project is designed for easy integration with desktops and can be extended for use in health technology and fitness applications.

---

## Features

- Real-Time Posture Recognition via webcam
- Visual & Audio Feedback for posture correction
- Personalized User Calibration
- Detailed Session Analytics & History
- Break, Stretch, and Exercise Reminders
- Desktop Notifications
- Multi-User Support
- Configurable Detection Sensitivity
- All processing is local (privacy-first)

---

## Tech Stack

- Python 3.7+
- OpenCV
- MediaPipe / TensorFlow / PyTorch
- NumPy
- Tkinter or PyQt5
- Pandas

---

## Project Structure

```
Posture-Detection/
├── main.py                 # Entry point for the application
├── requirements.txt        # Python dependencies
├── README.md
├── LICENSE
├── posture/
│   ├── __init__.py
│   ├── detector.py         # Posture detection logic
│   ├── calibrator.py       # User calibration and profile management
│   ├── feedback.py         # Visual/audio feedback system
│   ├── notifications.py    # Desktop notification integration
│   ├── analytics.py        # Session analytics, logging, reports
│   ├── config.py           # Settings, thresholds, options
│   ├── utils.py            # Utility functions
│   └── models/
│       └── pose_model.tflite  # Pre-trained model (example)
├── gui/
│   ├── __init__.py
│   ├── gui_tkinter.py      # Tkinter-based GUI
│   └── gui_pyqt.py         # PyQt5-based GUI
├── tests/
│   └── ...                 # Unit tests
├── docs/
│   └── ...                 # Documentation
└── assets/
    ├── icons/
    └── sample_images/
```

---

## Function Overview

- **main.py**: Starts the application and initializes modules.
- **detector.py**: Handles video capture and posture detection.
- **calibrator.py**: Manages user calibration and profiles.
- **feedback.py**: Provides visual and audio feedback to the user.
- **notifications.py**: Sends desktop reminders and notifications.
- **analytics.py**: Logs session data and generates reports.
- **config.py**: Stores and manages settings and preferences.
- **utils.py**: Contains helper functions and utilities.
- **gui_tkinter.py / gui_pyqt.py**: Builds and manages the user interface.

---

## Installation

```bash
git clone https://github.com/krHimanshu123/Posture-Detection.git
cd Posture-Detection
pip install -r requirements.txt
python main.py
```

---

## Contributing

We welcome contributions! Please read [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

---

## License

This project is licensed under the [MIT License](LICENSE).

---

## Contact

- GitHub: [krHimanshu123](https://github.com/krHimanshu123)
- Email: <himanshu171582@gmail.com>

---

**Empowering better posture for a healthier you!**

