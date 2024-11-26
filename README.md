This project demonstrates vehicle detection in both video and image formats using Haar Cascade Classifiers and OpenCV. It highlights the use of computer vision techniques to identify and track vehicles in real-world scenarios. Additionally, the project includes utilities for training custom Haar cascades.

-> Features:

1. Vehicle Detection in Videos:
- Processes a video file frame-by-frame.
- Uses a trained Haar cascade to detect vehicles.
- Highlights detected vehicles with bounding boxes in real-time.

2. Vehicle Detection in Images:
- Detects vehicles in static image files.
- Visualizes the bounding boxes around detected vehicles.

3. Custom Cascade Training Utilities:
- Tools for generating and training custom Haar cascade classifiers.
- Automates preparation of positive and negative samples.

-> Technologies Used:

- OpenCV: For image and video processing.
- Python: Programming language for implementing the detection pipeline.
- Haar Cascade Classifiers: A traditional machine learning approach for object detection.

-> Project Structure:

- video_testing.py: Detects and tracks vehicles in a video file.
- image_testing.py: Detects vehicles in static images.
- cascadeutils.py: Scripts and utilities for training custom Haar cascades.

-> How It Works: 

1. Pre-trained Haar Cascade:
- The project uses a pre-trained Haar cascade classifier (cascade.xml or cascade_2.xml) to detect vehicles.
- The cascade identifies patterns such as edges and shapes specific to vehicles.

2. Image Processing:
- Input images or video frames are converted to grayscale for efficient processing.
- Haar cascades scan the image to locate vehicles and return bounding box coordinates.

3. Visualization:
- Detected vehicles are outlined with green bounding boxes on the video or image.
