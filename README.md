# People-Detection-Tracking
People detection and tracking using YOLO, ByteTrack and OpenCV
A computer vision project that detects and tracks people in a video using YOLO, ByteTrack, and OpenCV.

## Features

- Detect people in video frames
- Assign unique tracking IDs
- Track people across consecutive frames
- Draw bounding boxes around detected people
- Display the current number of tracked people
- Save the processed video

## Technologies Used

- Python
- YOLO
- ByteTrack
- OpenCV
- Google Colab

## How It Works

The system processes the input video frame by frame.

YOLO is used to detect people in each frame. ByteTrack then associates detected people across frames and assigns tracking IDs.

The system displays:

- Bounding boxes
- Person tracking IDs
- Current number of tracked people

The processed video is saved as an output video.

## Project Pipeline

```text
Input Video
     |
     v
YOLO Person Detection
     |
     v
ByteTrack
     |
     v
Person Tracking IDs
     |
     v
Bounding Boxes + People Count
     |
     v
Output Video
