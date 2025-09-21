# Machine Learning Specialization - Logistic Regression Implementation

## 📜 Certificate Achievement
I have successfully completed the **Machine Learning Specialization** course and earned my certificate! This repository showcases one of the key projects from the course.

<!-- Add your certificate image here -->
![Machine Learning Certificate](ML%20course%201.png)

## 📊 Project Overview: Logistic Regression

This project demonstrates the implementation of **Logistic Regression** from scratch, covering both basic and regularized versions. The implementation includes two practical applications:

### 🎯 Applications

1. **University Admission Prediction**
   - Predicts student admission based on two exam scores
   - Binary classification problem
   - Demonstrates linear decision boundary

2. **Microchip Quality Assurance**
   - Determines if microchips pass quality tests
   - Uses polynomial feature mapping
   - Implements regularized logistic regression to prevent overfitting

## 🛠️ Key Implementations

### Core Functions Implemented:
- **Sigmoid Function**: Converts linear outputs to probabilities
- **Cost Function**: Calculates logistic regression cost with cross-entropy
- **Gradient Computation**: Computes gradients for parameter optimization
- **Regularized Versions**: Prevents overfitting with L2 regularization
- **Prediction Function**: Makes binary predictions using learned parameters

### 📈 Mathematical Concepts Covered:
- Sigmoid activation function: `σ(z) = 1/(1 + e^(-z))`
- Cross-entropy loss function
- Gradient descent optimization
- Feature mapping for non-linear boundaries
- L2 regularization

## 🔧 Technical Stack
- **Python 3.7+**
- **NumPy**: Numerical computations
- **Matplotlib**: Data visualization
- **Jupyter Notebook**: Interactive development

## 📁 File Structure
```
├── C1_W3_Logistic_Regression.ipynb    # Main implementation notebook
├── data/
│   ├── ex2data1.txt                   # University admission data
│   └── ex2data2.txt                   # Microchip QA data
├── utils.py                           # Helper functions
└── README.md                          # This file
```

## 🚀 Getting Started

### Prerequisites
```bash
pip install numpy matplotlib jupyter
```

### Running the Code
1. Clone this repository
```bash
git clone https://github.com/Himasara02/Supervised-Machine-Learning
```

2. Launch Jupyter Notebook
```bash
jupyter notebook C1_W3_Logistic_Regression.ipynb
```

3. Run all cells to see the implementation in action

## 📊 Results

### University Admission Dataset
- **Training Accuracy**: ~92%
- **Decision Boundary**: Linear separation
- **Visualization**: Clear separation between admitted/rejected students

### Microchip QA Dataset
- **Training Accuracy**: ~80%
- **Decision Boundary**: Non-linear (polynomial features)
- **Regularization**: Prevents overfitting with λ = 0.01

## 🎓 Learning Outcomes

Through this project, I gained hands-on experience with:
- ✅ Implementing machine learning algorithms from scratch
- ✅ Understanding the mathematical foundations of logistic regression
- ✅ Feature engineering and polynomial feature mapping
- ✅ Regularization techniques to prevent overfitting
- ✅ Data visualization and model evaluation
- ✅ Gradient descent optimization

## 📸 Visualizations

The project includes several key visualizations:
- Training data scatter plots with class labels
- Decision boundary plots (linear and non-linear)
- Cost function convergence during training

- Coursera/edX platform (specify which one)
- The machine learning community for continuous learning resources
