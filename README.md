# Gear Inspection Using Machine Vision
This repository contains a project focused on the automated inspection of gears using machine vision techniques. The goal of this project is to analyze an image of a gear, measure its key parameters, and determine whether the gear meets specified quality standards.

Overview

The gear inspection process involves several steps, from image acquisition to the final assessment of the gear's quality. This project automates these steps, leveraging computer vision techniques to measure and evaluate the characteristics of gears.

Features

Image Preprocessing: Convert images to grayscale, apply blurring, and edge detection.
Contour Detection: Identify the gear contour and measure its diameter.
Teeth Counting: Count the number of teeth on the gear.
Parameter Calculation: Calculate gear parameters such as module, pitch, and pitch circle diameter.
Quality Assessment: Compare measured values with original specifications to determine pass/fail status.

The machine vision-based gear inspection process consists of the following steps:

Image Acquisition: Load the gear image for processing.
Image Preprocessing: Apply blurring, smoothing, and edge detection to the image.
Contour Detection: Identify the gear's contour and measure its diameter.
Gear Segmentation: Apply segmentation and morphological operations to isolate gear teeth.
Teeth Counting: Count the number of teeth using contour methods.
Parameter Calculation: Calculate gear parameters such as module, pitch, and pitch circle diameter.
Surface Inspection: (Optional) Analyze the surface of the gear using a Convolutional Neural Network (CNN).
Quality Assessment: Compare the calculated values with the original specifications and determine the pass/fail status.

Results

The results of the inspection, including the measured values and a pass/fail indication, will be displayed in the notebook. The results can also be saved to a text file for further analysis.

Contributing
Contributions are welcome! Please fork this repository and submit a pull request with your changes.
