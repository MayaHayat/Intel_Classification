Scene classification has emerged as a crucial technology with broad applications across
various domains. From enabling autonomous vehicles to navigate diverse environments to
organizing our digital memories based on their content, scene classification offers a powerful
tool for unlocking the meaning and context within images.
This project aims to classify images into six categories, the data is found on Kaggle, at
https://www.kaggle.com/datasets/puneet6060/intel-image-classification.
The problem was originally approached using the well known softmax regression for
multi-classes. This model trains a separate linear model for each class. Each model has its
own weight vector and bias, and the linear outputs are passed through the softmax function
to obtain probabilities for each class. The softmax function normalizes the outputs to ensure
they sum to 1 and represent valid probabilities.
Next, we introduced a more complex and suitable model named CNN, the model offers a
greater range of abilities, especially in its capacity to capture complex spatial and contextual
features within the images. This allows it to differentiate between subtle details and patterns
that might be missed by simpler models.
The initial CNN model was improved using the VGG pretrained model which indeed resulted
in the highest accuracy.
This project explores the importance of data cleaning and transfer learning for the scene
classification problem. It compares different models and highlights the benefits of utilizing
pre-trained models to achieve better results.
