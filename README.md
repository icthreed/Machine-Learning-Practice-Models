# Machine-Learning-Practice-Models-
Design and implementation of machine learning models to strengthen applied ML skills using real-world datasets
Showcase of prediction models including League of Legends Win/Loss Prediction, Stroke Occurrence Classification (Kaggle datasets)

## Projects

### Stroke Prediction
- **Dataset**: [Kaggle Stroke Dataset](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset)
- **Goal**: Predict stroke risk based on demographic and health data
- **Methods**: Multiple Logistic Regression
- **Tools**: scikit-learn, matplotlib
- **Results**:
  - Full dataset: ~95% accuracy, but high false negatives
  - Downsampled dataset: ~56% accuracy, with improved precision/recall balance
  - Key predictors: age and hypertension

### League of Legends Win Prediction
- **Dataset**: Custom match statistics
- **Goal**: Predict game outcomes from early-game stats
- **Methods**: Multiple Logistic Regression
- **Tools**: PyTorch, scikit-learn, matplotlib
- **Results**: ~56% accuracy

### MNIST Number Prediction
- **Dataset**: MNIST
- **Goal**: Image Classification
- **Methods**: Convolutional Neural Net
- **Tools**: PyTorch, MNIST, numpy, torchvision
- **Results**: ~97% Accuracy

## How to Run
1. Clone this repository  
2. Install dependencies: 

## Summary Results
A brief presentation of the Stroke Prediction model results is included in `Stroke_Prediction_Results.pptx`.
