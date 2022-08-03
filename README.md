# Action-Detection-ML
A keypoint detection model consisting of an action detection model to decode certain actions. This is built using Tensorflow, keras to build a deep neural network introducing LSTM layers to handle the sequence of keypoints using MediaPipe Holistic Keypoints
The work is mainly divided into the following parts:
1. Importing required dependencies
2. Keypoints using MP Histolic
3.  Extract keypoint values
4. Setup folders for collection
5. Collect keypoint values for Training and Testing
6. Preprocess data and create labels and features
7. Build and Train LSTM Neural Network
8. Make predictions
9. Save weights
10. Evaluation using confusion matrix and Accuracy
11. Test in real time
