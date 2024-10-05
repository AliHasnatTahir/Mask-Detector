Mask Detection by Video
This repository contains the implementation of a Mask Detection system using video input. The project uses deep learning models to detect whether a person is wearing a face mask in real-time from video streams. The system is built using TensorFlow and Keras and can be applied to live video feeds or video files.

Dataset
The dataset used for training and testing the mask detection model can be downloaded from this link. Make sure to download and place the dataset in the correct directory as specified in the instructions below.

Installation
To run this project locally, follow the instructions below:

Prerequisites
Ensure that Python 3.6 or later is installed on your system. You can install all necessary dependencies by following these steps:

Clone this repository:

bash
Copy code
git clone https://github.com/your-username/mask-detection-by-video.git
cd mask-detection-by-video
Create and activate a virtual environment:

bash
Copy code
python3 -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
Install the required dependencies:

bash
Copy code
pip install -r requirements.txt
Dependencies
The following libraries are required to run the project:

TensorFlow 1.15.2 or higher
Keras 2.3.1
Imutils 0.5.3
NumPy 1.18.2
OpenCV 4.2.0
Matplotlib 3.2.1
SciPy 1.4.1
You can install them manually using:

bash
Copy code
pip install tensorflow>=1.15.2 keras==2.3.1 imutils==0.5.3 numpy==1.18.2 opencv-python==4.2.0.* matplotlib==3.2.1 scipy==1.4.1
Usage
Prepare Dataset: Download the dataset from the link provided above and place it in the project directory.

Run the Model: You can run the mask detection on a video file or a webcam stream. For example:

bash
Copy code
python detect_mask_video.py
This will start mask detection on your default webcam. You can modify the script to use a video file instead.

Files
detect_mask_video.py: Script for running mask detection on video streams.
train_mask_detector.py: Script for training the mask detection model.
requirements.txt: List of dependencies required for the project.
Results
The trained model will output real-time detection results showing the video feed with annotations indicating whether a mask is detected.
