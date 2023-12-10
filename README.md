#Ball Tracking and Event Recording with OpenCV

Overview
This Python script utilizes the OpenCV library to perform ball tracking and event recording in a video. The program is designed to track the movement of balls of different colors across various quadrants in the video, recording events such as entry and exit for each ball.

Features
Color Detection: The program uses color-based segmentation to detect balls of different colors (green, white, yellow, orange) in the video.

Quadrant Determination: Balls are assigned to one of four quadrants based on their position within the frame.

Timestamped Event Recording: The script records entry and exit events for each ball, including the timestamp, ball color, quadrant number, and event type.

Processed Video Output: The output video visually displays the timestamp, quadrant number, ball color, and entry/exit indication.

Text File Output: The recorded events are saved in a text file in the specified format (Timestamp, BallColour, Quadrant, EventType).

How to Use
Installation: Install the required libraries using the following command:

bash
Copy code
pip install opencv-python numpy
Input Video: Replace 'path/to/input_video.mp4' with the path to your input video.

Output Paths: Specify the paths for the output video and text file:

python
Copy code
output_video_path = 'path/to/output_video.mp4'
output_text_path = 'path/to/output_events.txt'
Run the code
Customization
Color Ranges: Adjust the color ranges in the color_ranges dictionary based on your specific scenario.

Parameters: Fine-tune parameters such as area threshold, frame dimensions, and others in the script to match your requirements.

Dependencies
OpenCV
NumPy
Author
[Your Name]
