# Sleep Health and Lifestyle Analysis

## Overview
This project explores a synthetic dataset of sleep health and lifestyle factors for close to 400 fictive individuals. It aims to analyze and predict the likelihood of sleep disorders based on various factors such as sleep duration, quality, physical activity, stress, BMI, blood pressure, and heart rate. The project includes data visualization, statistical analysis, and machine learning models to develop insights and solutions.

## Dataset
The dataset contains the following columns:

- `Person ID`
- `Gender`
- `Age`
- `Occupation`
- `Sleep Duration`: Average number of hours of sleep per day
- `Quality of Sleep`: A subjective rating on a 1-10 scale
- `Physical Activity Level`: Average number of minutes the person engages in physical activity daily
- `Stress Level`: A subjective rating on a 1-10 scale
- `BMI Category`
- `Blood Pressure`: Indicated as systolic pressure over diastolic pressure
- `Heart Rate`: In beats per minute
- `Daily Steps`
- `Sleep Disorder`: One of `None`, `Insomnia` or `Sleep Apnea`

## Objectives
### Data Exploration and Analysis:
1. **Identify factors contributing to sleep disorders.**
   - Understand how metrics like stress levels, BMI, and physical activity influence the presence of sleep disorders.
2. **Analyze the impact of physical activity on sleep quality.**
   - Determine if higher activity levels improve sleep quality ratings.
3. **Study the effect of sleep disorders on subjective sleep quality.**
   - Compare sleep quality ratings for individuals with and without sleep disorders.

### Visualization:
- **Boxplot**: Distribution of sleep duration and quality across different occupations.
- **Scatterplot**: Relationship between age and sleep duration, segmented by sleep disorder status.

### Predictive Modeling:
- **Objective**: Build a classifier to predict the presence of a sleep disorder based on other factors.
- **Use Case**: Health insurance companies can use this model to assess client health risks and adjust premiums accordingly.

## Tools and Techniques
### Data Processing:
- **Libraries**: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- **Techniques**: Data cleaning, handling missing values, and feature engineering.

### Visualization:
- Graphs and plots to uncover trends and relationships between variables.

### Machine Learning:
- Supervised learning techniques to classify sleep disorders.
- Models used:
  - Logistic Regression
  - Random Forest
  - Support Vector Machines
- Model evaluation through metrics like accuracy, precision, recall, and F1-score.

## Key Findings
1. Insights into lifestyle factors (e.g., stress and physical activity) that contribute to sleep disorders.
2. Relationships between demographic information (e.g., age and occupation) and sleep health metrics.
3. Predictive capabilities to identify individuals at risk for sleep disorders.

## Conclusion
This project demonstrates the importance of lifestyle factors in sleep health and showcases how machine learning can be applied to health risk assessment. The insights generated can be used for health policy development and personalized recommendations.

---

### Folder Structure
```
project/
│
├── data/
│   ├── data.csv  # Dataset file
│
├── notebooks/
│   ├── exploration.ipynb  # Data exploration and visualization
│   ├── modeling.ipynb     # Machine learning models
│
├── outputs/
│   ├── visualizations/    # Saved plots and charts
│   ├── models/            # Trained models
│
├── README.md              # Project overview (this file)
│
├── requirements.txt       # List of dependencies
│
└── scripts/
    ├── preprocess.py      # Data preprocessing pipeline
    ├── train_model.py     # Model training script
```

### How to Run
1. Clone the repository.
2. Install dependencies using `pip install -r requirements.txt`.
3. Open and run the notebooks in the `notebooks` folder or execute scripts for preprocessing and modeling.
4. Explore outputs and visualizations in the `outputs` folder.

---

### Future Work
- Incorporate additional data sources (e.g., dietary information) for deeper insights.
- Enhance the classifier with advanced techniques like deep learning.
- Develop a real-time prediction tool with a web interface.

For any inquiries or suggestions, feel free to contribute or reach out!
