# Emotion-Recognition-through-CNN-Happy-or-Sad
This project employs Convolutional Neural Networks (CNN) to classify facial expressions as "happy" or "sad." Using a labeled dataset of facial images, the model is trained to accurately predict emotions. The goal is to improve real-time emotion detection for applications in mental health, user experience, and social robotics.

Abstract:
Human Emotion recognition is an essential area of research in computer vision and machine learning that aims to identify and classify human emotions from facial expressions. Facial Expression Recognition (FER) is a subfield of this area that uses machine learning algorithms to automatically detect and classify facial expressions into different emotion categories such as happy, angry, sad, surprised, etc.

Problem Statement: 
The Fer-2013 dataset is a widely used benchmark dataset in the field of facial expression recognition. It contains 35,887 grayscale images of faces with 48x48 pixels, labeled with one of seven emotion categories: Angry, Disgust, Fear, Happy, Sad, Surprise, and Neutral. This project focuses on binary classification of angry and happy emotions using the Fer-2013 dataset. The objective is to develop a robust model that can accurately identify and classify facial expressions as either angry or happy. The project will involve the following steps:
1.	Data Preparation: Preprocessing the dataset by converting the images into a format suitable for model building, such as resizing, normalization, and splitting the dataset into training and testing sets.
2.	Model Building: Developing a Convolutional Neural Network (CNN) model from scratch that can accurately classify facial expressions into the two emotion categories. The model architecture will consist of multiple layers, including Convolutional layers, Pooling layers, Flatten layers, and Dense layers.
3.	Model Training: Training the CNN model on the training set to learn the patterns and features in the facial expressions that distinguish between angry and happy emotions. The training process will involve adjusting the model's weights and biases using an optimization algorithm such as Stochastic Gradient Descent (SGD).
4.	Model Evaluation: Evaluating the model's performance on the testing set to measure its accuracy and other performance metrics such as Precision, Recall, and F1-score. The model's generalization ability will also be evaluated by testing it on new and unseen images.

Scope of the project: 
•	Developing a robust understanding of Facial Expression Recognition (FER) and its applications in computer vision and machine learning.
•	Building a Convolutional Neural Network (CNN) from scratch to classify facial expressions into two emotion categories: Angry and Happy.
•	Preprocessing the Fer-2013 dataset and splitting it into training and testing sets.
•	Training the model on the training set and evaluating its performance on the testing set.
•	Testing the model’s generalization ability by passing new and unseen images to model and identifying their corresponding emotion category as happy or angry.
