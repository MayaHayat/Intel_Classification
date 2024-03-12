This project explores classifying natural scene images using logistic regression and convolutional neural networks (CNNs). We compare the performance of these two approaches on a dataset of 14,034 RGB images (150x150x3) categorized as buildings, forests, glaciers, mountains, seas, and streets.

# Abstract

Our focus is on demonstrating the power of CNNs for image classification. We built and analyzed a CNN model, compared its performance to a logistic regression model, and discussed potential areas for improvement. The CNN model achieved a significantly higher accuracy (88.2%) compared to logistic regression (46%). We delved into the code, analyzed the model's components, and explored both its achieved performance and potential areas for future development.

# Introduction

Scene classification plays a vital role in various domains, from enabling self-driving cars to organizing digital memories. This project aims to classify images into six categories using data from Kaggle's Intel Image Classification dataset (https://www.kaggle.com/datasets/puneet6060/intel-image-classification).

We initially approached the problem using softmax regression, a common method for multi-class classification. This method trains a separate linear model for each class. We then introduced a more complex and suitable model called CNN. CNNs offer a wider range of capabilities, particularly in capturing spatial and contextual features within images. This allows them to differentiate between subtle details that simpler models might miss.

The initial CNN model was further improved using the pre-trained VGG model, achieving the highest accuracy. This project emphasizes the importance of data cleaning and transfer learning for scene classification. It compares different models and highlights the benefits of utilizing pre-trained models to achieve better results.
