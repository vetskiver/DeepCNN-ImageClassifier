## Image Classifier: Happy vs Sad People

This project involves creating an image classifier that distinguishes between images of happy and sad people. The goal is to train a machine learning model to accurately classify images based on the emotion displayed by the individuals in the photos.

### Deep Learning Concepts Used

- **Convolutional Neural Networks (CNNs)**: 
  - CNNs are a type of deep learning model specifically designed for analyzing visual data. They use layers of convolutions and pooling to automatically and adaptively learn spatial hierarchies of features from images.
  - **Conv2D Layers**: Convolutional layers that apply filters to the input image to create feature maps.
  - **MaxPooling2D Layers**: Pooling layers that reduce the spatial dimensions of the feature maps to retain the most important information and reduce computation.
  - **Flatten Layer**: Converts the 2D feature maps into a 1D vector for further processing.
  - **Dense Layers**: Fully connected layers that perform classification based on the extracted features.
  - **Activation Functions**: Functions like ReLU (Rectified Linear Unit) and Sigmoid that introduce non-linearities into the model, helping it learn complex patterns.
  
- **Image Preprocessing**:
  - **Scaling**: The pixel values of images are scaled to the range [0, 1] to help the model converge faster and perform better.

- **Evaluation Metrics**:
  - **Precision**: Measures the proportion of true positive predictions among all positive predictions.
  - **Recall**: Measures the proportion of true positive predictions among all actual positives.
  - **Binary Accuracy**: Measures the overall accuracy of the model in classifying images as either happy or sad.

### Data Collection

For this project, the dataset of happy and sad images was collected using a Google Chrome extension called **Download All Images**. This tool allowed for the efficient and automated downloading of images from various web sources.

- **Steps for Data Collection**:
  1. **Install the Extension**: Add the "Download All Images" extension to your Google Chrome browser.
  2. **Navigate to the Source**: Go to a website or search engine that hosts images of happy and sad people.
  3. **Use the Extension**: Configure the extension to download all relevant images from the webpage.
  4. **Organize Data**: Sort the downloaded images into appropriate directories for training and testing the model.

By utilizing this approach, a diverse set of images was gathered to train and evaluate the image classification model effectively.
