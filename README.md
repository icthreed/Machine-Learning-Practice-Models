# Machine-Learning-Practice-Models-
Design and implementation of machine learning models to strengthen applied ML skills using real-world datasets
Showcase of prediction models including League of Legends Win/Loss Prediction, Stroke Occurrence Classification (Kaggle datasets)

## Projects

### Stroke Prediction
- **Dataset**: [Kaggle Stroke Dataset](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset)
- **Goal**: Predict stroke risk based on demographic and health data
- **Methods**: Multiple Logistic Regression
- **Tools**: scikit-learn, matplotlib
- **Files**: healthcare-dataset-stroke-data.csv, NobleDesktop_Stroke_Occurrence_Prediction_Model.ipynb, NobleDesktop_Stroke_Occurrence_Prediction_Model_Results.pptx
- **Results**:
  - Full dataset: ~95% accuracy, but high false negatives
  - Downsampled dataset: ~56% accuracy, with improved precision/recall balance
  - Key predictors: age and hypertension

### League of Legends Win Prediction
- **Dataset**: Custom match statistics
- **Goal**: Predict game outcomes from early-game stats
- **Methods**: Multiple Logistic Regression
- **Tools**: PyTorch, scikit-learn, matplotlib
- **Files**: league_of_legends_data_large.csv, edX_League_Win_Prediction_Model.ipynb
- **Results**: ~56% accuracy

### MNIST Number Prediction
- **Dataset**: MNIST
- **Goal**: Image Classification
- **Methods**: Convolutional Neural Net
- **Tools**: PyTorch, MNIST, numpy, torchvision
- **Files**: edX_MNIST_CNN_Model.ipynb
- **Results**: ~97% Accuracy

### CNN Tumor Prediction
- **Dataset**: Kaggle
- **Goal**: Image Classification
- **Methods**: Convolutional Neural Net
- **Tools**: PyTorch, MNIST, numpy, torchvision
- **Files**: Tumor_Detection_CNN.ipynb
- **Results**: ~88% Accuracy
