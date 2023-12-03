# Code_Clause_Internship_Project_2-Image-to-Pencil-Sketch-App

This project focuses on converting images into pencil sketches using OpenCV, implemented within a Jupyter Notebook environment. The goal is to create an application that transforms regular images into pencil sketch-like representations.

## Overview

This project utilizes OpenCV, a popular computer vision library, to convert images to pencil sketches. The application follows a specific process to achieve this transformation, involving various image processing techniques.

## Installation

Ensure you have Python installed on your system. Install the required libraries by running the following command:

## File Descriptions
Image_to_Pencil_Sketch_App.ipynb: Jupyter Notebook containing the code for the Image-to-Pencil-Sketch application.
assets/: Directory containing sample images for testing the application.
README.md: This file, providing an overview of the project.

## Functionality
The Image-to-Pencil-Sketch application follows the following steps:

Load an image from the local file system.
Convert the image to grayscale.
Invert the grayscale image.
Apply a Gaussian blur to the inverted image.
Blend the grayscale image with the blurred image using a color dodge blend mode to create a pencil sketch effect.
Display the original image and the resulting pencil sketch side by side.
Example
An example usage of the application is demonstrated within the Jupyter Notebook, showing the step-by-step transformation of a sample image into a pencil sketch.

## Future Improvements
Potential enhancements for this project include:

Implementing additional image processing techniques for different artistic effects.
Developing a graphical user interface (GUI) for a more user-friendly experience.
Optimizing the code for better performance on larger images or in bulk processing scenarios.
Contributing
Contributions to enhance and improve the project are welcome! You can fork this repository, make changes, and submit a pull request with your improvements.
