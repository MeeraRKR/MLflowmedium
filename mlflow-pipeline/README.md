MLflow Demo
==============================

Leveraging MLflow for E2E ML pipeline for a RandomForest Classifier


## References

- II - [MLflow Documentation & Tutorials](https://mlflow.org/docs/latest/tutorials-and-examples/index.html)
- II - [Streamline ML Workflow with MLflow - I](https://medium.com/towards-artificial-intelligence/streamline-ml-workflow-with-mlflow%EF%B8%8F-part-i-60857cd511ed)
- III - [Streamline ML Workflow with MLflow - II](https://medium.com/towards-artificial-intelligence/streamline-ml-workflow-with-mlflow-ii-daa8d50016f7)



## Generic installation and mlflow usage guideline

1. Create virtual environment.
2. Install dependencies using `pip install -r requirements.txt`
3. Test the setup using 'test_environment.py'
4. Load dataset and modify implementing feature engineering.
5. Train the model and save it using `mlflow.sklearn.save_model()`
6. Register the model using `mlflow.sklearn.log_model()`
7. Load the model using `mlflow.sklearn.load_model()`
8. Test the model using `test_model.py`
9. Deploy the model using `mlflow.sklearn.deploy_model()`

## Folder Structure
<!-- - `/.github`: Contains CI/CD workflow file. -->
<!-- - `/.dvc`: Contains configuration files of DVC -->
- `/data`: Stores raw and processed data.
- `/models`: Stores trained models.
- `/log`: Store the logs.
- `/src`: Contains the source code files.
- `/prod`: Production files.
- `/tests`: Testing files.
- `/plots`: Model performance plots like confusion matrix

## Dataset

- Download the dataset from [here](https://www.kaggle.com/datasets/yasserh/wine-quality-dataset).
