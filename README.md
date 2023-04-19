
# Virtual Dressing Room

This is a project for a virtual dressing room application. It allows users to virtually try on clothes, accessories, and other fashion items in a 3D environment.

## Features

-   Users can upload a photo of themselves to the application or stand Infront of the camera to see how the clothes will look on them
-   Users can select clothes from a pre-existing catalog or upload their own clothes to the application
-   The application allows users to adjust the fit of the clothes to match their body shape and size
-   Users can view the clothes from different angles and positions in the 3D environment

## Technologies Used

-   OpenCV for image processing
-   TensorFlow for machine learning
- The proposed system consist of 2 Algorithm:
	- Haar-cascade
	- Generative Adversarial Networks (GAN)
		- The Segmentation Algorithm
		- Geometric Matching Module
		- Try-on Module

## Installation

To install and run the application, follow these steps:

-  Clone the repository to your local machine
- Due to the files' size exceeding 100mb, they could not be uploaded on GitHub, so please download both files using the provided link below.:
	- pose_iter_440000.caffemodel: https://drive.google.com/file/d/1W4PfqN5681MjO1fReZ42mVBrQaZC5ces/view?usp=sharing
	- lip_jppnet_384.pb: https://drive.google.com/file/d/14HdNBHF3riufLjDtzb9ACv5Y5MmKUql2/view?usp=sharing
- Install the packages:
	- pip install opencv-python
	- pip install opencv-contrib-python 
	- pip install opencv-contrib-python-rolling
- Now execute main.py file
