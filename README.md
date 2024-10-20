# Network Security ML Project

## Overview
This project aims to develop a machine learning pipeline for detecting phishing attacks using network data. The pipeline includes data ingestion, validation, transformation, model training, and deployment. The project leverages various machine learning algorithms and tools to ensure robust and accurate phishing detection.

1. Data Ingestion
  File: data_ingestion.py 
  Description: Handles the ingestion of raw data from various sources into the pipeline.
2. Data Validation
  File: data_validation.py
  Description: Validates the ingested data against predefined schemas to ensure data quality.
3. Data Transformation
  File: data_transformation.py
  Description: Transforms the validated data into a format suitable for model training.
4. Model Training
  File: model_trainer.py
  Description: Trains machine learning models using the transformed data.
5. Pipeline Orchestration
  File: training_pipeline.py
  Description: Orchestrates the entire training pipeline, from data ingestion to model training.
6. Utility Functions
  File: utils.py
  Description: Contains utility functions for file operations, model evaluation, and more.
7. API
  File: app.py
  Description: Provides an API for training the model and making predictions.
8. Docker
  File: Dockerfile
  Description: Dockerfile for containerizing the application.
9. CI/CD
  File: main.yml
  Description: GitHub Actions workflow for continuous integration and deployment.

## Main Technologies Used

  Python: The primary programming language used for developing the pipeline.
  
  Scikit-learn: Used for machine learning algorithms and model evaluation.
  
  Pandas & NumPy: Used for data manipulation and numerical operations.
  
  FastAPI: Used for building the API.
  
  Docker: Used for containerizing the application. Images are pushed to Amazon ECR
  
  GitHub Actions: Used for CI/CD.
  
  AWS S3: Used for storing artifacts and models.
  
  Mlflow: Used for tracking experiments and model management.
  
  Dagshub: Used for versioning data and models.



  
