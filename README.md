# 🛡️ Privacy-Preserving Cryptocurrency Fraud Detection using Federated Learning

A final-year major machine learning project using **Federated Learning (FL)** to build a fraud detection model without centralizing user data.

---

## Project Summary

- **Dataset**: DEX transaction data from Kaggle
- **Objective**: Predict fraudulent transactions while preserving data privacy
- **Approach**:
  - 5 clients simulate decentralized data sources
  - Flower FL framework with Logistic Regression
  - Visualizations and centralized model comparison
- **Tools Used**: Python, Flower, scikit-learn, Matplotlib, Seaborn, Plotly, Ray

---

##  How to Run


# Install dependencies
pip install -U "flwr[simulation]==1.4.0" ray==2.9.3 scikit-learn seaborn plotly pandas
Run the notebook in Google Colab or locally with Python 3.10+.

 Files
main.ipynb: Full Jupyter notebook with FL pipeline

central_model.pkl: Trained centralized model (Logistic Regression)

requirements.txt: All Python dependencies

README.md: Project documentation

Results
FL Accuracy: Averaged over 5 clients

Centralized Accuracy: ~97%

Visualization: Included for fraud rate, client distribution, correlation

Key Learnings
Hands-on experience with FL concepts

Importance of privacy-preserving AI

Integration of data visualization with ML

Future Work
Try deep learning models with PyTorch

Integrate real-time fraud alerts

Use real-time APIs or blockchain simulators

👩‍💻 Author
Harsha Jain
LinkedIn : https://www.linkedin.com/in/harsha-jain-b1859b287
GitHub : https://github.com/harshajain6114/
