# Computer Vision with OpenCV

![Running GIF](https://camo.githubusercontent.com/1140a4f2ffe1d7d5432df78421909e56c97909423568e609983ec3d4fbcb0b22/68747470733a2f2f726561646d652d747970696e672d7376672e6865726f6b756170702e636f6d3f666f6e743d4f72626974726f6e2673697a653d343026636f6c6f723d253233373941353030266865696768743d3637266475726174696f6e3d333030302663656e7465723d74727565266c696e65733d254630253946253835254236254630253946253836253831254630253946253835254234254630253946253835254234254630253946253836253833254630253946253835254238254630253946253835254244254630253946253835254236254630253946253836253832)



This repository contains examples of computer vision tasks using the OpenCV library. It demonstrates face detection and background blur as well as calculating the distance of a detected face from the camera.

## Face Detection with Background Blur

### `blurBackground.ipynb`

This Jupyter Notebook demonstrates how to perform face detection and apply background blur using OpenCV.

#### How the Code Works

The code does the following:

1. Initializes the webcam for capturing video.
2. Detects faces in the video feed using the Haar Cascade classifier.
3. Applies Gaussian blur to the background while keeping the detected face sharp.
4. Displays the video feed with face detection and background blur.
5. Press 'q' to exit the program.

#### Usage

1. Make sure you have OpenCV installed: `pip install opencv-python`.

2. Run the Jupyter Notebook using a compatible environment.

3. The notebook will open your webcam feed with face detection and background blur.

## Calculating Distance of Face from Camera

### `distanceOfFaceFromCamera.ipynb`

This Jupyter Notebook demonstrates how to calculate the distance of a detected face from the camera using OpenCV.

#### How the Code Works

The code does the following:

1. Initializes the webcam for capturing video.
2. Detects faces in the video feed using the Haar Cascade classifier.
3. Estimates the distance of the detected face from the camera based on size.
4. Displays the estimated distance on the video feed.
5. Press 'q' to exit the program.

#### Usage

1. Make sure you have OpenCV installed: `pip install opencv-python`.

2. Run the Jupyter Notebook using a compatible environment.

3. The notebook will open your webcam feed with face detection and estimated distance display.

![Running GIF](  https://raw.githubusercontent.com/trinib/trinib/82213791fa9ff58d3ca768ddd6de2489ec23ffca/images/footer.svg)
