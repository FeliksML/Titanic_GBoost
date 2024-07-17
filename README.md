# 🚢 Titanic Survival Prediction (Work in Progress) 🧊

## 📊 Predicting Passenger Survival using Gradient Boosted Trees 🌳

Welcome to our ongoing Titanic Survival Prediction project! We're currently using machine learning to predict who would have survived the Titanic disaster. 🕵️‍♂️

### 🎯 Project Goal

Our mission is to build a model that can predict whether a passenger survived the Titanic sinking based on features like age, sex, ticket class, and more. 🧮

### 🛠 Technologies Used (So Far)

- Python 🐍
- Pandas 🐼
- TensorFlow 🧠
- TensorFlow Decision Forests 🌲
- Matplotlib 📈

### 📋 Current Progress

1. **Data Exploration and Cleaning** 🧹
    - Handled missing values in 'Age' using MICE 🕳️
    - Dropped 'Cabin' column due to high missing values 🗑️
    - Imputed 'Embarked' with mode value 🔤

2. **Initial Feature Engineering** ⚙️
    - Created 'Ticket_number' and 'Ticket_item' from 'Ticket' 🔨
    - Currently using 10 input features 🌟

3. **Preliminary Model** 🏗️
    - Implemented Gradient Boosted Trees 🌳
    - Achieved initial accuracy of 87.37% 🎉

4. **Preliminary Feature Importance** 🔍
    - Initial top feature: Sex 👫

### 📈 Initial Results

Our preliminary model shows:
- Accuracy: 87.37% 🎯
- Loss: 0.7564 📉

### 🚧 Ongoing Work

- Implementing hyperparameter tuning with 1000 trials 🎛️
- Exploring additional feature engineering possibilities 🛠️
- Planning to try other algorithms for comparison 🔀

### 🔜 Next Steps

- Complete hyperparameter tuning 🔧
- Analyze results of tuned model 📊
- Implement and compare other algorithms 🧪
- Refine feature engineering based on new insights 🔬

### 💻 Current Setup

1. Clone this repository 📂
2. Install required packages: `pip install -r requirements.txt` 📦
3. Run the Jupyter notebook (work in progress) 🏃‍♂️