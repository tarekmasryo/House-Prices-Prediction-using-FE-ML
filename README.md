# 🏡 House Prices Prediction --- A Data Story

> *Behind every house sold is a story --- of age, quality, size, and
> even the porch where someone once had coffee every morning.*

In this notebook, we uncover the **hidden drivers of housing prices**
and build machine learning models that can **predict the future of real
estate**.

------------------------------------------------------------------------

## 🚀 Project Highlights

-   **Data Cleaning:** Handle missing values, duplicates, and outliers
    (giant houses sold cheap).\
-   **EDA:**
    -   Histograms, scatterplots, and boxplots to reveal patterns.\
    -   Neighborhood analysis: which areas are most expensive?\
    -   Correlation heatmaps & pairplots --- the "social map" of
        features.\
-   **Feature Engineering:**
    -   Age, remodeling, total space, bathroom ratios.\
    -   Flags (HasGarage, HasFireplace, HasPool).\
    -   Interaction features (Qual × Age, Lot ratios).\
-   **Modeling Arena:**
    -   Ridge (linear monk), Random Forest (explorer), XGBoost
        (champion), CatBoost (stealth newcomer).\
    -   10-Fold CV leaderboard with RMSLE metric.\
-   **Feature Importances:** Top 20 drivers behind SalePrice.\
-   **Error Analysis:** Residual plots, distributions, and breakdown by
    neighborhoods/quality.

------------------------------------------------------------------------

## 🏆 Results

-   **CatBoost** emerged as the champion with the lowest RMSLE.\
-   Errors are smallest in mid-range houses, higher in very cheap or
    luxury homes.\
-   Features like **Overall Quality, Living Area, Bathrooms, and
    Neighborhood** dominate price prediction.

------------------------------------------------------------------------

## 📂 Outputs

-   `submission.csv` --- Final Kaggle submission file.\
-   Rich visualizations (heatmaps, boxplots, residual plots).\
-   End-to-end pipeline: preprocessing → modeling → evaluation →
    submission.

------------------------------------------------------------------------

## ✨ Takeaway

This journey was more than predicting prices ---\
it was about **discovering how space, quality, and time shape the value
of a home**.
