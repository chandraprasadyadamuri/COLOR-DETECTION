# Color Detection Project
## Overview

This is a simple and interactive Python project that lets you detect colors from an image.
Just double-click anywhere on the image, and it will instantly tell you the color name along with its RGB values.

## Setup Instructions
### 1. Install Python

Make sure you have Python 3.x installed on your system.

### 2. Install Required Libraries

Run this command in your terminal:

pip install opencv-python numpy pandas


## How to Use
### Run the program using: ###
python color_detection.py -i pic2.jpg

- Once you run the program, an image window will open

- Double-click anywhere on the image

- The detected color name and RGB values will appear on the screen

- Press ESC to close the window

## How It Works
- When you double-click, the program reads the pixel’s RGB values
- It compares those values with a dataset (colors.csv)
- It calculates the closest match using a simple distance formula
Finally, it shows the color name on the image itself
## Libraries Used
- OpenCV – for image processing

- Pandas – for handling the dataset

- NumPy – for numerical operations
## Output
Displays the color name
Shows RGB values
Works interactively with mouse clicks
## Conclusion

This project is a simple way to learn the basics of image processing and color detection using Python. It’s easy to understand and a good starting point for beginners.

## Note

This project was developed as part of an internship task.
