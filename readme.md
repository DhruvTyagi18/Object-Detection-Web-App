![Screenshot 2024-03-24 214310](https://github.com/DhruvTyagi18/Object-Detection-Web-App/assets/92265404/cd4cf5fc-b40a-4336-8742-384dcb44df79)


# Live Object Detection on Live Streams or Videos Flask Web Application using YOLOv8

The Object Detection Live Stream Application is a Flask-based web application that allows users to process live video streams or videos from URLs and perform real-time object detection using YOLO (You Only Look Once) model. The application uses Streamlink to fetch video streams from URLs and Ultralytics YOLO for object detection. It provides a user-friendly interface to control various settings, such as flipping the video horizontally, showing the live stream, and running object detection on the video.


## Features

- Fetch live video streams or videos from URLs using Streamlink
-Object Detection in image.
- Perform real-time object detection using Ultralytics YOLO model
- Allow users to toggle preview, flip the video horizontally, and run object detection
- Adjust object detection confidence threshold using a slider
- Display real-time object detection results on the live stream


## Prerequisites

Before running the Live Object Detection web application, ensure you have the following prerequisites installed on your system:

- Python 3.10
- pip (Python package manager)


Install the required Python packages using `pip`:

   ```
   pip install -r requirements.txt
   ```

## Usage

1. Run the Flask application:

   ```
   python app.py
   ```

2. Open your web browser and go to `http://localhost:5000` to access the application's homepage.

3. On the homepage, enter the URL of the video/live stream you want to process.

4. Click on the "Start Stream" button to initiate the video stream processing.

5. The video stream with real-time object detection will be displayed on the index page.

6. Use the control features (checkboxes and slider) to modify the behavior of the video stream and object detection.

7. To stop the video stream processing, click the "Back to Homepage" button.


## Control Features

The application provides the following control features:
 **Image Analysis*: Upload image and see the identification feature of the application.

- **Show Stream**: This checkbox allows users to toggle the preview of the video stream. When checked, the stream is visible; otherwise, a placeholder image is displayed.

- **Flip Horizontally**: This checkbox allows users to flip the video stream horizontally. When checked, the video will be horizontally mirrored.

- **Run Detection**: This checkbox enables or disables real-time object detection. When checked, the YOLOv8 model performs object detection on each frame.

- **Confidence Threshold**: Users can adjust the confidence threshold for object detection using the slider. The confidence threshold determines the minimum confidence required for an object to be detected.

## Technologies Used

- Python 3
- Flask (Web Framework)
- OpenCV (cv2) (Video Stream Processing)
- YOLOv8 (You Only Look Once) Model for Object Detection
- Socket.IO (For Real-Time Updates)
- Bootstrap (Frontend Styling)
- HTML/CSS/JavaScript


## Acknowledgments

- Ultralytics YOLO for providing the object detection model.
- Streamlink for video processing from various platforms.
- Flask, Bootstrap, jQuery, and SocketIO for the web application framework.

#   O b j e c t - D e t e c t i o n - W e b - A p p 
 
 #   O b j e c t - D e t e c t i o n - W e b - A p p 
 
 
#   O b j e c t - D e t e c t i o n - W e b - A p p 
 
 
