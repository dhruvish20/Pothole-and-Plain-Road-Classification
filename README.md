
Pothole Detection using VGG16

Pothole detection is a crucial task for ensuring road safety. In this project, we developed a pothole detection model using the VGG16 convolutional neural network architecture. The dataset used for training the model was obtained from Kaggle, consisting of images of roads with and without potholes.
Dataset

The dataset used for training the model is available on Kaggle, and it consists of 3,800 images of roads with and without potholes. The images are of various sizes and resolutions and were preprocessed before training to ensure consistency. The dataset was split into training and validation sets, with 80% of the images used for training and 20% for validation.
Model Architecture

The VGG16 architecture was used for this project, and we used a pre-trained model to reduce the training time and improve the accuracy of the model. We added a fully connected layer with a softmax activation function to the pre-trained model to classify the images as either potholes or no potholes.
Training

The model was trained using the Adam optimizer and a batch size of 32. The model was trained for 100 epochs, and early stopping was used to prevent overfitting. The training accuracy was 0.99, and the validation accuracy was 0.97, indicating that the model performed well on both the training and validation sets.
Results

We achieved an accuracy of 97% on the test set, demonstrating the effectiveness of our model in detecting potholes in images. We saved the model as a .h5 file named pothole_fcl.h5, which can be used for further testing and deployment.
Conclusion

In conclusion, we developed a pothole detection model using the VGG16 architecture and achieved an accuracy of 97%. Our model can be used to detect potholes in images and can be further developed for real-time pothole detection in videos. The saved model can be found in the pothole_fcl.h5 file, which can be used for further testing and deployment.


