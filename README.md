# 💎 Diamond Price Prediction

This project aims to predict the price of diamonds using machine learning techniques. The model is built on a dataset with various features related to the diamond's physical attributes and quality. The final model is deployed as a web interface where users can input diamond features and get the predicted price.

## 🚀 How to Run

1. **Create a virtual environment**:
   ```bash
   conda create --name env python=3.9
   
2. **Activate the environment**:
   ```bash
   conda activate env

3. **Install the required dependencies by running the setup.py file**:
   ```bash
   python setup.py install

4. **Run the training pipeline**:
   ```bash
   python training_pipeline.py

That's it! 🎉 You're all set to start predicting diamond prices.

# 📊 Introduction About the Data

The goal of this project is to predict the price of a diamond based on several features (Regression Analysis).

### **Dataset Overview**

The dataset includes the following 10 independent variables (including `id`):

- **`id`**: Unique identifier for each diamond
- **`carat`**: Weight of the diamond in carats
- **`cut`**: Quality of the diamond cut
- **`color`**: Color grade of the diamond
- **`clarity`**: Purity and rarity of the diamond, graded under 10x magnification
- **`depth`**: Height of the diamond (in mm) from the culet to the table
- **`table`**: Width of the diamond's top facet
- **`x`**: X dimension of the diamond (in mm)
- **`y`**: Y dimension of the diamond (in mm)
- **`z`**: Z dimension of the diamond (in mm)

### **Target Variable**

- **`price`**: The price of the diamond.

You can find the dataset on Kaggle:  
[Dataset Source](https://www.kaggle.com/competitions/playground-series-s3e8/data?select=train.csv)


### 🛠️ Feature Engineering & Model Building

- Performed **data visualization** to understand the relationships between features.
- Created 3 new features (`cut`, `clarity`, `color`) based on domain knowledge to enhance prediction accuracy.
- Applied **feature engineering** and trained multiple models using a pipeline.
- Selected **ElasticNet** as the best model for prediction.


### 🌐 Web Interface

An end-to-end web interface was built to allow users to input diamond features and receive the predicted price. This interface makes the model easy to use and accessible to non-technical users.
