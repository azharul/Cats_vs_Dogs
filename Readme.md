## Kaggle Cats vs Dogs challenge using tensorflow

Different implementations of Kaggle cats vs dogs challenge using tensorflow.keras. This is a binary classification problem. Original dataset has 25000 training images and 12500 test images.

## Models

1. three layer convnet, each with a maxpool layer, followed by a flatten and a dense layer. Finally a sigmoid layer for binary classification (image available in model folder

2. transfer learning (used MobileNetV2/InceptionNet , added a global average layer and a dense layer for classification)


## Implementations
    
    1. No data augmentation, dropout, using model1 mentioned above
    2. Data augmentation and dropout, using model1

![model1](https://github.com/azharul/Cats_vs_Dogs/blob/master/model/Model.png)
    
    3. Data augmentation and dropout, used model2 -  best performing model
  
Project Link: [Kaggle Cats vs Dogs](https://www.kaggle.com/c/dogs-vs-cats)"
   
![cats and dogs](https://media.istockphoto.com/photos/dogs-and-cats-peeking-over-web-banner-picture-id930281684)
