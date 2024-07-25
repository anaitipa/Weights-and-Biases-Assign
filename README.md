# URL Phishing Detection

This project aims to classify URLs as phishing or non-phishing using Decision Tree and Logistic Regression models.

## Project Structure
- `data/`: Contains the dataset.
- `models/`: Contains model training scripts.
- `results/`: Contains results and logs.
- `README.md`: Project documentation.

## Dataset
The dataset (`urlset.csv`) contains URLs with features indicating whether they are phishing or not.

## Getting Started
1. Clone the repository:
    ```bash
    git clone <your-repo-url>
    cd <your-repo-name>
    ```
2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the Decision Tree model:
    ```bash
    python models/decision_tree.py
    ```
4. Run the Logistic Regression model:
    ```bash
    python models/logistic_regression.py
    ```

## Results
The results of the models are logged using [Weights and Biases](https://wandb.ai/site).

## Conclusion
The project demonstrates the use of Decision Tree and Logistic Regression models to detect phishing URLs. The results are tracked and visualized using WandB.
