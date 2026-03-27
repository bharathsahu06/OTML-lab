# OTML Lab - Optimization & Machine Learning Experiments

## 📚 Overview

This website provides a comprehensive, educational resource for understanding optimization algorithms and machine learning techniques. Each experiment includes:

- **Aim**: Learning objectives
- **Description**: Conceptual explanation  
- **Algorithm**: Step-by-step procedure
- **Formulas**: Mathematical equations
- **Mathematical Procedure**: Detailed calculations
- **Simple Python Program**: Easy-to-read, well-commented code
- **Expected Output**: Sample results

## 🎯 Experiments by Course Outcome

### CO1: Gradient Descent & Optimization Fundamentals (Exp 1-3)
- **Experiment 1**: Gradient Descent for f(x) = x²
- **Experiment 2**: Newton's Method for f(x) = x⁴ - 3x² + 2
- **Experiment 3**: Stochastic Gradient Descent (SGD)

### CO2: Convex Optimization & Linear Programming (Exp 4-7)
- **Experiment 4**: Quadratic Optimization with CVXPY
- **Experiment 5**: Linear Optimization with CVXPY
- **Experiment 6**: Quadratic with Linear Constraints
- **Experiment 7**: Linear Programming with PuLP (with and without library)

### CO3: Sub-gradient & Interior Point Methods (Exp 8-11)
- **Experiment 8**: Sub-gradient Method with L1-Regularization (Dataset 1)
- **Experiment 9**: Sub-gradient Method with L1-Regularization (Dataset 2)
- **Experiment 10**: Interior Point Method (1D constraint)
- **Experiment 11**: Interior Point Method (2D constraints)

### CO4: Mini-batch & Distributed Gradient Descent (Exp 12-15)
- **Experiment 12**: Mini-batch Gradient Descent (Dataset 1)
- **Experiment 13**: Distributed Gradient Descent (larger dataset)
- **Experiment 14**: Mini-batch Gradient Descent (Dataset 2)
- **Experiment 15**: Distributed Gradient Descent (Dataset 2)

### CO5: Regularization & Advanced Optimization (Exp 16-19)
- **Experiment 16**: L1/L2 and Elastic Net Regularization
- **Experiment 17**: Group Lasso for Grouped Sparsity
- **Experiment 18**: Conjugate Gradient Method
- **Experiment 19**: Quasi-Newton Method (BFGS)

## 🚀 Getting Started

1. Open `index.html` in a web browser
2. Navigate using the organized course outcome sections
3. Click on any experiment card to view details
4. Read through the complete experiment including:
   - Problem definition
   - Step-by-step mathematical procedure
   - Python implementation
   - Expected output

## 💻 Running the Code

Each experiment includes Python code that you can:

1. **Copy and run directly**: All code is self-contained and executable
2. **Install dependencies as needed**:
   ```bash
   pip install numpy scipy scikit-learn cvxpy pulp
   ```

3. **Learn from the implementation**: Code is intentionally written to be easy to understand

## 📊 Key Concepts Covered

- **Gradient Descent**: Fundamental optimization algorithm
- **Convex Optimization**: Using professional libraries (CVXPY, PuLP)
- **Constraints**: Handling inequality and equality constraints
- **Regularization**: L1 (Lasso), L2 (Ridge), Elastic Net, Group Lasso
- **Advanced Methods**: Interior point, conjugate gradient, quasi-Newton
- **Distributed Computing**: Parallel gradient descent simulation
- **Sparsity**: Promoting sparse solutions in machine learning

## 🎓 Learning Path Recommendations

### Beginners
Start with CO1 (Experiments 1-3) to understand basic optimization concepts.

### Intermediate
Progress to CO2 (Experiments 4-7) to learn about constrained optimization.

### Advanced
Explore CO3-CO5 (Experiments 8-19) for specialized techniques.

## 📝 File Structure

```
website/
├── index.html              # Main landing page
├── css/
│   └── style.css          # Styling for all pages
├── experiments/
│   ├── exp1.html to exp19.html  # Individual experiment pages
└── README.md              # This file
```

## 🔗 Features

- **Responsive Design**: Works on desktop and mobile
- **Easy Navigation**: Breadcrumb navigation and next/previous buttons
- **Code Highlighting**: Syntax highlighting for Python code
- **Mathematical Notation**: Clear formula display
- **Step-by-Step Procedures**: Detailed mathematical examples

## 💡 Tips for Learning

1. **Read the Aim first**: Understand what problem you're solving
2. **Study the Algorithm**: Follow the step-by-step procedure
3. **Work through the Math**: Manually calculate example values
4. **Run the Code**: Copy and execute to see results
5. **Modify and Experiment**: Change parameters and observe effects

## 🎨 Color Scheme

- **Purple/Indigo**: Primary color for headers and emphasis
- **Light Gray**: Background for code and formulas
- **Green**: Output and successful results
- **Yellow**: Important formulas and highlighted information

## 📚 Additional Resources

For deeper understanding:
- Understand gradients and derivatives
- Linear algebra fundamentals
- Python NumPy and SciPy libraries
- Optimization theory and constraints

## ✨ About This Website

This educational website was created to make optimization algorithms and machine learning techniques accessible to students. Each experiment is carefully designed to:

- Explain complex concepts clearly
- Provide working Python code
- Include realistic examples with actual calculations
- Support hands-on learning

---

**Last Updated**: 2024  
**Course**: Optimization Techniques & Machine Learning (OTML)  
**Educational Resource**
