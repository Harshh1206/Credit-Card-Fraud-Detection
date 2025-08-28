# Credit Card Fraud Detection

This repository contains a machine learning project to detect fraudulent credit card transactions using various data science techniques. The project utilizes a real-world dataset and applies preprocessing, balancing, and classification to identify fraudulent cases.

## Dataset

- Features: 30 anonymized features (`V1` to `V28`, `Time`, `Amount`) and a target column `Class` (0 = legitimate, 1 = fraud)

## Project Structure

- `CreditCardFraud.ipynb`: Main Jupyter notebook with full code and workflow.
- `README.md`: Project overview and instructions.
- `Report.md`: Detailed report of methodology and results.
- `CreditCardFraudDetection.pptx`: Presentation outline for sharing findings.

## Requirements

- Python 3.x
- Libraries: numpy, pandas, scikit-learn, imbalanced-learn, matplotlib

Install dependencies:
```bash
pip install numpy pandas scikit-learn imbalanced-learn matplotlib
```

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Harshh1206/Credit-Card-Fraud-Detection.git
   cd Credit-Card-Fraud-Detection
   ```

2. Open `CreditCardFraud.ipynb` in Jupyter or Google Colab.

3. Ensure the dataset (`IBM_Credit_Card_Transactions.csv`) is in the correct path.

4. Run the notebook cells sequentially.

## Workflow Summary

- Data Loading and Exploration
- Preprocessing (handling missing data, scaling)
- Balancing with SMOTE
- Model Training (Logistic Regression)
- Evaluation (accuracy, confusion matrix)

## Results

The model demonstrates effective fraud detection using logistic regression after balancing the dataset.

## License

This project is for educational purposes.

## Author

- Harshh1206
- munnss
- devanshKale1025
