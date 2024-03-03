# 4Class-LungDiseaseClassification

# Lung Disease Detection using Deep Learning

In recent times, lung diseases such as COVID-19, Tuberculosis, and Pneumonia have become significant public health concerns. Early detection is crucial for effective treatment. While previous studies achieved high accuracy in binary classifications (e.g., COVID-19 vs. Normal), this research focuses on investigating the effect of BiLSTM method in multi-class CXR image classifications and we used pre-trained architectures(VGG16, EfficientNetB7, and others) to compare the efficiency of the developed model.

## Dataset

The dataset consists of nearly 8.1k CXR images in .jpg format:
- [Lung X-Rays Grayscale](https://www.kaggle.com/datasets/samuel156/lungxrays-grayscale)

## Obtained and modified from Kaggle datasets:
- [Lungs Disease Dataset (4 types)](https://www.kaggle.com/datasets/omkarmanohardalvi/lungs-disease-dataset-4-types)
- [TB Chest X-Ray Dataset](https://www.kaggle.com/datasets/tawsifurrahman/tuberculosis-tb-chest-xray-dataset)

The dataset includes augmented images from various techniques like stretching, rotation, flipping, and padding.

## Pre-processing Techniques

1. **Scaling:** Images were scaled to 224x224 resolution for standardized input to deep learning models.
2. **Grayscaling:** Color images were converted to grayscale for simplified processing, especially in medical imaging.

## Model Architecture

The developed model utilizes Convolutional Neural Networks (CNN) for classifying CXR images into four classes: Normal, COVID-19, Pneumonia, and Tuberculosis. Additionally, Bidirectional Long Short-Term Memory (BiLSTM) is explored for capturing sequential dependencies in image classification tasks.

## Results

The model achieved high precision, recall scores (0.95 to 0.99), and F1-scores (mean of 0.97) for all four classes. The accuracy score of 0.97 demonstrates the model's excellent performance on the CXR dataset. Graphical comparisons and grad-CAM visualizations further illustrate the model's effectiveness in training and testing.

## Conclusion

Accurate and efficient classification of medical images holds promise for improving disease diagnosis and treatment outcomes.

Feel free to refer this [Research Paper](https://ieeexplore.ieee.org/document/10134132). If you have suggestions or improvements, please open an issue or submit a pull request.

Happy exploring and coding! 🚀
