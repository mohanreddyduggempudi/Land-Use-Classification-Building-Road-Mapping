Land Use Classification – Building & Road Mapping
📌 Overview
This project implements a computer vision-based system to classify aerial images into four major land cover categories:

🌳 Vegetation

💧 Water

🛣️ Roads

🏢 Buildings

The system uses OpenCV with HSV color-based segmentation, applies morphological operations to remove noise, extracts contours to visualize boundaries, and calculates the percentage area of each land class.

🚀 Features
Multi-image batch processing

HSV color-based segmentation

Morphological noise removal

Contour extraction and visualization

Pixel-based land area percentage calculation

Google Colab compatible

🛠️ Technologies Used
Python

OpenCV

NumPy

Matplotlib

Google Colab

🧠 Methodology
Upload aerial images

Convert image from BGR to HSV color space

Apply color thresholding for each land class

Perform morphological operations to remove noise

Extract contours and overlay on original image

Calculate percentage of each land cover class

📊 Sample Output
Vegetation: 39.82%
Water: 12.51%
Road: 25.33%
Building: 18.90%

🔮 Future Enhancements
Integration of Deep Learning (CNN / U-Net)

Accuracy evaluation with labeled datasets

GIS system integration

Real-time drone image processing

🎯 Applications
Urban Planning

Smart City Development

Land Use Monitoring

Encroachment Detection

Environmental Analysis

If you want, I can also generate:

A more professional GitHub-styled README with badges

Add embedded output images section

Generate a requirements.txt file

Create a short project demo description

Just tell me 👍
