# Breast Cancer Classification with Logistic Regression

This project demonstrates binary classification using logistic regression on the Breast Cancer Wisconsin Dataset.

## Project Structure
- `task.ipynb`: Jupyter notebook containing the complete solution
- `data.csv`: Dataset used for the analysis
- `.gitignore`: Standard Python gitignore file

## Key Steps
1. Data preprocessing and exploration
2. Feature standardization
3. Train-test split
4. Logistic regression model training
5. Model evaluation using:
   - Confusion matrix
   - Classification report
   - Precision, recall, ROC-AUC
   - ROC curve and Precision-Recall curve
6. Threshold tuning demonstration
7. Sigmoid function visualization

## Key Concepts
1. **Logistic Regression**: A classification algorithm that uses the sigmoid function to output probabilities
2. **Sigmoid Function**: S-shaped curve that maps any real-valued number to a value between 0 and 1
3. **Evaluation Metrics**:
   - Precision: Ratio of true positives to all predicted positives
   - Recall: Ratio of true positives to all actual positives
   - ROC-AUC: Area under the Receiver Operating Characteristic curve
4. **Threshold Tuning**: Adjusting the decision threshold to optimize for precision or recall

## How to Run
1. Clone the repository
2. Install required packages: `pip install numpy pandas matplotlib scikit-learn`
3. Open and run `task.ipynb` in Jupyter Notebook
