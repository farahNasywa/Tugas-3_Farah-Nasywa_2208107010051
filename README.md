# Tugas-3_Farah-Nasywa_2208107010051

# Rock-Paper-Scissors Classification Project 🪨📄✂️
---

## 📚 Deskripsi Proyek

Proyek ini bertujuan untuk membangun sistem klasifikasi gambar sederhana menggunakan **Deep Learning** dengan arsitektur **Transfer Learning** (menggunakan MobileNetV2).  
Gambar yang diklasifikasikan terdiri dari tiga kategori: **Rock**, **Paper**, dan **Scissors**.

Model yang dilatih kemudian akan diintegrasikan ke dalam aplikasi backend berbasis **FastAPI**, sehingga bisa menerima gambar dan memberikan hasil prediksi secara real-time.

---

## 🛠️ Teknologi yang Digunakan

- **TensorFlow / Keras** — Untuk membangun dan melatih model klasifikasi gambar.
- **FastAPI** — Untuk membangun backend REST API.
- **Uvicorn** — Sebagai ASGI server untuk menjalankan FastAPI.
- **PIL (Pillow)** — Untuk memproses gambar.
- **NumPy** — Untuk manipulasi data numerik.
- **scikit-learn** — Untuk evaluasi model (classification report, confusion matrix).

---

## 📂 Struktur Folder Proyek

```
Tugas-3_Farah-Nasywa_2208107010051/
├── backend/
│   ├── main.py         # Kode backend FastAPI
│   └──requirements.txt
├── frontend/
│   ├── main.py         
│   └──requirements.txt   
├── model/
│   └── best_transfer.keras # Model hasil training yang disimpan
├── images/
│   ├── Frontend
│   ├── Frontend
│   ├── HasilEvaluasiModel
│   └── TrainingModel
├── dataset/
│   ├── rock/
│   ├── paper/
│   └── scissor/
├── README.md
└── notebook.ipynb
```

---

## 🚀 Langkah Penggunaan

### 1. Clone Repository

git clone https://github.com/Tugas-3_Farah-Nasywa_2208107010051.git
cd Tugas-3_Farah-Nasywa_2208107010051

### 2. Siapkan Environment Python

Disarankan menggunakan **Python 3.9–3.11**.

Buat environment baru, lalu install dependencies:

pip install -r requirements.txt

### 3. Download Dataset

Unduh dataset Rock-Paper-Scissors dari Kaggle:  
🔗 [Rock-Paper-Scissors Dataset – Kaggle](https://www.kaggle.com/datasets/drgfreeman/rockpaperscissors)

Setelah download dan ekstrak:
- Susun dataset ke dalam folder:

dataset/
    rock/
    paper/
    scissor/

### 4. Jalankan Backend FastAPI

Masuk ke folder `frontend/`, lalu jalankan:

`streamlit run app.py`

Streamlit akan berjalan di `http://localhost:8501/`

Kemudian, masuk ke folder `backend/`, lalu jalankan:

`uvicorn main:app --host 0.0.0.0 --port 8000 --reload`

Server akan berjalan di `http://localhost:8000/`.

---

## 🎯 Tujuan Pembelajaran

- Memahami alur kerja training dan deployment model machine learning.
- Membiasakan diri mengintegrasikan model ke dalam aplikasi backend nyata.
- Melatih kerapihan penyusunan struktur proyek dan dokumentasi.

---

## 📋 Hasil Model

<img width="1439" alt="Frontend" src="https://github.com/user-attachments/assets/042792aa-460c-4310-82e6-db965cba7dfe" />

<img width="1440" alt="Frontend1" src="https://github.com/user-attachments/assets/e33d79b1-9105-40a9-ba1b-0871b939041e" />

<img width="1239" alt="HasilEvaluasiModel" src="https://github.com/user-attachments/assets/cc3adb22-3da7-4a39-aae1-fef45e0f09d2" />

<img width="1232" alt="TrainingModel" src="https://github.com/user-attachments/assets/e301e037-7462-4dd9-ba32-b61a55b62bd7" />

---
