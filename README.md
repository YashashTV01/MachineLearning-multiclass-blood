# Deep Learning Medical Image Analysis Example

This project explores different convolutional neural network (CNN) models for image classification using the BloodMNIST dataset. Three models with varying architectures were implemented and analyzed for multiclass classification.

## 1. BloodMNISTbb

### Model Architecture
- Input Layer
- Two Convolutional Layers (32 filters, 3x3 kernel, ReLU activation)
- Two MaxPooling Layers (2x2 pool size)
- Flatten Layer
- Output Layer (Dense, Softmax activation)

### Training Results
- Increasing graph with two intersections.
- Accuracy increases throughout training.
- Loss is below the training data.
- Accuracy ends slightly above the training data.
- Achieves accuracy score of 1.0 and loss of 0.0.

## 2.2BloodMNISTbb

### Model Architecture
- Input Layer
- Two Dense Layers

### Training Results
- Increasing accuracy graph slightly above validation data.
- Loss is a curve below the training data.
- Achieves accuracy score of 1.0 and loss of 0.04.

## 3.2BloodMNISTbb

### Model Architecture
- Input Layer
- Two Convolutional Layers (32 filters, 3x3 kernel, ReLU activation)
- Two Dense Layers

### Training Results
- Increasing accuracy graph with slight intersections.
- Loss is below the training data.
- Achieves accuracy score of 1.0 and loss of 0.96.

## Conclusion

After experimenting with three different models for multiclass classification on the BloodMNIST dataset, it can be concluded that the third model (3.2BloodMNISTbb) performs better compared to the first two. This conclusion is based on the increasing accuracy, decreasing loss, and achieving an accuracy score of 1.0 with a low loss of 0.96.

These observations suggest that the third model effectively learns the patterns in the BloodMNIST dataset, resulting in accurate predictions for multiple classes.
