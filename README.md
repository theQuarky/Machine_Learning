# Machine Learning Course Exercises

This repository contains programming exercises from a Machine Learning course, implemented in MATLAB/Octave. The exercises cover fundamental machine learning algorithms including linear regression and logistic regression.

## 📚 Course Content

### Exercise 1: Linear Regression
Learn the fundamentals of linear regression and gradient descent optimization.

**Topics Covered:**
- Single variable linear regression
- Multi-variable linear regression
- Gradient descent algorithm
- Cost function computation
- Feature normalization
- Normal equation method

**Files:**
- `ex1.m` - Main script for single variable linear regression
- `ex1_multi.m` - Main script for multi-variable linear regression
- `warmUpExercise.m` - Basic MATLAB/Octave warm-up
- `plotData.m` - Data visualization
- `computeCost.m` - Cost function for linear regression
- `gradientDescent.m` - Gradient descent implementation
- `computeCostMulti.m` - Cost function for multivariate regression
- `gradientDescentMulti.m` - Gradient descent for multiple variables
- `featureNormalize.m` - Feature normalization/scaling
- `normalEqn.m` - Normal equation for analytical solution

### Exercise 2: Logistic Regression
Implement logistic regression for classification problems.

**Topics Covered:**
- Binary classification
- Sigmoid function
- Logistic regression cost function
- Regularization
- Decision boundaries
- Prediction

**Files:**
- `ex2.m` - Main script for logistic regression
- `ex2_reg.m` - Main script for regularized logistic regression
- `sigmoid.m` - Sigmoid function implementation
- `costFunction.m` - Cost function for logistic regression
- `predict.m` - Prediction function
- `costFunctionReg.m` - Regularized cost function
- `plotData.m` - Data visualization
- `plotDecisionBoundary.m` - Decision boundary visualization
- `mapFeature.m` - Feature mapping for polynomial features

## 🛠️ Prerequisites

- **MATLAB** (R2018a or later) or **Octave** (4.0 or later)
- Basic understanding of linear algebra
- Familiarity with MATLAB/Octave syntax

## 📥 Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/theQuarky/Machine_Learning.git
   cd Machine_Learning
   ```

2. **Install MATLAB or Octave:**
   - **MATLAB:** Download from [MathWorks](https://www.mathworks.com/products/matlab.html)
   - **Octave:** Download from [GNU Octave](https://www.gnu.org/software/octave/)

## 🚀 Usage

### Running Exercise 1 (Linear Regression)

1. Navigate to the exercise directory:
   ```bash
   cd machine-learning-ex1/ex1
   ```

2. Open MATLAB or Octave and run:
   ```matlab
   ex1        % For single variable linear regression
   ex1_multi  % For multi-variable linear regression
   ```

3. Follow the on-screen instructions and press Enter to proceed through each section.

### Running Exercise 2 (Logistic Regression)

1. Navigate to the exercise directory:
   ```bash
   cd machine-learning-ex2/ex2
   ```

2. Open MATLAB or Octave and run:
   ```matlab
   ex2        % For basic logistic regression
   ex2_reg    % For regularized logistic regression
   ```

3. Follow the on-screen instructions and press Enter to proceed through each section.

## 📂 Repository Structure

```
Machine_Learning/
├── machine-learning-ex1/
│   ├── ex1/
│   │   ├── ex1.m                    # Main script for linear regression
│   │   ├── ex1_multi.m              # Main script for multivariate regression
│   │   ├── computeCost.m            # Cost function
│   │   ├── gradientDescent.m        # Gradient descent algorithm
│   │   ├── featureNormalize.m       # Feature normalization
│   │   ├── normalEqn.m              # Normal equation
│   │   ├── ex1data1.txt             # Dataset 1
│   │   ├── ex1data2.txt             # Dataset 2
│   │   └── lib/                     # Helper libraries
│   └── ex1.pdf                      # Exercise instructions
│
├── machine-learning-ex2/
│   ├── ex2/
│   │   ├── ex2.m                    # Main script for logistic regression
│   │   ├── ex2_reg.m                # Main script for regularized version
│   │   ├── sigmoid.m                # Sigmoid function
│   │   ├── costFunction.m           # Cost function
│   │   ├── costFunctionReg.m        # Regularized cost function
│   │   ├── predict.m                # Prediction function
│   │   ├── mapFeature.m             # Feature mapping
│   │   ├── ex2data1.txt             # Dataset 1
│   │   ├── ex2data2.txt             # Dataset 2
│   │   └── lib/                     # Helper libraries
│   └── ex2.pdf                      # Exercise instructions
│
└── README.md                        # This file
```

## 📖 Learning Objectives

By completing these exercises, you will:

- Understand the theory behind linear and logistic regression
- Implement gradient descent from scratch
- Apply feature normalization and regularization techniques
- Visualize decision boundaries for classification problems
- Gain practical experience with MATLAB/Octave programming
- Debug and optimize machine learning algorithms

## 🎯 Key Concepts

### Linear Regression
- **Cost Function:** Measures how well the model fits the training data
- **Gradient Descent:** Iterative optimization algorithm to minimize cost
- **Feature Scaling:** Normalization technique to improve convergence
- **Normal Equation:** Analytical solution for linear regression

### Logistic Regression
- **Sigmoid Function:** Maps values to probability range [0, 1]
- **Binary Classification:** Predicts discrete outcomes (0 or 1)
- **Regularization:** Prevents overfitting by penalizing large parameters
- **Decision Boundary:** Separates different classes in feature space

## 💡 Tips for Success

1. **Read the PDFs:** Each exercise folder contains a detailed PDF with instructions and theory
2. **Start Simple:** Complete functions in the order suggested by the exercise scripts
3. **Test Incrementally:** Run the main scripts after completing each function
4. **Visualize Results:** Pay attention to the plots generated - they provide insights
5. **Experiment:** Try different learning rates and iteration counts to see their effects

## 🤝 Contributing

Contributions are welcome! If you find bugs or have suggestions for improvements:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature/improvement`)
5. Open a Pull Request

## 📝 License

This project is part of a Machine Learning course. Please respect academic integrity policies if you're currently taking a similar course.

## 🙏 Acknowledgments

These exercises are based on the Stanford Machine Learning course materials. Special thanks to the course instructors and contributors.

## 📧 Contact

For questions or feedback, please open an issue in the repository.

---

**Happy Learning! 🎓**
