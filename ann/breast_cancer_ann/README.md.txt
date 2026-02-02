## Breast Cancer Classification using Artificial Neural Networks

### Objective
To understand how Artificial Neural Networks extend logistic regression
by learning non-linear feature interactions on tabular data.

### Dataset
- Breast Cancer Wisconsin dataset (from sklearn)

### Preprocessing
- Train-test split
- Feature standardization using StandardScaler

### Model Architecture
- Input layer: 30 features
- Hidden layers:
  - Dense(32, ReLU)
  - Dense(16, ReLU)
- Output layer:
  - Dense(1, Sigmoid)

### Loss & Optimizer
- Binary Crossentropy
- Adam optimizer

### Evaluation
- Accuracy
- Confusion Matrix
- Classification Report

### Key Learnings
- Importance of feature scaling for ANNs
- Effect of network depth on performance
- Overfitting and regularization concepts

### Future Improvements
- Hyperparameter tuning
- Comparison with classical ML models
