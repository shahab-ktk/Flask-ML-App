<h2>🚀 Flask ML Web App – Fire Weather Index (FWI) Prediction System</h2>
<br>
A Machine Learning-powered web application built with Flask that predicts the Fire Weather Index (FWI) using environmental and forest-related features from the Algerian Forest Fires dataset.
<br>

 <h3>📌Overview</h3>

This project demonstrates the end-to-end deployment of a trained ML model using Flask.<br>
Users can input meteorological and fire-related parameters through a simple web interface and receive real-time predictions for fire risk (FWI-based model output).
<br><br>
 <h3>🎯 Features </h3>

🔹 Simple and clean web interface<br>
⚡ Real-time prediction system<br>
🧠 ML model integration (trained on real dataset)<br>
🌐 Flask-based backend API<br>
📊 Supports environmental feature inputs<br>
📦 Lightweight and easy to deploy
<br><br>
 <h3>🧠 Machine Learning Model </h3>

📌 Problem Type: Regression (FWI Prediction)<br>
📊 Dataset: Algerian Forest Fires Dataset<br>
⚙️ Algorithm: Ridge Regression (or trained regression model)<br>
🔧 Preprocessing: StandardScaler normalization<br>
📚 Library: Scikit-learn
<br><br>
 <h3>📥 Input Features Used  </h3>

🔹 Temperature (°C)<br>
🔹 Relative Humidity (%)<br>
🔹 Wind Speed (km/h)<br>
🔹 Rain (mm)<br>
🔹 FFMC (Fine Fuel Moisture Code)<br>
🔹 DMC (Duff Moisture Code)<br>
🔹 ISI (Initial Spread Index)<br>
🔹 Classes (Encoded: 0 = Not Fire, 1 = Fire)<br>
🔹 Region (Encoded: 0 = Bejaia, 1 = Sidi-Bel Abbes)
<br><br>
 <h3>🛠️ Tech Stack </h3>
🐍 Python<br>
🌐 Flask<br>
🤖 Scikit-learn<br>
🎨 HTML / CSS<br>
📦 Pickle (Model Serialization)<br>

## 📁 Project Structure

```
TESTED_MODEL/
│
├── application.py              # Main Flask application
├── README.md                   # Project documentation
├── requirements.txt            # Dependencies
│
├── models/                     # Saved ML models
│   ├── ridge.pkl
│   └── Scalar.pkl
│
├── notebook/                   # Model training notebook
│   └── Model_Train_on_Algerian_forest_dataset.ipynb
│
├── templates/                  # HTML templates for Flask
│   ├── home.html
│   └── index.html
```
