# Brain Stroke Prediction with Ensemble Techniques

This project aims to predict stroke occurrence using various ensemble techniques in machine learning. The dataset includes several medical and lifestyle factors influencing stroke risk, such as age, gender, hypertension, heart disease, glucose levels, and BMI. The project explores data preprocessing, feature analysis, and model training with ensemble methods to improve predictive accuracy.

## Dataset

The dataset used in this notebook is `brain_stroke.csv`, containing medical records with the following features:
- **gender**: Gender of the patient
- **age**: Age of the patient
- **hypertension**: History of hypertension
- **heart_disease**: History of heart disease
- **ever_married**: Marital status
- **work_type**: Type of work
- **Residence_type**: Living area (Urban/Rural)
- **avg_glucose_level**: Average glucose level
- **bmi**: Body Mass Index
- **smoking_status**: Smoking history
- **stroke**: Stroke occurrence (target variable)

## Project Structure

1. **Data Exploration**: Initial exploration of dataset statistics and feature distributions.
2. **Preprocessing**: Handling missing values, encoding categorical variables, and normalizing numerical features.
3. **Modeling**: Training ensemble models such as Random Forest, Gradient Boosting, and Voting Classifiers.
4. **Evaluation**: Assessing model performance using metrics like accuracy, precision, recall, and F1-score.

## Installation

To run the notebook, you need Python 3.x with the following libraries:
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

Install the dependencies using:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/brain-stroke-ensemble.git
   ```
2. Run the notebook:
   ```bash
   jupyter notebook AIM0204D2203_EnsembleTechnique_A.ipynb
   ```

## Results

The notebook demonstrates feature importance and compares the performance of various ensemble models. The model with the best performance can be used as a reference for future research or practical applications in stroke prediction.
