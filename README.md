## Pedestrian Detection using HOG in Python

This repository contains the Python code for a simple pedestrian detection system using Histogram of Oriented Gradients (HOG). It demonstrates how to use HOG features for detecting people in an image and how to apply non-maximum suppression to improve the output.

The main step in this code is importing a pre-trained model for Pedestrian Detection using HOG. We are using the default people detector classifier from the HOG library for this purpose.

### Prerequisites

The code uses the following libraries:

- OpenCV (headless version)
- imutils
- numpy

You can install these libraries using pip:
```
pip install opencv-python-headless imutils numpy
```

### Usage

Run the script with your input image as an argument. The script will output two images: one with initial bounding boxes ("before suppression") and one after applying non-maximum suppression ("after suppression").

Example command:
```
python file_name.py --image path/to/your/image.jpg
```

### Note

Please be aware that HOG-based pedestrian detection may not give perfect results and might pick up some noise due to the nature of the algorithm. For more accurate object detection, consider methods such as YOLO (You Only Look Once) or SSD (Single Shot MultiBox Detector), which use deep learning techniques for higher accuracy and robustness.

### P.S.

I will soon be updating this code to improve its refinement and readability. I will also add images to showcase the results. Stay tuned! :)
