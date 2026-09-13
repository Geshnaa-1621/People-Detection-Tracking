# People Detection and Tracking

This project detects and tracks people in a video using YOLO, ByteTrack and OpenCV.

I built this project to understand how object detection and multi-object tracking work together. The program takes a video as input, detects people in each frame and assigns an ID to each person so they can be tracked as they move.

## Demo

![Tracking Result 1](tracking_output_1.jpeg.jpg)
![Tracking Result 2](tracking_output_2.jpeg.jpg)

## What it does

- Detects people in a video
- Tracks multiple people at the same time
- Assigns an ID to each tracked person
- Shows a bounding box around each person
- Shows the current number of people being tracked
- Saves the processed video

## Tools used

- Python
- YOLO
- ByteTrack
- OpenCV
- Google Colab

## How it works

The video is read frame by frame using OpenCV.

YOLO is used to detect people in each frame. The detections are then passed to ByteTrack, which tracks the people between frames and assigns IDs.

The result is displayed with a bounding box and ID around each person.

Example:

```text
Person ID: 1
Person ID: 2
Person ID: 3

People Tracked: 3
