# Traffic Injury Prediction (Machine Learning)



This project analyzes **traffic accident data** and predicts the **number of injuries** using **Machine Learning** techniques.

The model is trained using **Random Forest Regression** to estimate the expected number of injuries based on several factors such as:

* Hour of the crash
* Day of the week
* Weather conditions
* Trafficway type

The project also includes **data visualization** and an **interactive prediction interface**.

---

## Project Features

* Traffic accident data analysis
* Feature engineering from date/time
* Random Forest Regression model
* Model evaluation using:

  * MAE
  * RMSE
  * R² Score
* Data visualization with **Matplotlib** and **Seaborn**
* Interactive prediction using **ipywidgets**

---

## Dataset

The dataset used in this project is included in this repository.

Dataset file:

```
trafikk.zip
```

After extracting the file, the dataset can be accessed as:

```
trafikveri.csv
```

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* ipywidgets
* Joblib

---

## How to Run

1. Open the notebook in **Google Colab** or **Jupyter Notebook**
2. Extract the dataset file
3. Update the dataset path if necessary
4. Run all cells to train the model
5. Use the interactive interface to make predictions

---

## Model Output

The model predicts the **estimated number of injuries** for a traffic accident based on user inputs.

Example inputs:

* Hour
* Day of the week
* Weather condition
* Trafficway type

Output:

Estimated number of injured people.

---

## Author

Sara Acet
GitHub: https://github.com/SaraAcet

---







# Trafik Yaralanma Tahmini (Makine Öğrenmesi)

Bu projede **trafik kazası verileri analiz edilerek kazalarda oluşabilecek yaralı sayısı tahmin edilmektedir.**

Model, aşağıdaki faktörlere göre tahmin yapmaktadır:

* Kaza saati
* Haftanın günü
* Hava durumu
* Yol tipi

Tahmin modeli olarak **Random Forest Regression** kullanılmıştır.

---

## Proje Özellikleri

* Trafik kazası veri analizi
* Tarih verisinden yeni özellikler çıkarma
* Random Forest Regression modeli
* Model performans değerlendirmesi

  * MAE
  * RMSE
  * R² Score
* Matplotlib ve Seaborn ile veri görselleştirme
* ipywidgets ile etkileşimli tahmin sistemi

---

## Veri Seti

Projede kullanılan veri seti bu repository içinde bulunmaktadır.

Dosya:

```
trafikk.zip
```

Zip dosyası çıkarıldıktan sonra veri dosyası:

```
trafikveri.csv
```

---

## Kullanılan Teknolojiler

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* ipywidgets
* Joblib

---

## Projeyi Çalıştırma

1. Notebook dosyasını **Google Colab** veya **Jupyter Notebook** ile açın
2. Veri setini zip dosyasından çıkarın
3. Gerekirse veri yolu (dataset path) kısmını güncelleyin
4. Tüm hücreleri çalıştırarak modeli eğitin
5. Arayüz üzerinden tahmin yapabilirsiniz

---

## Geliştirici

Sara Acet
GitHub: https://github




