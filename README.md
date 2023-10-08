# Image to Video Converter
This Python script converts a series of images into a video file. It utilizes the OpenCV library for image processing and video creation.

Prerequisites
Before using this script, make sure you have the following prerequisites:

Python 3: Ensure you have Python 3 installed on your system.

OpenCV (cv2): Install OpenCV for image processing using pip:

Copy code
pip install opencv-python
Usage
Image Folder: Place the images you want to convert into a video in a directory. Set the image_folder variable in your script to the path of this directory.

Output Video: Specify the name of the output video file by setting the video_name variable in your script.

Run the Script: Execute the script to convert the images into a video by running:

Copy code
python your_script_name.py
Output Video: The script will create the video in the same directory as the script with the name specified in the video_name variable.

Additional Notes
The script assumes that your images are named in alphabetical order or according to the desired sequence.

This script is configured to create videos with a frame rate of 1 frame per second (cv2.VideoWriter(video_name, fourcc, 1, (width, height))). You can adjust the frame rate by modifying the value 1 in this line.

You can change the codec used for video encoding by modifying the fourcc variable. The current setting uses the 'mp4v' codec, which you can change to other codecs as needed.

The script is designed to convert images with the '.jpg' file extension. If your images have a different extension, update the script accordingly