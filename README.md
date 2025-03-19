# Heart Condition Prediction ❤️🩺

## 📌 Project Overview

This project focuses on predicting heart conditions using machine learning. It aims to assist healthcare professionals by providing insights into potential heart diseases based on patient data. The model leverages historical medical records to make accurate predictions.

## 📊 Data Source

The dataset consists of various patient health attributes, including:

- **Age & Gender** 👥
- **Blood Pressure** 💉
- **Cholesterol Levels** 🩸
- **Heart Rate** ❤️
- **ECG Results** 📈
- **Other relevant health metrics**

## 🛠️ Tech Stack

- **Python** – Primary programming language
- **Scikit-Learn & TensorFlow** – Machine learning frameworks
- **Pandas & NumPy** – Data processing
- **Matplotlib & Seaborn** – Data visualization
- **MLflow** – Model tracking and experiment logging
- **Streamlit** – Deployment for an interactive user interface

## ⚙️ Architecture

The workflow follows these key steps:

1. **Data Collection**: Collect and preprocess patient health records.
2. **Feature Engineering**: Extract relevant features for model training.
3. **Model Training**: Train various machine learning models and fine-tune hyperparameters.
4. **Model Evaluation**: Evaluate model performance using metrics like accuracy, precision, recall, and F1-score.
5. **Model Deployment**: Deploy the best model using Streamlit for user interaction.
6. **Monitoring**: Continuously track model performance and data drift.

## 📥 Installation & Setup

### 📍 Prerequisites

Ensure you have the following installed:

- **Python 3.x**
- **Jupyter Notebook (optional)**
- **Scikit-Learn, TensorFlow, Pandas, Matplotlib** (install using `requirements.txt`)
- **Streamlit** (for deployment)

### 📥 Installation Steps

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/tejaskolpek/Heart_Condition_Prediction.git
   cd Heart_Condition_Prediction
   ```
2. **Create a Virtual Environment**:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```
3. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```
4. **Run the Streamlit App**:
   ```bash
   streamlit run app.py
   ```

## 📈 Model Performance & Monitoring

- Model performance is evaluated using **accuracy, precision, recall, and F1-score**.
- **MLflow** logs experiments and model versions.
- Predictions are stored and analyzed for data drift detection.

## 🚀 Application Deployment

You can access the deployed application at:

- 🌍 **[Streamlit App](https://your-deployment-link.streamlit.app/)**

## 🤝 Contribution

Contributions are welcome! Feel free to open **pull requests** or **raise issues** for improvements.

## 📝 License

This project is licensed under the **MIT License**.

---

🚀 **Empowering Healthcare with AI!** ❤️
