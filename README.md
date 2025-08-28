# # Credit Card Fraud Detection

This repository contains a machine learning project to detect fraudulent credit card transactions using various data science techniques. The project utilizes a real-world dataset and applies preprocessing, modeling, and evaluation to predict fraudulent activity.

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

---

## GUI Output

A graphical user interface (GUI) was created in Google Colab to allow users to interactively input transaction details and receive predictions on whether a transaction is fraudulent or legitimate.

<img width="1919" height="918" alt="Screenshot 2025-08-28 215302" src="https://github.com/user-attachments/assets/2c063ca0-918d-459a-bbff-47e12de959dd" />


**Features Used in the GUI:**
- `V4`, `V11`, `V2`: These are encrypted credit card indicators that play a crucial role in deciding if the transaction is fraudulent or legitimate.
- `Amount`: The transaction amount.

Users can enter values for these features and submit the form to receive a prediction. The output section displays whether the transaction is flagged as fraudulent or legitimate.

---

## License

This project is for educational purposes.

## Author

- Harshh1206
- munnss
- devanshKale1025
  
