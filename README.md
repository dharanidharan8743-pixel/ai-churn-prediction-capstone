# ai-churn-prediction-capstone
End-to-end AI capstone project: customer churn prediction using gradient-boosted models, SHAP explainability, and a deployable FastAPI service with a lightweight web interface. Includes data pipeline, modeling code, evaluation reports, and Dockerized API for real-world deployment.
This project delivers a complete, production-ready AI system for predicting customer churn in subscription-based businesses. It covers the full lifecycle: data preparation, feature engineering, model training, evaluation, explainability, and deployment.

The solution uses gradient-boosted tree models to estimate churn risk for each customer, supported by SHAP-based explanations that highlight the strongest behavioral and billing factors driving the prediction. The pipeline is built with reproducibility in mind, using a unified preprocessing and modeling workflow.

A FastAPI service exposes the model through REST endpoints for real-time or batch inference, and a lightweight web interface allows non-technical users to upload customer data and view risk scores with explanations. The service is containerized with Docker for easy deployment on any cloud platform.
