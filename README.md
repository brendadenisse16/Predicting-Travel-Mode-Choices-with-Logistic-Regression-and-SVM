# Travel Mode Prediction using Machine Learning

## Overview
This project implements machine learning models to predict travel mode choices based on individual preferences and behaviors. The models include:
1. **Multinomial Logistic Regression**
2. **Multiclass Classification with Support Vector Machines (SVM)**

The dataset comes from the **Netherlands Mobility Panel (MPN)**, a comprehensive survey on daily travel behavior. This project aims to predict the preferred travel mode (e.g., car, bike, public transport) based on personal and household characteristics, including workplace and home locations.

This research is valuable for transportation planning, understanding travel behaviors, and optimizing new transportation projects.

## Key Features
- **Custom Implementations**: Models were developed and tuned using Python with Scikit-learn.
- **Dataset**: Contains 7,310 observations from 676 individuals, providing detailed information on their daily trips.
- **Performance Metrics**: Evaluated models using accuracy, precision, and recall for classification performance.

## Project Structure
- `/code/environment.yml`: Conda environment setup for the project.
- `/code/util.py`: Utility functions for data manipulation and preprocessing.
- `/code/preprocessing.py`: Functions for cleaning and preprocessing the dataset.
- `/code/training.py`: Functions for training the machine learning models.
- `/data/mobility_dataset.csv`: The dataset used for training and testing.
- `/data/catalogue.csv`: A file containing detailed variable descriptions.

## Installation and Usage
To run the project, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/brendadenisse16/MachineLearning.git
2. **Set up the environment**:
   Create a conda environment using the environment.yml file:
   ```bash
   conda env create -f code/environment.yml
   conda activate travel_mode_prediction

3. **Run the project**:
    The main file to execute is **G03-Project.ipynb**, which will call all data preprocessing, training, and evaluation steps.

