# Model-Building-Training-Evaluation-and-Validation

## Overview
This project aims to develop an AI solution for sustainable waste management through multiclass classification. By implementing deep learning models, specifically VGG16, VGG19, and ResNet50 architectures, the project aims to classify waste materials into six categories: metal, glass, organic, paper, battery, and plastic. The solution can be deployed in Indonesia to assist in efficient waste sorting and management.

## Model Architecture
Three pre-trained deep learning architectures were employed:
- VGG16
- VGG19
- ResNet50

## Model Training and Evaluation
The models were trained using a combination of checkpoint, early stopping, and learning rate reduction techniques to optimize performance. Evaluation metrics such as accuracy, loss, confusion matrix, and classification report were used to assess model performance.

## Model Comparison
- **VGG16**: Achieved the highest accuracy among the three models but with the largest model size.
- **VGG19**: Balanced performance with relatively smaller model size compared to VGG16.
- **ResNet50**: Slightly lower accuracy compared to VGG models but with the smallest model size.

## Selection of Optimal Model
Considering the trade-off between accuracy and model size, VGG19 was chosen as the optimal model for deployment. It provides a good balance of performance and resource efficiency.

## Testing with New Data
The deployed model can be tested with new data to ensure its effectiveness and reliability in real-world scenarios. Continuous monitoring and improvement may be necessary to adapt to evolving waste management needs.
