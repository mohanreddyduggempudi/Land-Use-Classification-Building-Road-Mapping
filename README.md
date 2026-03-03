Land Use Classification – Building and Road Mapping

This project implements a computer vision-based system to classify aerial images into major land cover categories such as buildings, roads, vegetation, and water bodies using OpenCV. The system also calculates the percentage area occupied by each land class in the image.

Aim
To classify aerial images into buildings, roads, vegetation, and water using OpenCV and compute the percentage area of each land cover class.

Technologies Used
Python
OpenCV
NumPy
Matplotlib
Google Colab

Methodology
Image preprocessing
Conversion from BGR to HSV color space
HSV color-based segmentation
Morphological operations for noise removal
Contour extraction for boundary visualization
Percentage area calculation using pixel count

Applications
Urban planning and land analysis
Smart city development
Environmental monitoring
Infrastructure assessment
Land use mapping

How to Run

Install requirements:
pip install -r requirements.txt

Run the program:
python land_use_classification.py
