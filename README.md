# CNN-CIFAR-10-Image-Recognition
This project implements a Convolutional Neural Network (CNN) to recognize images from the CIFAR-10 dataset. It enhances the model's accuracy using data augmentation techniques such as zooming, horizontal flipping, and more. The project showcases progressive improvements across models, achieving high accuracy for image classification.

# CNN-CIFAR-10-Image-Recognition

This project implements a Convolutional Neural Network (CNN) to recognize images from the CIFAR-10 dataset. The dataset consists of 60,000 32x32 colour images categorized into 10 classes (e.g., aeroplanes, automobiles, birds, cats, etc.). The project progressively improves the model’s accuracy by applying data augmentation techniques such as horizontal flipping, zooming, random rotations, and shear transformations. The final model achieves a significant improvement in classification accuracy.

## Dataset

- **CIFAR-10**: Contains 60,000 images.
  - Training Data: 50,000 images.
  - Test Data: 10,000 images.
- Classes include aeroplanes, automobiles, birds, cats, deer, dogs, frogs, horses, ships, and trucks.

## Models

1. **Part I**: A simple CNN model with one hidden layer, achieving 66.94% accuracy on the test set.
2. **Part II**: An improved CNN architecture with deeper layers, resulting in 78.65% accuracy.
3. **Part III**: Final model enhanced with data augmentation, reaching an accuracy of 80.65%.

## Data Augmentation Techniques

- Horizontal Flips
- Zooming
- Random Rotations
- Shear Transformations

## Requirements

- Python 3.x
- TensorFlow
- Keras
- NumPy
- Matplotlib

## Installation

Install the required libraries using !pip

Model Architecture
The CNN model consists of multiple convolutional layers, followed by max-pooling and dropout for regularization. It then employs dense layers for classification. The architecture is fine-tuned through deeper layers and data augmentation techniques to enhance accuracy.

Training Strategy
Optimizer: RMSprop optimizer was used to compile the model.
Callbacks: Learning rate scheduler, model checkpointing, and early stopping were utilized to optimize training.
Evaluation: The final model was evaluated on the CIFAR-10 test set.

Conclusion
Data augmentation plays a crucial role in enhancing the model’s generalization capabilities and improving its ability to classify images more accurately. This project effectively demonstrates the progressive development of a CNN model for image classification on the CIFAR-10 dataset, highlighting the importance of deeper architectures and augmentation techniques in achieving higher accuracy.






