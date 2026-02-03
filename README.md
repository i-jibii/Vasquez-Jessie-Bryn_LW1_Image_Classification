# Vasquez-Jessie-Bryn_LW1_Image_Classification

# Questions: (February 8, 2026)

**1.  What is the Fashion MNIST dataset?**
- The Fashion MNIST dataset is a collection of 70,000 grayscale images of clothing items, each sized 28 by 28 pixels. It contains 10 classes, including shirts, shoes, bags, and dresses. The dataset is widely used to practice image classification and evaluate machine learning models on visual data.

**2. Why do we normalize image pixel values before training?**
- We normalize image pixel values before training to scale them from 0–255 to 0–1. This helps the model learn faster, improves numerical stability, and reduces errors caused by large input values. Normalization ensures the neural network can process the data efficiently.

**3. List the layers used in the neural network and their functions.**
- The neural network uses three layers. The first is a Flatten layer that converts the 28 by 28 image into a one-dimensional vector. The second is a Dense layer with 128 neurons and ReLU activation, which extracts patterns and features from the input. The third is a Dense output layer with 10 neurons that provides raw prediction scores for each clothing class.

**4.  What does an epoch mean in model training?**
- An epoch in model training is a single full pass through the entire training dataset. During an epoch, the model sees every training image once. Multiple epochs allow the model to adjust its weights repeatedly, improving learning and overall accuracy.

**5. Compare the predicted label and actual label for the first test image.**
- For the first test image, the model predicts a label based on the learned features, which is then compared to the actual label in the dataset. If the predicted label matches the true label, the model made a correct prediction. If the labels do not match, the prediction is incorrect, highlighting areas where the model may need improvement.

**6. What could be done to improve the model’s accuracy?**
- To improve the model’s accuracy, you can increase the number of training epochs, add more hidden layers, or adjust the number of neurons in the existing layers. Using dropout layers can reduce overfitting, and switching to convolutional neural networks can better capture image patterns, leading to higher classification performance.
