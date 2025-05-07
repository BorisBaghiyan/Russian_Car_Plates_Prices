# 🚗 Predicting Prices of Russian Car License Plates 🇷🇺

This project predicts the market value of Russian vehicle license plates using machine learning models. The aim is to build a regression model that evaluates a plate's price based on its visual and structural patterns (digits, letters, regions) and historical pricing data.

## 🚀 Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/BorisBaghiyan/Russian_Car_Plates_Prices.git
    ```

2. Navigate to the project directory:
    ```bash
    cd Russian_Car_Plates_Prices
    ```

3. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. Launch Jupyter Notebook to explore and run the code:
    ```bash
    jupyter notebook
    ```

## 🔧 Technologies

This project uses the following technologies:

- **Python** 🐍: Programming language.
- **Pandas** 📊: Data manipulation and analysis.
- **NumPy** 🔢: Numerical computations.
- **Scikit-learn** 🔬: Machine learning library for model building.
- **Matplotlib & Seaborn** 📈: Data visualization.
- **Jupyter Notebook** 📓: Interactive coding environment.

## 📝 How to Use

1. **Prepare the dataset**:
    - Download the dataset from Kaggle: [Russian Car Plates Dataset](https://www.kaggle.com/datasets/)
    - Place it inside the `data/` folder.

2. **Train the model**:
    - Launch Jupyter Notebook:
      ```bash
      jupyter notebook
      ```
    - Open the `car_plates_price_predict.ipynb` notebook and run the cells sequentially for data loading, preprocessing, and model training.

3. **Make predictions**:
    - Use the trained model to predict car plate prices:
      ```bash
      python src/inference.py --input_data path/to/your/car_plate_data.csv
      ```

## 💡 Features

- 🔥 Predict the price of car plates based on features like plate pattern, region, etc.
- 🔄 Data preprocessing: cleaning, encoding, and preparing the data.
- 📊 Model evaluation using metrics like Mean Squared Error (MSE) and R-squared (R²).
- 🌈 Visualization: training curves, prediction plots, feature importance.

## 🧠 Model Architecture

- **Input layer**: Features such as plate number, region, and other encoded data.
- **Regression model**: Random Forest, Linear Regression, or other regressors.
- **Output layer**: Predicted price of the car plate.

## 🏆 Model Performance

- **Loss function**: Mean Squared Error (MSE)
- **Metrics**: R-squared (R²), Mean Squared Error (MSE)

## 📊 Visualizations

- Training loss curves
- Comparison of actual vs. predicted car plate prices
- Feature importance charts

## 🤝 Contributing

Contributions are welcome:
- Fork the repository
- Open issues
- Submit pull requests

---

