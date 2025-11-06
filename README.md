# 🚗 Smart Car Price Predictor using ML

## 📋 Project Description

This project implements an intelligent machine learning system designed to accurately predict used car prices in the Indian automobile market. By analyzing multiple vehicle parameters and historical pricing data, the system provides reliable price estimations to help buyers and sellers make informed decisions.

## 🎯 Objective

The primary goal is to develop a robust predictive model that estimates car prices based on key features including:
- Vehicle age and manufacturing year
- Total kilometers driven (mileage)
- Fuel type (Petrol, Diesel, CNG, etc.)
- Transmission type (Manual/Automatic)
- Number of previous owners
- Seller type (Dealer/Individual)
- Brand and model specifications

## 🔍 Technical Approach

### Data Collection & Preprocessing
- Utilized comprehensive dataset from CarDekho with real market data
- Performed data cleaning and handled missing values
- Applied feature engineering techniques for better accuracy
- Normalized and scaled numerical features

### Machine Learning Models Implemented

#### 1. **Linear Regression Model**
   - Baseline model for price prediction
   - Analyzes linear relationships between features
   - Performance metrics:
     - Mean Absolute Error (MAE)
     - Root Mean Squared Error (RMSE)
     - R² Score for model accuracy

#### 2. **Random Forest Regression**
   - Advanced ensemble learning technique
   - Handles non-linear relationships effectively
   - Provides feature importance analysis
   - Better generalization and reduced overfitting

## 📊 Dataset Features

The dataset includes the following key attributes:

| Feature | Description |
|---------|-------------|
| **Car_Name** | Brand and model of the vehicle |
| **Year** | Manufacturing year |
| **Selling_Price** | Target variable (price in lakhs) |
| **Present_Price** | Current ex-showroom price |
| **Kms_Driven** | Total kilometers driven |
| **Fuel_Type** | Petrol, Diesel, or CNG |
| **Seller_Type** | Dealer or Individual |
| **Transmission** | Manual or Automatic |
| **Owner** | Number of previous owners |

## 🛠️ Technologies & Libraries Used

```python
- Python 3.x
- Pandas - Data manipulation and analysis
- NumPy - Numerical computations
- Scikit-learn - ML algorithms and tools
- Matplotlib & Seaborn - Data visualization
- Jupyter Notebook - Development environment
```

## 📈 Model Performance

Both models were evaluated using cross-validation techniques:
- Training accuracy compared with testing accuracy
- Residual analysis for prediction errors
- Feature correlation analysis

## 🚀 How to Run

1. Clone the repository:
```bash
git clone https://github.com/saurabhshukla9649/Car-Price-Predictor-ML.git
```

2. Install required dependencies:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
```

3. Open Jupyter Notebook:
```bash
jupyter notebook
```

4. Run the notebook file: `Cars Price Prediction.ipynb`

## 📁 Project Structure

```
Car-Price-Predictor-ML/
│
├── Cars Price Prediction.ipynb    # Main notebook with code
├── CAR DETAILS FROM CAR DEKHO.csv # Dataset file
├── README.md                      # Project documentation
└── requirements.txt               # Dependencies (if needed)
```

## 💡 Key Insights

- Brand and model significantly impact pricing
- Newer cars with lower mileage command higher prices
- Automatic transmission typically adds premium value
- Diesel cars often priced higher than petrol variants
- First-owner vehicles fetch better resale value

## 🔮 Future Enhancements

- [ ] Implement additional ML algorithms (XGBoost, Gradient Boosting)
- [ ] Develop a web interface for user-friendly predictions
- [ ] Add more features like car condition, service history
- [ ] Real-time data integration from multiple sources
- [ ] Deploy as a web application using Flask/Django

## 📝 License

This project is open-source and available for educational purposes.

## 👤 Author

**Saurabh Shukla**
- GitHub: [@saurabhshukla9649](https://github.com/saurabhshukla9649)

## 🙏 Acknowledgments

- Dataset source: CarDekho
- Inspiration from real-world automobile pricing challenges
- Machine Learning community for valuable resources

---

⭐ If you find this project helpful, please consider giving it a star!

#MachineLearning #DataScience #PricePrediction #Python #AI
