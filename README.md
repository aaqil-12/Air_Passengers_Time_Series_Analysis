# ✈️ Air Passengers Forecasting using GluonTS (DeepAR)

This project demonstrates how to use **DeepAR**, a probabilistic time series forecasting model from Amazon’s [GluonTS](https://ts.gluon.ai/stable/index.html) library, to forecast the number of international airline passengers over time.

---

## 📊 Dataset

**Name**: [International Airline Passengers Dataset](https://raw.githubusercontent.com/jbrownlee/Datasets/master/airline-passengers.csv)  
**Description**: Monthly total number of passengers (in thousands) from January 1949 to December 1960.  
**Frequency**: Monthly (`freq="M"`)  
**Columns**:
- `Month`: Date in `YYYY-MM` format
- `Passengers`: Number of passengers (in thousands)

---

## 📦 Libraries Used

- Python 3.x
- [GluonTS](https://github.com/awslabs/gluonts)
- MXNet (as backend)
- Matplotlib
- Pandas
- NumPy

---

## 🔧 Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/air-passengers-forecasting.git
   cd air-passengers-forecasting
2. Install Dependencies

pip install gluonts mxnet pandas matplotlib
3. Run the Notebook
Open Air_Passengers_Forecast.ipynb in Jupyter Notebook or Colab.
