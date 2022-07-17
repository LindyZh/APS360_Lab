# APS360

5 course labs of University of Toronto APS360 (Applied Fundamentals of Deep Learning, Summer 2022).

## Required modules

see `requirements.txt`

##  Labs
### Lab_1
This lab is a **warm up** to get you used to the **PyTorch programming environment** used in the course, and also to help you **review and renew your knowledge of Python** and relevant **Python libraries**.
### Lab_2
In this lab, you will **train a convolutional neural network** to classify an image into one of two classes: "cat" or "dog". By the end of the lab, you should be able to:

- Understand at a high level the training loop for a machine learning model.
- Understand the distinction between training, validation, and test data.
- The concepts of overfitting and underfitting.
- Investigate how different hyperparameters, such as learning rate and batch size, affect the success of training.
- Compare an ANN (aka Multi-Layer Perceptron) with a CNN.
### Lab_3
You will **train a convolutional neural network** to make classifications on different hand gestures. By the end of the lab, you should be able to:

- Generate and preprocess your own data
- Load and split data for training, validation and testing
- Train a Convolutional Neural Network
- Apply transfer learning to improve your model

### Lab_4
We will use a variation of a denoising autoencoder to solve this data imputation problem. Our autoencoder will be trained using inputs that have one categorical feature artificially removed, and the goal of the autoencoder is to correctly reconstruct all features, including the one removed from the input. In the process, you are expected to learn to:

- Clean and process continuous and categorical data for machine learning.
- Implement an autoencoder that takes continuous and categorical (one-hot) inputs.
- Tune the hyperparameters of an autoencoder.
- Use baseline models to help interpret model performance.

### Lab_5
In this assignment, we will build a recurrent neural network to classify an SMS text message as "spam" or "not spam". In the process, you will

- Clean and process text data for machine learning.
- Understand and implement a character-level recurrent neural network.
- Use torchtext to build recurrent neural network models.
- Understand batching for a recurrent neural network, and use torchtext to implement RNN batching.
