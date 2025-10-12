# 🎓 Research Project: Perbandingan Model XGBoost dan LightGBM untuk Prediksi Customer Churn pada Platform Netflix

## 📌 Deskripsi Singkat
Proyek penelitian ini bertujuan untuk **memprediksi customer churn pada platform streaming Netflix** dengan membandingkan dua algoritma machine learning berbasis boosting — **XGBoost** dan **LightGBM**.  
Penelitian ini juga menerapkan **Bayesian Optimization (Optuna)** untuk melakukan tuning hyperparameter secara efisien dan objektif, sehingga hasil perbandingan model lebih adil dan valid.

---

## 📍 Fenomena
Dalam era digital, layanan streaming seperti Netflix telah mengubah pola konsumsi hiburan menjadi berbasis on-demand. Persaingan yang ketat antarplatform membuat **retensi pelanggan** menjadi tantangan strategis utama. Fenomena **customer churn**, yaitu keputusan pelanggan untuk menghentikan langganan, berdampak langsung terhadap pendapatan dan stabilitas bisnis. Oleh karena itu, **prediksi churn berbasis machine learning** menjadi salah satu solusi yang banyak diteliti di bidang data-driven customer retention.

---

## ⚠️ Research Problem
### 1. Masalah Besar
Sebagian besar penelitian churn prediction masih berfokus pada **telekomunikasi dan e-commerce**, sementara **studi pada layanan video streaming** masih terbatas.  
Karakteristik perilaku pengguna streaming (seperti durasi tontonan, jeda antar episode, dan preferensi genre) berbeda secara signifikan dari sektor lain.  
Selain itu, belum banyak **perbandingan terkontrol** antara **XGBoost** dan **LightGBM** untuk konteks streaming.

### 2. Area Cakupan
Penelitian ini berfokus pada **prediksi churn pelanggan Netflix** dengan:
- Menggunakan **fitur perilaku pengguna (watch-time, genre, frekuensi nonton)**.  
- Membandingkan dua algoritma boosting modern (**XGBoost vs LightGBM**).  
- Menerapkan **Bayesian Optimization** sebagai metode tuning parameter.  

### 3. Pertanyaan Penelitian
- Bagaimana perbandingan performa algoritma XGBoost dan LightGBM dalam memprediksi churn pelanggan Netflix?  
- Sejauh mana Bayesian Optimization dapat membantu menghasilkan perbandingan yang lebih objektif?  
- Model mana yang paling unggul berdasarkan metrik evaluasi seperti akurasi, presisi, recall, F1-score, AUC, dan efisiensi waktu pelatihan?

---

## 🎯 Tujuan Penelitian
1. Menganalisis dan membandingkan performa XGBoost dan LightGBM dalam memprediksi churn pelanggan Netflix.  
2. Menggunakan **Bayesian Optimization (Optuna)** untuk tuning hyperparameter terbaik.  
3. Menentukan model terbaik berdasarkan hasil evaluasi komprehensif terhadap metrik performa dan waktu komputasi.

---

## 📊 Evaluasi Model
Evaluasi dilakukan berdasarkan beberapa metrik performa:
- **Accuracy**
- **Precision**
- **Recall**
- **F1-score**
- **AUC (Area Under Curve)**
- **Training Time / Computational Efficiency**

---

## 💡 Urgensi & Manfaat
- **Akademik:** Menambah literatur empiris terkait perbandingan algoritma boosting pada domain streaming.  
- **Praktis:** Memberikan rekomendasi bagi platform OTT seperti Netflix dalam strategi retensi pelanggan berbasis data.  
- **Teknis:** Menunjukkan efektivitas Bayesian Optimization dalam meningkatkan efisiensi tuning model.  
- **Inovatif:** Mengisi *research gap* karena minimnya studi perbandingan XGBoost–LightGBM dalam konteks VOD (Video on Demand).  

---




