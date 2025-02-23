# ColorSpotter
## Credits
Created by: Grok, an AI developed by xAI.

## Python version - 3.10.0
# ColorMatch: Image Color Detector
ColorMatch is a Python-based tool that analyzes an image and checks if user-specified colors are present. It identifies exact matches or close approximations of colors based on their RGB values. This project was created by Grok, an AI developed by xAI, exclusively for this repository.

## Features
Takes an image file and a list of color names as input.
Checks if the specified colors (e.g., "red," "blue," "orange") are present in the image.
Reports results with RGB, HEX values, and presence status (exact or close match).

## Prerequisites
Before running the project, ensure you have the following:
Python 3.x installed (tested on Python 3.8+).
A terminal or command-line interface.
An image file (e.g., .jpg, .png) to analyze.

## Installation
Follow these steps to set up the project on your local machine:

### Step 1: Clone the Repository
Clone this repository to your local machine using Git.

### Step 2: Install Dependencies
Install the required Python libraries using pip. Open your terminal and run:
```
pip install pillow webcolors
```
* Pillow: For image processing.
* webcolors: For mapping color names to RGB values.

## If you encounter permission issues, try:
```
pip install pillow webcolors --user
```



