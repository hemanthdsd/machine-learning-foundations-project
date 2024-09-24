
# Machine Learning Foundations Project

### IS41070 Machine Learning Foundations

This project is part of the **IS41070 Machine Learning Foundations** course. It involves using machine learning techniques for data understanding, exploration, and model development. The project includes data analysis, visualization, and model implementation.

## Project Overview

The project includes the following key components:
- **Data Understanding**: Exploratory Data Analysis (EDA) using visualizations to understand the dataset.
- **Machine Learning Models**: A logistic regression model is trained and improved to predict outcomes.
- **NLP and Text Processing**: Natural Language Processing is applied to analyze and visualize text data.

### Key Objectives:
- **Data Preparation**: Train, validation, and test datasets are provided (`train.csv`, `valid.csv`, `test.csv`).
- **Model Development**: The project builds a logistic regression model and saves the improved version as a `.pkl` file for further use.
- **Text and Data Visualization**: Various data and text visualizations, including word clouds and other graphical analysis.

## Project Files

- **`23202425_Machine_learning_foundations_project.ipynb`**: The main Jupyter notebook containing all code and analysis.
- **`logreg_improved_model.pkl`**: The saved improved logistic regression model for further use or inference.
- **`train.csv`**: The training dataset.
- **`valid.csv`**: The validation dataset.
- **`test.csv`**: The test dataset.
- **`requirement.txt`**: A text file listing all necessary packages for running this project.
- **`23202425_Machine_learning_foundations_project.html`**: An HTML export of the project notebook.
  


### Key Libraries:
- **pandas**: For data manipulation and analysis.
- **numpy**: For numerical operations.
- **matplotlib** & **seaborn**: For data visualization.
- **nltk**: For natural language processing tasks.
- **wordcloud**: For generating word clouds.
- **scikit-learn**: For machine learning algorithms and tools.

## How to Use

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/machine-learning-foundations-project.git
   ```
2. **Install Dependencies**:
   Install all required packages by running:
   ```bash
   pip install -r requirement.txt
   ```
3. **Run the Notebook**:
   Open and run the Jupyter notebook:
   ```bash
   jupyter notebook 23202425_Machine_learning_foundations_project.ipynb
   ```

4. **Model Usage**:
   - The improved logistic regression model is saved in the file `logreg_improved_model.pkl`. You can load and use this model for predictions:
     ```python
     import pickle
     with open('logreg_improved_model.pkl', 'rb') as file:
         model = pickle.load(file)
     ```

## Data

- The project works with three CSV files:
  - **`train.csv`**: The training dataset.
  - **`valid.csv`**: The validation dataset.
  - **`test.csv`**: The test dataset for model evaluation.

## Visualizations

The project provides various visualizations, including:
- **Word Clouds**: Visualizing word frequency from text data.
- **Data Exploration**: Graphs and charts for better understanding the dataset.

## Conclusion

This project demonstrates how to use machine learning techniques, including logistic regression and text analysis, for data-driven insights and predictions.

## Author

- **Name**: Sai Durga Hemanth Davuloori
- **Course**: IS41070 Machine Learning Foundations

