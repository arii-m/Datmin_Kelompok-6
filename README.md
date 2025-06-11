# Datmin_Kelompok-6
# Prediksi Harga Mobil Bekas di Maroko

## Deskripsi
Repositori ini berisi analisis data dan forecasting harga mobil bekas di Maroko menggunakan pendekatan:
- **Exploratory Data Analysis (EDA)**  
  – Pembersihan data, konversi kolom numerik, filter outlier  
  – Statistik deskriptif, histogram, boxplot, heatmap korelasi  
- **Time Series Modeling (ARIMA)**  
  – Perbandingan agregasi Mean vs Median  
  – Split train/test, evaluasi MAE/RMSE/MAPE  
  – Final ARIMA(1,2,1) pada median series  
  – Forecast 5 tahun ke depan + 95% CI  
  – Diagnostik residual (ACF/PACF, Ljung–Box, Q–Q plot)

## Data
- `cars_dataframe.csv`: dataset harga mobil bekas- 2024 (merek, tahun, mileage, kondisi, dsb.)  
- Source:
  > Diunduh dari Mendeley Data (Dataset “Used Cars Morocco”), DOI: [10.17632/vjrbcb2rrt.2](https://data.mendeley.com/datasets/vjrbcb2rrt/2)   

## Struktur Folder
├── cars_dataframe.csv
├── datmin_eda_arima.ipynb 
└── README.md # Dokumen ini

