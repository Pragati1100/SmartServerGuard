# SmartServerGuard 🚨  
AI-Driven Server Monitoring & Failure Prediction System

## 🧠 Overview
SmartServerGuard is an AI-powered system that predicts server failures and detects anomalies by monitoring real-time system metrics. It uses ML models (like KNN and CatBoost) trained on system health data to enable **proactive maintenance** and **downtime prevention**.

## 🔍 Key Features
- Real-time server health monitoring
- Predictive alerts based on machine learning
- Modular Flask-based architecture
- Interactive web dashboard (under `app/`)
- Easy integration and extendability

## 🧱 Project Structure
SmartserverGuard.zip is the Main code Folder.

SmartServerGuard/
├── app/ # Flask application
│ ├── client/ # Client-side interface (dashboard)
│ ├── routes/ # Route definitions (Flask)
│ ├── static/ # CSS/JS files
│ ├── templates/ # HTML templates
│ ├── utils/ # Utility modules (metrics, model, etc.)
│ └── init.py # Flask app factory
│
├── catboost_info/ # CatBoost model info/logs
├── Dataset/ # Raw and processed datasets
├── model/ # Trained ML models
├── monitoring_data/ # System logs and metric snapshots
│
├── dataset.csv # Combined dataset
├── real_time_prediction.py # Live inference script
├── run.py # Main entry point to start app
├── new.py # Experiment script (if applicable)

📺 [Watch Demo Video]
This file  is named as 📊 Device Dashboard - Google Chrome 2025-07-24 16-58-52 / It is is zip file.
