
# Fruit Tracking and Inspection App-finalyearproject-

This application is designed to track and inspect fruits in real-time using YOLOv8, a state-of-the-art object detection model. It supports tracking of three types of fruits: Tomato, Banana, and Orange. The app is built with Streamlit, a fast and easy-to-use framework for building web applications, and OpenCV for handling video streams and image processing.

## Features

- **Real-time Fruit Tracking**: Utilizes YOLOv8 to track fruits in real-time from a video stream.
- **Fruit Selection**: Allows users to select the type of fruit they want to track from a sidebar.
- **Model Directory Mapping**: Maps selected fruits to their corresponding model directories for tracking.
- **Annotated Video Display**: Displays the video stream with bounding boxes and labels for tracked fruits.
- **Start/Stop Tracking**: Provides buttons to start and stop the tracking process.

## Prerequisites

- Python 3.6 or higher
- Streamlit
- OpenCV
- PIL (Python Imaging Library)
- Ultralytics YOLO

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/axtonleon/Fruit_inspection-finalyearproject-.git
   ```
2. Navigate to the project directory:
   ```
   cd Fruit_inspection-finalyearproject-
   ```


## Usage

1. Run the Streamlit app:
   ```
   streamlit run app2.py
   ```
2. Open your web browser and navigate to the URL provided by Streamlit (usually `http://localhost:8501`).
3. Select a fruit from the sidebar to start tracking.
4. Click "Start Tracking" to begin the video stream with fruit tracking.
5. Click "Stop Tracking" to stop the video stream.

