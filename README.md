# Classify-X-rays-using-CNN

The dataset contains chest x-ray images of Covid-19, Pneumonia and normal patients can be extracted from https://www.kaggle.com/datasets/prashant268/chest-xray-covid19-pneumonia

The objectives of this CNN project is practice how to apply convolutional layer in image classification project. I trained three different model and compare their performance with `accuracy` and `confusion matrix` </br>
* Model 1: Using input, flatten and output layer to train model.
* Model 2: Using input, two convolutional layer, two MaxPooling2D layer, two dropout layer, flatten layer and output to train model.
* Model 3: Using ResNet50V2 as base model, it consists of 50 layers, including convolutional layers, pooling layers, and fully connected layers.

#### Based on `20` epoch, `0.001` learning rate, `Adam` optimier, `CategoricalCrossentropy` loss function and `CategoricalAccuracy` metrics.

|         | Training Accuracy | Validation Accuraccy |  
|---------|-------------------|----------------------|
| Model 1 |      78.8103 %    |     86.1801 %        |     
| Model 2 |      88.1998 %    |     92.3913 %        |      
| Model 3 |      95.3149 %    |     92.0031 %        |     

## Model Loss, Confusion Matrix

#### Model 1:
![](/images/model_1_loss.png) </br>
![](/images/model_1.png) </br>

#### Model 2:
![](/images/model_2_loss.png) </br>
![](/images/model_2.png) </br>

#### Model 3:
![](/images/model_3_loss.png) </br>
![](/images/model_3.png) </br>

From the confusion matrix result, the accuracy of classification for `Covid-19` and `Normal` will lower than `Penumonia` since the dataset was imbalanced and most of the images are `Pneumonia`. 



