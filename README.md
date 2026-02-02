# FASHION-MNIST-DATASET
Clothing

## Google Collab Link : https://colab.research.google.com/drive/1a6y9A7-0Jhd1XT8pPo8g5QO1wBVE3TkB?usp=sharing


## 1. What is the Fashion MNIST dataset?
- is a collection of grayscale images of clothing items such as shirts, shoes, bags, and dresses.
Each image is 28×28 pixels and belongs to one of 10 different clothing categories.
It is commonly used as a benchmark dataset for image classification and machine learning experiments, similar to the original MNIST dataset but more challenging.

## 2. Why do we normalize image pixel values before training?
- We normalize image pixel values to scale the data between 0 and 1 instead of 0 to 255.
This helps the neural network train faster, improve numerical stability, and achieve better accuracy, because smaller and consistent values allow the optimizer to update weights more effectively.

## 3. List the layers used in the neural network and their functions.
- The neural network uses the following layers:
Flatten Layer
  - Converts the 2D image (28×28) into a 1D array of pixels.
Dense Layer (128 neurons, ReLU activation)
  - Learns important features from the images and introduces non-linearity.
Dense Output Layer (10 neurons)
  - Outputs raw prediction scores (logits) for the 10 clothing classes.
    
## 4. What does an epoch mean in model training?
- An epoch represents one complete pass of the entire training dataset through the neural network.
During each epoch, the model updates its weights based on the training data to improve accuracy and reduce loss.

## 5. Compare the predicted label and actual label for the first test image.
- For the first test image, the predicted label matches the actual label, indicating that the model correctly classified the image.
This shows that the trained model can accurately recognize clothing items it has not seen during training.

## 6. What could be done to improve the model’s accuracy?
- The model’s accuracy can be improved by:
  -Increasing the number of training epochs
  
  -Adding more hidden layers

  -Adjusting the number of neurons in each layer
  
  -Using regularization techniques such as Dropout
  
  -Applying data augmentation
  
  -Using more advanced architectures like Convolutional Neural Networks (CNNs)
