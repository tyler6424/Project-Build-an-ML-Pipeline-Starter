# NYC Airbnb Price Prediction Pipeline

This ML pipeline predicts Airbnb listing prices in NYC using a Random Forest model. It includes automated data ingestion, cleaning, validation, model training, and evaluation — all tracked and orchestrated using MLflow and Weights & Biases (W&B).

## Tools Used
- Python, scikit-learn
- MLflow for orchestration
- W&B for experiment tracking
- Hydra for configuration

## Key Features
- Automated ETL pipeline with dynamic config
- Outlier and geolocation filtering
- Data validation with pytest
- Stratified train/val/test split
- Hyperparameter sweeps
- Versioned model training and deployment

## Final Model Performance
- MAE: 32.42
- R²: 0.58

## Links
- [GitHub Repository](https://github.com/tyler6424/Project-Build-an-ML-Pipeline-Starter)
- [W&B Project](https://wandb.ai/zhende5-western-governors-university/nyc_airbnb)