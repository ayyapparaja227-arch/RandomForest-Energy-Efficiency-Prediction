# 🏢 Building Energy Efficiency Prediction

Welcome to the **Building Energy Efficiency Prediction** project! This repository contains a sleek, modern Streamlit application that predicts the heating load of a residential building based on its various architectural characteristics using a pre-trained **Random Forest Regression** model.

## 🌟 Features
- **Accurate Predictions**: Leverages a robust Random Forest algorithm to estimate Heating Load accurately.
- **Interactive UI**: Clean, professional, and user-friendly interface built with Streamlit.
- **Real-time Feedback**: Instantly computes predictions upon adjusting inputs, offering quick insights into energy efficiency classes (e.g., High Efficiency, Moderate Efficiency, Low Efficiency).

## 🛠️ Tech Stack
- **Python**: Core programming language.
- **Streamlit**: Web framework for building the interactive ML web app.
- **Scikit-Learn**: Machine learning library used for the Random Forest Regression model.
- **Joblib**: Used for model serialization and loading.
- **Numpy**: For efficient numerical computations.

## 🚀 How to Run Locally

Follow these steps to run the application on your local machine:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/ayyapparaja227-arch/RandomForest-Energy-Efficiency-Prediction.git
   cd RandomForest-Energy-Efficiency-Prediction
   ```

2. **Install the required dependencies:**
   Make sure you have Python installed. Then, run:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Streamlit application:**
   ```bash
   streamlit run app.py
   ```

4. **Access the Application:**
   Open a web browser and navigate to `http://localhost:8501`.

## 📁 Repository Structure
- `app.py`: The main Streamlit application script.
- `energy_rf_model.pkl`: The pre-trained Random Forest Regression model.
- `requirements.txt`: The list of Python dependencies required to run the app.
- `README.md`: This documentation file.

## 🤝 Contributing
Contributions are welcome! If you have any ideas, suggestions, or bug reports, please open an issue or submit a pull request.
