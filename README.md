## 🏠 House Price Prediction Project
## 📌 Project Overview
This project walks through a machine learning pipeline for predicting housing prices. We'll cover:
- Data collection and exploration
- Feature engineering
- Model training (regression)
- Evaluation and tuning
- (Optional) Deployment
---

### 📊 Tools & Technologies

![Python](https://img.shields.io/badge/Python-FFD43B?style=flat&logo=python&logoColor=blue)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626.svg?&style=flat&logo=Jupyter&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3776AB?style=flat&logo=python&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-9BAFC6?style=flat&logo=python&logoColor=white)
![BeautifulSoup](https://img.shields.io/badge/BeautifulSoup-ffffff?style=flat&logo=python&logoColor=black)
![WebScraping](https://img.shields.io/badge/Web%20Scraping-6A5ACD?style=flat&logo=python&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-1D8348?style=flat&logo=lightgbm&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![ComputerVision](https://img.shields.io/badge/Computer%20Vision-4682B4?style=flat&logo=opencv&logoColor=white)
![NLP](https://img.shields.io/badge/Resnet18-8A2BE2?style=flat&logo=spacy&logoColor=white)

---

### 📁 Project Structure

```
├── data/                   # Raw and cleaned data files
├── notebooks/              # Jupyter notebooks for EDA and modeling
├── src/                    # Source code for preprocessing and training
│   ├── preprocess.py
│   └── model.py
├── requirements.txt        # List of dependencies
├── README.md               # Project overview
└── house_price_predictor.py # Main executable script
```

---

### 🔍 Features Used
- Square footage
- Number of bedrooms and bathrooms
- Year built
- Location (zipcode, neighborhood)
- House condition and grade

---

### 📈 Model
- Preprocessing: StandardScaler, OneHotEncoding
- Model: Linear Regression / Random Forest / XGBoost
- Evaluation Metrics: RMSE, MAE, R²

---

### 🚀 Results
Achieved an R² score of **0.88** with XGBoost after hyperparameter tuning. 

---

### ✅ Future Improvements
- Add geospatial analysis
- Use advanced regression techniques
- Deploy the model with a web interface

---

### 📬 Contact
Feel free to reach out if you have questions or suggestions!

---

> ⭐ *Don't forget to star this repository if you find it helpful!*


# House Rent Price Prediction with Image Classification

This project aims to predict house rent prices using a combination of traditional features scraped from real estate listings and image classification models. Leveraging data from bina.az, a leading real estate platform, we've developed a comprehensive solution that incorporates both numerical features and visual data to improve the accuracy of rent price predictions.

# Key Components:
## Traditional Feature Extraction: 
We scraped various features from bina.az, including location, number of rooms, square footage, amenities, and more, to build a robust dataset for training our predictive models.

## Image Classification with ResNet18:
We employed state-of-the-art deep learning techniques, utilizing the ResNet18 architecture, to classify house images. We trained two image classification models:

## Binary Model:
This model determines whether a house is suitable for rent based on the presence of interior images. If there are no interior images, the house is deemed unsuitable; otherwise, it is classified as suitable.
## Multi-class Model: 
This model evaluates the condition of the house interior across four classes: 'Excellent', 'Good', 'Average', and 'Poor', providing a more nuanced understanding of the property's condition.
## Vision Score Calculation: 
In addition to classifying the interior condition, we calculate a vision score for each house based on the image analysis results. This score provides an intuitive metric for assessing the overall visual appeal of the property, which can influence its rental value
