**Prediksi Harga Saham BBCA Menggunakan LSTM**

Repository ini berisi implementasi model Long Short-Term Memory (LSTM) untuk melakukan prediksi harga saham Bank Central Asia (BBCA) serta aplikasi Streamlit untuk visualisasi dan prediksi interaktif. Proyek ini bertujuan untuk menerapkan deep learning pada data time series saham dan menampilkan hasilnya dalam bentuk aplikasi web sederhana.

**Struktur Repository**
├── app (3).py              # Aplikasi Streamlit untuk prediksi harga saham

├── bbca.csv                # Dataset historis saham BBCA

├── model_lstm_bbca.keras   # Model LSTM terlatih

├── scaler_bbca.pkl         # Scaler untuk normalisasi data

├── requirements.txt        # Daftar dependensi Python

└── README.md               # Dokumentasi proyek

**Deskripsi singkat proyek **
Model LSTM digunakan karena kemampuannya dalam menangkap pola jangka panjang pada data runtun waktu (time series). Data harga saham BBCA diproses dan dinormalisasi menggunakan scaler, kemudian digunakan untuk melatih model LSTM. Model yang telah dilatih selanjutnya diintegrasikan ke dalam aplikasi Streamlit agar pengguna dapat melihat hasil prediksi secara langsung.

Teknologi yang Digunakan

Python

TensorFlow / Keras

NumPy & Pandas

Scikit-learn

Streamlit

## Demo Aplikasi

Aplikasi Streamlit dapat diakses melalui tautan berikut:  
👉 [https://nama-aplikasi.streamlit.app](https://lstmbbcaapp-9dgzuseenswyep9mngkmbf.streamlit.app/#grafik-harga-aktual-vs-prediksi)
