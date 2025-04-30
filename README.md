
# Image Classification Project

Proyek ini bertujuan membangun model Convolutional Neural Network (CNN) menggunakan TensorFlow untuk melakukan klasifikasi gambar.

## Dataset
- Menggunakan dataset dengan minimal 1000 gambar.
- Dataset **bukan** Rock, Paper, Scissors ataupun X-Ray.
- Dataset dibagi menjadi Train, Validation, dan Test Set.

## **Objective:**   
Membangun sebuah model menggunakan CNN yang dapat mengklasifikasikan penyakit pada daun padi dengan menggunakan gambar daun padi.

## **Sumber Dataset**
https://www.kaggle.com/datasets/loki4514/rice-leaf-diseases-detection

## Model
- Dibangun menggunakan arsitektur Sequential.
- Menggunakan Conv2D dan Pooling Layer.
- Target akurasi minimal 85% di training dan testing.

## Format Output Model
- SavedModel
- TensorFlow Lite (.tflite)
- TensorFlow.js (TFJS)

## Cara Menjalankan
1. Install semua dependensi:
    ```bash
    pip install -r requirements.txt
    ```
2. Jalankan notebook:
    ```bash
    jupyter notebook klasifikasi_gambar.ipynb
    ```

3. Setelah training selesai, model akan disimpan dalam 3 format berbeda.

## Struktur Folder
```
├── klasifikasi_gambar.ipynb
├── model_saved/            # SavedModel format
├── model_saved/model.tflite # TF-Lite format
├── model_tfjs/              # TensorFlow.js format
├── README.md
└── requirements.txt
```

## Catatan
- Pastikan dataset sudah tersedia di path yang benar sebelum menjalankan training.
- TensorFlowJS converter harus sudah terinstall.
