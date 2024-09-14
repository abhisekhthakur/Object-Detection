# person detection with unique id generated.

This script performs person tracking on a video using the YOLOv8 model.

## Requirements

* Python 3.8 or higher
* OpenCV
* Ultralytics

## Installation

Install the required packages:

#!pip install ultralytics

## Usage

1. Replace `/content/drive/MyDrive/VID_20190307_192446.mp4` with the path to your video file.
2. Run the script.
3. The output video will be saved as `output_video4.mp4`.(you can rename as you wish)

## Notes

* The script uses the `yolov8n.pt` model for object tracking. You can replace this with a different YOLOv8 model if needed.
* The `classes=0` argument in the `model.track` function specifies that only person will be  tracked. You can modify this to track different classes.
* The output video will have the same frame rate and resolution as the input video.
*Video needs to be downloaded or saved in google drive for better retrieval.
*performed in google colab, was working absolutely fine, accuracy can be fine tuned to get better results.# Object-Detection
A small project demonstrating how object detection model lookslike.
