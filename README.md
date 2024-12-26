# CredSecure: Real-Time Credit Card Fraud Detection

[![Deployed on Render](https://img.shields.io/badge/Deployed%20on-Render-purple)](https://credit-card-fraud-detection-application.onrender.com/)

## 🎯 Overview

CredSecure is a robust credit card fraud detection system powered by Random Forest machine learning. Built with Flask and Python, it provides real-time transaction monitoring with industry-leading accuracy and recall rates.

🔗 **[Try the Live Demo](https://credit-card-fraud-detection-application.onrender.com/)**

## 🤖 Model Performance Analysis

Our comprehensive model evaluation revealed Random Forest as the optimal choice for fraud detection:

| Model | Key Strengths | Limitations |
|-------|--------------|-------------|
| **Random Forest** ✨ | - Superior accuracy & recall<br>- Excellent with imbalanced data<br>- Robust performance | - Slightly higher computational needs |
| XGBoost | - High accuracy<br>- Fast predictions | - Prone to overfitting<br>- Lower recall on fraud cases |
| Decision Tree | - Highly interpretable<br>- Simple implementation | - Overfitting issues<br>- Poor generalization |
| Logistic Regression | - Fast training<br>- Low complexity | - Misses complex patterns<br>- Lower accuracy |

## ✨ Key Features

- 🚀 Real-time transaction monitoring
- 📊 High-precision fraud detection
- 🎯 Optimized for imbalanced datasets
- 💻 Clean, intuitive web interface
- ⚡ Production-ready architecture

## 🛠️ Technology Stack

- **Backend**: Python, Flask
- **ML Model**: Random Forest
- **Deployment**: Render
- **Data Processing**: NumPy, Pandas
- **ML Libraries**: Scikit-learn

## 🚀 Getting Started

### Local Development

1. **Clone the Repository**
   ```bash
   git clone https://github.com/Susanta2102/Credit-Card-Fraud-Detection-Application-
   cd CredSecure
   ```

2. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Launch the Application**
   ```bash
   python app.py
   ```

4. **Access the App**
   - Open your browser and navigate to `http://127.0.0.1:5000/`

### Production Deployment

The application is live on Render! Access it here:
https://credit-card-fraud-detection-application.onrender.com/

## 📫 Contact & Support

For questions, feature requests, or bug reports, please open an issue in the GitHub repository.

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.
