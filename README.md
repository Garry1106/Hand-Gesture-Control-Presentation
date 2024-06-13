
# Hand Gesture Control Presentation

## Overview

Hand Gesture Control Presentation is a Python-based project that enables users to control presentation slides using hand gestures. This project utilizes computer vision techniques to recognize hand gestures and maps them to specific presentation controls, allowing for a hands-free presentation experience. The project leverages various Python libraries such as OpenCV, Mediapipe, and PyAutoGUI to achieve this functionality.

## Features

- **Real-time Hand Gesture Recognition:** Detect and recognize hand gestures in real-time using the camera.
- **Slide Navigation:** Navigate through presentation slides using gestures (e.g., swipe left/right).
- **Gesture Customization:** Customize gestures to map to different presentation controls.
- **User-friendly Interface:** Easy to set up and use with a straightforward interface.

## Installation

### Prerequisites

- Python 3.6 or higher
- A webcam or an external camera

### Required Libraries

Install the required libraries using pip:

```bash
pip install opencv-python 
```

### Clone the Repository

Clone the repository to your local machine using the following command:

```bash
git clone https://github.com/yourusername/hand-gesture-control-presentation.git
```

## Usage

1. **Navigate to the project directory:**

   ```bash
   cd hand-gesture-control-presentation
   ```

2. **Run the main script:**

   ```bash
   python main.py
   ```

3. **Instructions:**
   - Ensure your camera is connected and functioning.
   - Stand in front of the camera and perform the gestures to control the presentation.
   - The default gestures include:
     - **Small Finger up:** Move to the next slide
     - **Thumb Up:** Move to the previous slide
     - **Index and Middle Finger Up :** Show Pointer
     - **Index Finger Up :** Annotate
     - **Index,Middle and Ring Finger Up :** Undo
     - **Show Palm:** End the presentation

## Configuration

You can customize the gestures and their corresponding actions by editing the `main.py` file. This file contains mappings between recognized gestures and the actions they trigger.

## Contributing

Contributions are welcome! If you have any ideas, suggestions, or improvements, please feel free to open an issue or submit a pull request. Follow the steps below to contribute:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature-branch`
3. Make your changes and commit them: `git commit -m 'Add new feature'`
4. Push to the branch: `git push origin feature-branch`
5. Open a pull request.


## Acknowledgements

- [OpenCV](https://opencv.org/)

## Contact

For any questions or inquiries, please contact [Gaurav Divekar](mailto:your-gauravdivekar1106@gmail.com).

---

Thank you for using Hand Gesture Control Presentation! We hope it makes your presentations more interactive and engaging.

