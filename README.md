# American Sign Language Detector using Convolutional Neural Networks

## Overview
The American Sign Language Detector is a real-time sign language detection application developed using Python3. This project utilizes Convolutional Neural Networks (CNNs) to detect American Sign Language alphabets and numbers from live video feeds. By leveraging the power of machine learning and computer vision techniques, this application aims to bridge the communication gap between hearing-impaired individuals and the rest of society.

## Features
- Real-time sign language detection: The application is capable of detecting American Sign Language alphabets and numbers in real-time from video feeds.
- Large training dataset: The project utilizes a training dataset consisting of 87,000 images, sourced from Kaggle, to train the CNN model effectively.
- Convolutional Neural Networks: The CNN model is trained using multiple training layers and max pooling layers, allowing it to learn and recognize intricate patterns and features in sign language gestures.
- Hand detection using Mediapipe and OpenCV: The application employs the Mediapipe and OpenCV libraries to detect hands in real-time video feeds, enabling accurate recognition and analysis of sign language gestures.

## Installation

- Clone the repository:
`git clone https://github.com/your-username/american-sign-language-detector.git`

- Navigate to the project directory:
`cd american-sign-language-detector`

## Usage
- Run the application:
`python sign_language_detector.py`
This will start the application, which will use your computer's webcam to capture live video and detect sign language gestures in real-time.

Interacting with the application:

- The application will display the video feed from your webcam.
- Place your hand(s) within the camera's field of view, ensuring they are clearly visible.
- The application will detect and recognize the sign language gestures made by your hand(s) and display the corresponding alphabet or number on the screen.
- Experiment with different gestures and observe the application's accuracy and response.

## Training

If you wish to train the CNN model using your own dataset or modify the existing model, follow these steps:

1. Prepare your training dataset:

- Gather a collection of images containing sign language alphabets and numbers.
- Organize the images into appropriate directories according to their corresponding labels.
- Update the training configuration:

2. Open the train_config.py file.
- Modify the DATASET_PATH variable to point to the directory containing your training dataset.
- Adjust other configuration parameters, such as image dimensions, batch size, and training epochs, as desired.

3. Train the CNN model:
- Run the training script:
`python train.py`
-The script will load the training dataset, train the CNN model, and save the trained model weights.

4. Update the model in the application:
- Copy the generated model weights file (model_weights.h5) to the models directory in the application.

## Contributing

Contributions to this project are welcome and encouraged. Here are some ways you can contribute:

- Report any bugs, issues, or feature requests by opening an issue on the project's GitHub repository.
- Submit a pull request with bug fixes, improvements, or additional features.
- Please ensure that any contributions align with the project's coding style and follow best practices.

## Acknowledgements

- The training dataset used in this project was sourced from Kaggle (https://www.kaggle.com/datasets/ayuraj/asl-dataset).
- The Mediapipe and OpenCV libraries were instrumental in hand detection and tracking.

  
