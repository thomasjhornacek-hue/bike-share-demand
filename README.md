# Bike Share Demand Prediction on AWS SageMaker

An end-to-end cloud machine learning pipeline that predicts bike share demand, taking data from storage through training, tuning, and model deployment. Built as the applied project for the Johns Hopkins AI on Cloud certificate.

## Overview

This project demonstrates the full cloud ML lifecycle on AWS SageMaker: reading data from S3, training a model, tuning it, and deploying it to a live endpoint for inference. The use case is predicting bike share demand from historical and seasonal features.

## Approach

1. Data stored and read from Amazon S3
2. Model training in SageMaker using XGBoost
3. Hyperparameter tuning
4. Deployment to a SageMaker endpoint for inference

## Tools

AWS SageMaker, XGBoost, Amazon S3, cloud ML workflows, model deployment.

## Notes

Completed as coursework for the Johns Hopkins AI on Cloud certificate. This is a learning project that demonstrates the SageMaker train-tune-deploy workflow on a course-provided dataset.
