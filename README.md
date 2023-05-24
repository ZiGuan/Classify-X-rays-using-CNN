# Classify-X-rays-using-CNN

The objectives of this CNN project is practice how to apply convolutional layer in image classification project. I trained three different model and compare their performance with `accuracy`,  `confusion matrix` and `classification report`. </br></br>
* Model 1: Using input, flatten and output layer to train model.
* Model 2: Using input, two convolutional layer, two MaxPooling2D layer, two dropout layer, flatten layer and output to train model.
* Model 3: Using ResNet50V2 as base model, it consists of 50 layers, including convolutional layers, pooling layers, and fully connected layers.

|         | Training Accuracy | Validation Accuraccy |  Training Loss  |  Validation Loss  |
|---------|-------------------|----------------------|-----------------|-------------------|
| Model 1 |      77.8383 %    |     79.4255 %        |      4.4109     |     3.1448        |
| Model 2 |      88.9191 %    |     93.7112 %        |      0.2903     |     0.197         |
| Model 3 |      95.1205 %    |     94.9534 %        |      0.1401     |     0.1483        |



