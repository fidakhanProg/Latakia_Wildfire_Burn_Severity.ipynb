Latakia Wildfire Burn Severity Prediction

Project Overview

This project evaluates machine learning models for estimating continuous differenced Normalized Burn Ratio (dNBR) within the July 2025 Latakia wildfire boundary.

Dataset

4,963 samples

10 baseline predictors

Target variable: dNBR

Four spatial validation folds

landcover_pre treated as a categorical predictor

Models Evaluated

Random Forest

Extra Trees

XGBoost

Evaluation

Models are evaluated using spatial out-of-fold predictions and the metrics R², RMSE, and MAE.

Deliverables

Runnable analysis notebook

Model configuration and metadata

Spatial validation metrics and predictions

Feature importance and response plots

Fitted Extra Trees pipeline

Limitations

The saved spatial folds have already been examined during model development. Results are exploratory and do not constitute independent final validation. Full-area prediction mapping requires the aligned predictor GeoTIFF files.

Feature importance and response plots represent model-based relationships, not causal effects.
