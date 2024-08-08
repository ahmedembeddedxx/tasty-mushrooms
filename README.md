# Tasty Mushrooms 🍄

This repository contains a machine learning project aimed at classifying mushroom species as either edible or poisonous based on various features. The project uses multiple classification algorithms, including K-Nearest Neighbors (KNN), Deep Neural Networks (DNN), and other standard classifiers to achieve this task.

## Project Overview

The notebook in this repository walks through the entire process of data exploration, preprocessing, model selection, training, and evaluation. The data used for this project is sourced from Kaggle, containing a variety of features that describe different mushroom species.

### Models Used
- **K-Nearest Neighbors (KNN):** A simple, yet effective instance-based learning algorithm.
- **Deep Neural Network (DNN):** A more complex model that leverages deep learning for classification.
- **Other Classification Algorithms:** Various other classification techniques have been implemented and compared, including Logistic Regression, Decision Trees, Random Forests, and Support Vector Machines (SVM).

### Notebook
The Jupyter Notebook (`tasty_mushrooms.ipynb`) provides a step-by-step guide, including:
- Data loading and exploration
- Data preprocessing and feature engineering
- Model implementation and training
- Model evaluation and comparison
- Results interpretation

## Data

The dataset used in this project is from Kaggle and includes features such as cap shape, cap color, gill color, and others, which help in distinguishing between edible and poisonous mushrooms.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/ahmedembeddedxx/tasty-mushrooms.git
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the notebook and run the cells:
   ```bash
   jupyter notebook tasty_mushrooms.ipynb
   ```

## Results

The project compares the performance of various classification algorithms, providing insights into which model best classifies the mushroom species based on the available features.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
