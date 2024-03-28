# Face Recognition using OpenCV

This project demonstrates face recognition using OpenCV and a trained classifier.

## Description

This Python script captures video from a webcam, detects faces, and recognizes them using OpenCV. It first identifies faces using a Haar cascade classifier, and then it utilizes additional classifiers to identify facial features such as eyes, nose, and mouth. After detecting the face and its features, the script generates a dataset of the user's face and trains a face recognition model using the LBPH (Local Binary Patterns Histograms) algorithm. Finally, it predicts and recognizes the user's face in real-time video streams.

## Files

- `script.ipynb`: Jupyter Notebook containing the main script for face detection, feature identification, data generation, training, and recognition.
- `classifier.ipynb`: Jupyter Notebook containing the code for training the face recognition model using the generated dataset.

## Workflow

1. **Face Detection:** The script utilizes a Haar cascade classifier to detect faces in the video frames captured from the webcam.

2. **Feature Detection:** Additional classifiers are used to identify facial features such as eyes, nose, and mouth within the detected faces.

3. **Data Generation:** Once the face is detected, the script generates a dataset of the user's face by capturing images from the video stream.

4. **Training:** The generated dataset is used to train a face recognition model using the LBPH algorithm.

5. **Recognition:** The trained model is then used to recognize the user's face in real-time video streams.

## Requirements

- OpenCV
- Trained face recognition model
- Haar cascade classifiers for face and feature detection

## Usage

1. Make sure you have installed the required dependencies.
2. Open and run the Jupyter Notebook `script.ipynb` to execute the face recognition script.
3. Use the Jupyter Notebook `classifier.ipynb` to train the face recognition model with your own dataset.



[Tadakamalla srikar]

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
