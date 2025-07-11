# Machine-Learning-Practice-Models-
Design and implementation of machine learning models to strengthen applied ML skills using real-world datasets
Showcase of prediction models including League of Legends Win/Loss Prediction, Stroke Occurrence Classification (Kaggle datasets)

## Projects

### CNN Tumor Prediction (2025y/07m/11d)
- **Dataset**: Kaggle
- **Goal**: Image Classification
- **Methods**: Convolutional Neural Net
- **Tools**: PyTorch, MNIST, numpy, torchvision
- **Files**: Tumor_Detection_CNN.ipynb
- **Results**: ~88% Accuracy

### MNIST Number Prediction (2025y/07m/01d)
- **Dataset**: MNIST
- **Goal**: Image Classification
- **Methods**: Convolutional Neural Net
- **Tools**: PyTorch, MNIST, numpy, torchvision
- **Files**: edX_MNIST_CNN_Model.ipynb
- **Results**: ~97% Accuracy

### Stroke Prediction (2025y/06m/14d)
- **Dataset**: [Kaggle Stroke Dataset](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset)
- **Goal**: Predict stroke risk based on demographic and health data
- **Methods**: Multiple Logistic Regression
- **Tools**: scikit-learn, matplotlib
- **Files**: NobleDesktop_Stroke_Occurrence_Prediction_Model.ipynb, NobleDesktop_Stroke_Occurrence_Prediction_Model_Results.pptx
- **Results**:
  - Full dataset: ~95% accuracy, but high false negatives
  - Downsampled dataset: ~56% accuracy, with improved precision/recall balance
  - Key predictors: age and hypertension

### League of Legends Win Prediction (2025y/06m/18d)
- **Dataset**: Custom match statistics
- **Goal**: Predict game outcomes from early-game stats
- **Methods**: Multiple Logistic Regression
- **Tools**: PyTorch, scikit-learn, matplotlib
- **Files**: league_of_legends_data_large.csv, edX_League_Win_Prediction_Model.ipynb
- **Results**: ~56% accuracy
