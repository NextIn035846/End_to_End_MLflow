# Wine Quality Prediction with ElasticNet and MLflow
This project aims to predict the quality of wine using the ElasticNet regression algorithm. Additionally, MLflow is utilized for tracking various aspects of the machine learning process, including parameters, metrics, code versions, and artifacts.

## Requirements
To run this project, you need the following dependencies:

Python 3.x
pandas
scikit-learn
mlflow

# You can install the dependencies via pip:

```bash
pip install pandas scikit-learn mlflow
```
Project Structure
data/: Directory to store the dataset.
models/: Directory to save trained models.
src/: Source code directory.
main.py: Python script for training the ElasticNet model and logging metrics with MLflow.

## Usage
**Clone the repository:**
```bash

git clone https://github.com/NextIn035846/End_to_End_MLflow
```
Navigate to the project directory:
```bash
cd End_to_End_MLflow
```
Download the Wine Quality dataset from the provided link and save it to the data/ directory.

Run the training script:

```bash
python app.py
```
View MLflow UI to track the experiment:
```bash
mlflow ui
```
Open a web browser and go to http://localhost:5000 to access the MLflow UI.

MLflow Tracking
MLflow Tracking is used to log the following:

Parameters: Hyperparameters such as alpha and l1_ratio for ElasticNet.
Metrics: Evaluation metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared.
Artifacts: Trained models saved in the models/ directory.
## Conclusion
This project demonstrates how to build a machine learning model using the ElasticNet algorithm to predict wine quality. MLflow is employed to track the experimentation process, making it easier to manage, reproduce, and compare different runs.
