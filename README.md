# Hand Gesture Recognition using Deep Learning

## Overview
This project implements a deep learning model for recognizing hand gestures from images, enabling intuitive human-computer interaction and gesture-based control systems. It leverages the LeapGestRecog dataset from Kaggle, containing over 20,000 images of various hand gestures.

## Project Highlights
- **Dataset**: Utilized the LeapGestRecog dataset from Kaggle, featuring gestures like fist, palm, and five fingers.
- **Data Augmentation**: Implemented transformations including 10-degree random rotations, horizontal flips, and center cropping to enhance model robustness.
- **Model Architecture**: Designed a Convolutional Neural Network (CNN) with 3 convolutional layers, batch normalization, max pooling, and a fully connected layer.
- **Training**: Achieved a validation accuracy of 95% after training the model for 30 epochs with a batch size of 64.
- **Performance**: Developed using PyTorch for efficient training and real-time inference capabilities.

## Files Included
- `train.py`: Python script for training the hand gesture recognition model.
- `test.py`: Python script for testing the trained model on new images.
- `requirements.txt`: List of Python dependencies for reproducing the environment.

## Getting Started
1. **Clone the repository**:
   ```bash
   git clone https://github.com/Santhosh-reddyp/hand-gesture-recognition.git
   cd hand-gesture-recognition
Install dependencies:

bash
Copy code
pip install -r requirements.txt
Training the model:

bash
Copy code
python train.py
Testing the model:

bash
Copy code
python test.py --image_path path_to_test_image.jpg
Future Improvements

Implement real-time gesture recognition using webcam or video input.
Explore transfer learning with pre-trained models for enhanced accuracy.
Deploy the model as part of a gesture-controlled application.
Contributors

Santhosh Reddy
Acknowledgments

This project was developed as task 4 at Prodigy Infotech, leveraging deep learning techniques to enhance human-computer interaction through gesture recognition.
Feel free to explore the code and contribute to further advancements in gesture recognition technology!

rust
Copy code

This `README.md` file provides an overview of your project, instructions for getting started, key highlights, files included, and suggestions for future improvements. Adjust the details and structure as per your project specifics and preferences.





