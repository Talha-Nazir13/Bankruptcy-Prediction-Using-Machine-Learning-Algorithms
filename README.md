# Bankruptcy Prediction Using Machine Learning

This project predicts corporate bankruptcy using various machine learning algorithms. It leverages financial data to classify companies as bankrupt or non-bankrupt.

## Project Overview
We used advanced machine learning techniques, including:
- Random Forest
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Neural Networks

## Dataset
The dataset contains financial ratios from 6819 companies, with 220 bankrupt cases. Key financial features include:
- Net Income to Total Assets
- Debt Ratio
- After-tax Net Interest Rate
- Retained Earnings to Total Assets

## How to Run
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/bankruptcy-prediction.git
    ```
2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the Jupyter notebook:
    ```bash
    jupyter notebook Bankruptcy_prediction.ipynb
    ```

## Results
The Random Forest model achieved the best performance with a 0.93 AUC score.

## Future Work
- Incorporating non-financial variables
- Experimenting with more advanced models like XGBoost

## License
This project is licensed under the MIT License.
