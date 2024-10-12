# Hand Tracking System

This project implements a hand tracking system using MediaPipe and OpenCV. It captures images from the webcam, detects hands in the captured images, and displays the landmarks of the detected hands.

## Features
- **Hand Detection:** Uses MediaPipe to detect hands in images.
- **Webcam Capture:** Captures images directly from the webcam for hand tracking.
- **Landmark Rendering:** Visualizes the hand landmarks on the captured image.
- **Image Saving:** Saves the processed image with detected hand landmarks.

## Prerequisites
- Python 3.x
- The following Python libraries must be installed:
  - `mediapipe`
  - `opencv-python`
  - `numpy`
  
You can install the required libraries using pip:
```bash
pip install mediapipe opencv-python
```
## Project Structure
```bash
.
├── Output Images/        # Folder to save output images with detected hand landmarks
├── Hand_tracking_System.ipynb  # Main Jupyter Notebook for hand tracking
└── README.md            # Project README file
```
## How It Works
Webcam Capture: The notebook utilizes JavaScript to access the user's webcam and capture an image.
Hand Detection: The captured image is processed to detect hands using MediaPipe.
Landmark Rendering: Detected hand landmarks are drawn on the image.
Image Saving: The processed image with hand landmarks is saved to the "Output Images" folder.

## Running the Project
Open the Jupyter Notebook:
`jupyter notebook Hand_tracking_System.ipynb`

Run the cells in the notebook to capture an image from your webcam.

Allow the application to access your webcam when prompted.

The application will process the image and display the landmarks of detected hands.

## Example Output
When running the notebook, if any hands are detected, the landmarks will be rendered on the captured image and saved in the "Output Images" folder.

## Contributing
Contributions, issues, and feature requests are welcome! Feel free to check the issues page for new ideas.

## License
This project is licensed under the MIT License.

## Acknowledgments
MediaPipe for hand tracking functionalities.
OpenCV for computer vision functionalities.
