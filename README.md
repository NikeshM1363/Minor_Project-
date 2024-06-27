# 📊 Cost of Living Prediction Model Deployment

This repository contains the necessary files for deploying our Cost of Living Prediction Model onto a website. The project utilizes Flask for the backend and includes HTML, CSS, and JavaScript for the frontend.

## 📁 Project Structure

The project directory is organized as follows:

- **🗂 static/**: Contains static files such as CSS and JavaScript.
- **📄 templates/**: Contains HTML templates.
- **📝 app.py**: The main Flask application code.
- **📊 india_subset.xlsx**: Dataset containing the cost of living values for Indian cities from 2010 to 2022.
- **🔍 codes/COL_V2.ipynb**: Jupyter Notebook with the calculation logic and prediction function.

## 📜 Project Description

This project aims to deploy a cost of living prediction model on a website. The current version uses static values where the user inputs the year and city of India, and the model predicts the cost of living using pre-existing data from `india_subset.xlsx`.

### ⚙️ Current Functionality

- The user inputs a year and a city from India.
- The model retrieves the cost of living values for Indian cities from 2010 to 2022.
- Using these values, the model predicts the cost of living through the prediction function defined in `app.py`.

### 🚀 Future Enhancements

Our goal is to make the website dynamic by allowing multiple user inputs and utilizing the calculation logic defined in `COL_V2.ipynb`. The dynamic version will take various inputs, predict the cost of living, and display the results on the website.

## 🛠 Getting Started

### 📋 Prerequisites

- Python 3.x
- Flask
- Pandas
- Jupyter Notebook

### 📦 Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/cost-of-living-prediction.git
   cd cost-of-living-prediction
