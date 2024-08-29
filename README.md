# UFC Fight Prediction

This project was developed to predict the outcomes of UFC (Ultimate Fighting Championship) fights using fight data from [UFC Stats](http://www.ufcstats.com/statistics/events/completed) and a Random Forest Classifier. The model is built using Python and the scikit-learn module.

## Table of Contents

- [Dataset](#dataset)
- [Model Training and Evaluation](#model-training-and-evaluation)
- [Installation](#installation)
- [Usage](#usage)

## Dataset

The dataset used in training the machine learning algorithm contains data on UFC fights, including fight statistics such as Significant Strikes, Submission Attempts, and Takedowns and fight outcomes. Data processing involves handling missing values and standardizing data for analysis. Additionally, some new features like fighters' win/loss ratios and average fight duration are added.

## Model Training and Evaluation

The dataset is split into training and testing sets. A Random Forest Classifier from the scikit-learn library is trained on the data.

## Installation

To run this project, clone the repository and install the required dependencies:

\`\`\`bash
git clone https://github.com/b-temirov/UFC-fight-prediction.git
cd UFC-fight-prediction
pip install -r requirements.txt
\`\`\`

## Usage

To use the prediction system, ensure the dataset is available and run the Jupyter notebook or the Python script:

\`\`\`bash
jupyter notebook ufc_fight_prediction.ipynb
\`\`\`
# UFC-fight-prediction
# UFC-fight-prediction
