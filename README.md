# House-Property-Sales---Time-Series-Analysis-and-Forecasting

<h3>Source Dataset: https://www.kaggle.com/htagholdings/property-sales </h3>

## Overview

Project ini menggunakan dua model yaitu ARIMA dan SARIMA model, kemudian model terbaik dipilih berdasarkan akurasi terbaik atau Mean Absolute Percentage Error (MAPE) terendah. 

## Results

### Dataset

![GitHub Logo](/images/1.png)

### Splitting Dataset 

![GitHub Logo](/images/2.png)

![GitHub Logo](/images/3.png)

### ARIMA dan SARIMA 

Pada ARIMA tidak terlalu terlihat peramalan yang signifikan, mengingat hasilnya hanya memberi kita garis lurus:

![GitHub Logo](/images/4.png)

Itu kenapa pada ARIMA punya <b>Mean Absolute Percentage Error (MAPE)</b> yang sangat besar. Sedangkan SARIMA memiliki MAPE yang kecil hanya sekitar 4% dan ini hasilnya:

![GitHub Logo](/images/6.png)

Dan untuk diagnostic modelnya diperlihatkan di notebook. 

### Predictions

Saya mencoba memprediksi dalam jangka waktu 1 tahun menggunakan SARIMA, yang dimana dia adalah model yang lebih baik daripada ARIMA dalam kasus ini

![GitHub Logo](/images/pred.png)





