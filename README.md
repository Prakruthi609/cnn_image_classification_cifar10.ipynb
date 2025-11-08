# cnn_image_classification_cifar10.ipynb
CNN image classification project using TensorFlow/Keras and Google Colab. Classifies CIFAR-10 images into 10 categories. Includes full Colab notebook, evaluation, visualizations, and step-by-step workflow.
# CNN Image Classification on CIFAR-10

This repository contains a complete deep learning workflow for image classification using Convolutional Neural Networks (CNNs) with TensorFlow and Keras in Google Colab. The model is trained on the CIFAR-10 dataset, which comprises 60,000 32x32 color images in 10 classes.

## Dataset

- **CIFAR-10:** 50,000 training images and 10,000 test images, across 10 classes such as airplane, car, bird, cat, deer, dog, frog, horse, ship, and truck.

## Project Highlights

- Loads and preprocesses the CIFAR-10 dataset
- Builds and trains a CNN from scratch using Keras/TensorFlow
- Evaluates the model on test data and reports accuracy
- Visualizes training process, accuracy/loss curves, and sample predictions
- Utilizes GPU acceleration via Google Colab for faster training

## How to Run

1. Open the notebook `cnn_image_classification_cifar10.ipynb` in Google Colab.
2. Run all cells sequentially from top to bottom.
3. The notebook will handle all steps (data loading, training, evaluation, and visualization).
4. Final results—including accuracy and example predictions—will be automatically output.

## Requirements

These are automatically handled in Colab, but to run locally:
pip install tensorflow keras numpy matplotlib

## Output

- **Accuracy and loss plots** for both training and validation sets
- **Test accuracy** displayed after model evaluation
- **Sample image predictions** shown in notebook outputs

## Extensions (Optional)

- Try modifying the model architecture or adding data augmentation for improved results.
- Experiment with training for more epochs or using different batch sizes.

## Credits

Built as a practical machine learning project for image classification coursework.
