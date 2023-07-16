# SOC-Find-Me-Out
This project is focused on building a Face Recognition Model using Convolutional Neural Networks (CNNs) and Feedforward Neural Networks in TensorFlow. The goal is to train the model to recognize 4 different celebrities. Here's an overview of the steps involved:

Face Detection (pre-processing step):
Before starting with the face recognition model, the project requires a simple task of face detection on any image of the user's choice. This will serve as a preliminary step to building a more realistic version of the face recognition model later on. OpenCV can be used for face detection, and it is advised to have some understanding of its internal working to use its inbuilt functions effectively.

Dataset:
The user is expected to choose 4 different celebrities and collect a dataset for each celebrity. The dataset should consist of at least 100 images for each celebrity, and each image should only contain the face of the celebrity. This is to ensure that the model focuses solely on recognizing the face and improves accuracy. Collecting such images may require some effort.

Model Training:
The user needs to build a Face Recognition Model using TensorFlow, which involves creating a CNN (Convolutional Neural Network) and Feedforward Neural Network. The CNN part of the model is usually responsible for feature extraction from the face images, and the Feedforward Neural Network performs the actual recognition task.

Testing:
A test set of 100 images is to be created, with 25 images for each celebrity. The user is encouraged to split the 100 images of each celebrity into 75:25 for training and testing purposes. The main objective is to achieve at least 75% accuracy on the test set, indicating the model's ability to recognize the celebrities' faces accurately.

Saving the Model:
Once the model is trained and achieves the desired accuracy on the test set, the user is expected to save the model using TensorFlow's built-in function 'save()'. This is crucial for later usage or deployment of the trained model.

Overall, the project combines concepts of face detection, CNNs, and Feedforward Neural Networks to create a Face Recognition Model capable of identifying specific celebrities from images containing their faces.
