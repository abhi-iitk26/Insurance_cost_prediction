# Insurance Cost Prediction

A machine learning project that predicts insurance charges based on personal attributes using multiple regression techniques and feature analysis.

## 📋 Project Overview

This project analyzes insurance cost data to build predictive models that can estimate insurance charges based on various personal and demographic factors. The analysis includes comprehensive exploratory data analysis (EDA), feature engineering, multicollinearity testing, and model evaluation with feature selection.

## 🎯 Objectives

- Predict insurance charges based on personal attributes
- Identify the most significant factors affecting insurance costs
- Build and evaluate multiple regression models
- Perform feature selection to optimize model performance
- Analyze relationships between different variables and insurance charges

## 📊 Dataset Features

The dataset includes the following features:
- **Age**: Age of the individual
- **BMI**: Body Mass Index
- **Children**: Number of children/dependents
- **Smoker**: Smoking status (yes/no)
- **Sex**: Gender (male/female)
- **Region**: Geographic region
- **Charges**: Insurance charges (target variable)

## 🔍 Analysis Pipeline

### 1. Exploratory Data Analysis (EDA)
- Dataset overview and statistical summary
- Distribution analysis of insurance charges
- Feature correlation analysis
- Data visualization and insights

### 2. Data Preprocessing
- Categorical variable encoding
- Feature scaling and normalization
- Data cleaning and preparation

### 3. Multicollinearity Analysis
- Correlation matrix visualization
- Feature relationship assessment
- Identification of redundant features

### 4. Model Building & Evaluation
- Multiple linear regression implementation
- Model performance metrics (R², Adjusted R²)
- Statistical significance testing
- Feature importance analysis

### 5. Feature Selection
- Identification of statistically significant features
- Model optimization with top features
- Performance comparison between full and reduced models

## 📈 Key Findings

Based on the analysis, the most significant factors affecting insurance costs are:
- **Age**: Older individuals typically have higher insurance costs
- **BMI**: Body Mass Index significantly impacts charges
- **Smoking Status**: Smokers have substantially higher insurance costs
- **Number of Children**: Family size affects insurance pricing

## 🛠️ Technologies Used

- **Python**: Primary programming language
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical computations
- **Matplotlib/Seaborn**: Data visualization
- **Scikit-learn**: Machine learning algorithms
- **Statsmodels**: Statistical modeling and analysis
- **Jupyter Notebook**: Development environment

## 📁 Project Structure

```
Insurance_cost_prediction/
│
├── insurance_prediction_project.ipynb    # Main analysis notebook
├── data/                                 # Dataset files
├── README.md                            # Project documentation
└── requirements.txt                     # Python dependencies
```

## 🚀 Getting Started

### Prerequisites
- Python 3.7+
- Jupyter Notebook
- Required libraries (see requirements.txt)

### Installation
1. Clone the repository:
```bash
git clone https://github.com/yourusername/Insurance_cost_prediction.git
```

2. Navigate to the project directory:
```bash
cd Insurance_cost_prediction
```

3. Install required dependencies:
```bash
pip install -r requirements.txt
```

4. Launch Jupyter Notebook:
```bash
jupyter notebook
```

5. Open `insurance_prediction_project.ipynb` to explore the analysis

## 📊 Model Performance

The project evaluates model performance using:
- **R-squared (R²)**: Measures the proportion of variance explained
- **Adjusted R-squared**: Accounts for the number of predictors
- **Statistical significance**: P-value analysis for feature importance

## 🎯 Future Enhancements

- Implement additional machine learning algorithms (Random Forest, XGBoost)
- Cross-validation for robust model evaluation
- Hyperparameter tuning for optimal performance
- Feature engineering for improved predictions
- Deployment as a web application

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 📧 Contact

For questions or suggestions, please open an issue or contact [your-email@example.com]

---

*This project demonstrates practical application of machine learning techniques for insurance cost prediction and serves as a comprehensive example of data science workflow from EDA to model deployment.*
