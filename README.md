# 🌧️ Rain Prediction in Australia

This repository contains the code and resources for a machine learning project that aims to tackle rain prediction in Australia. The project utilizes historical weather data and various machine learning algorithms to forecast whether it will rain in different regions of Australia.

![35913Untitled design](https://github.com/edrisshk1/Rain-Prediction-In-Australia/assets/122979130/00b41e3e-dee9-4301-bc93-8e84bcbec7cc)

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Models](#models)
- [Evaluation](#evaluation)
- [Results](#results)
- [Contributing](#contributing)
- [Acknowledgements](#acknowledgements)
- [License](#license)

## Introduction

Rainfall prediction is of utmost importance for various applications such as agriculture, water resource management, and disaster preparedness. This machine learning project focuses on building predictive models that can forecast rain occurrence in different regions across Australia. By analyzing historical weather patterns, the goal is to create accurate and reliable predictions to help stakeholders make informed decisions.

## Dataset

The original source of the data is the Australian Government's Bureau of Meteorology and the latest data can be gathered from [URL to Dataset Source](http://www.bom.gov.au/climate/dwo/.)

The dataset to be used has extra columns like 'RainToday' and our target is 'RainTomorrow', which was gathered from the Rattle at [URL to Dataset](https://bitbucket.org/kayontoga/rattle/src/master/data/weatherAUS.RData)


## Installation

To run the code in this repository, follow these installation instructions:

1. Clone this repository to your local machine using the following command:

   ```
   git clone thttps://github.com/edrisshk1/Rain-Prediction-In-Australia
   ```
2. Download the Dataset
3. Open Jupyter Notebook:

   ```
   jupyter notebook
   ```
4. Follow the instructions within the notebooks to preprocess the data, train the machine learning models, and make predictions.

## Models

Several machine learning algorithms are employed in this project to predict rain in Australia. The following models are implemented and compared:

- Linear Regression
- K-Nearest Neighbors (KNN)
- Decision Trees
- Logistic Regression
- Support Vector Machine (SVM)
- 
## Evaluation

To evaluate our models, we used :

- Accuracy Score
- Jaccard Index
- F1-Score
- LogLoss
- Mean Absolute Error
- Mean Squared Error
- R2-Score

## Results

The evaluation results and insights are summarized in the notebooks and presented graphically. Additionally, comparison tables and visualizations are provided to showcase the strengths and weaknesses of each model.

## Contributing

Contributions to this project are welcome! If you want to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes and push the branch to your fork.
4. Submit a pull request, detailing the changes you made.

## Acknowledgements

I would like to thank the following organizations for their contributions and the amazing tools provided to accomplish this project :
- Coursera: This platform gave me the idea for the project and provided me with the tools needed for this project.
- Cognitive Class AI: This platform provided me with the workspace and the processing power needed to train and evaluate the models
- The contributors to scikit-learn’s development and maintenance

## License

This project is licensed under the [MIT License](LICENSE).
