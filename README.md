# Face-Recognition-and-Verification
This project utilizes a face recognition and verification system using a pre-trained FaceNet model with the Inception architecture. The goal is to simplify the process of face verification and recognition without the need for extensive training.

## Required libraries

1. tensorflow
2. pandas
3. os
4. keras
5. PIL
6. numpy

## Usage
### 1. Installing Packages
Ensure you have the required packages installed.
### 2. Using a Pre-trained FaceNet Model
As training a ConvNet, especially FaceNet can be resource-intensive, we leverage a pre-trained model. This project utilizes a model based on the Inception architecture for efficiency. An Inception network implementation has been provided for you, and you can find it in the file inception_blocks_v2.py to get a closer look at how it is implemented.
### 3. Loading the Pre-trained Model
This step ensures that the model is ready for face verification and recognition tasks.
### 4. Applying the model
#### Face Verification
Build a database containing one encoding vector for each person who is allowed to enter the office. To generate the encoding, you'll use img_to_encoding(image_path, model), which runs the forward propagation of the model on the specified image.
#### Face Recognition
Implement a face recognition system that takes as input an image, and figures out if it is one of the authorized persons (and if so, who). Unlike the previous face verification system, you will no longer get a person's name as one of the inputs.

## Acknowledgments
Special thanks to the contributors and the FaceNet project for providing the pre-trained model and making face recognition more accessible.

Feel free to reach out for any questions or improvements!
