# Klasifikasi Daging Menggunakan Ekstraksi Fitur GLCM dan Random Forest

Repositori ini berisi kode dan notebook untuk klasifikasi jenis daging (daging sapi, daging babi, dan daging kuda) berbasis citra digital menggunakan metode ekstraksi fitur tekstur GLCM (Gray Level Co-Occurrence Matrix) dan algoritma klasifikasi Random Forest.

## 🧪 Metode

- **Ekstraksi Fitur**: GLCM (Gray Level Co-occurrence Matrix)
- **Klasifikasi**: Random Forest Classifier
- **Preprocessing**: 
  - Konversi Grayscale
  - Histogram Equalization
  - Median Filter *(dapat dipilih satu)*

## 💻 Tools yang Digunakan

- Python 3 (Google Colab)
- Scikit-learn
- OpenCV
- Pandas, NumPy, Matplotlib
- Gradio (untuk UI prediksi gambar)

## 🚀 Cara Menjalankan

1. Clone repositori ini:
    ```
    git clone https://github.com/AogamiKiryuu/Klasifikasi-abjad-tulisan-tangan.git
    ```

2. Buka `Final_GLCM.ipynb` di Google Colab.

3. Pastikan dataset sudah tersedia di Google Drive dan di-mount ke Colab.

4. Jalankan sel-sel untuk preprocessing, training, evaluasi, dan testing.

## 🧠 Output

Model akan mengklasifikasikan gambar menjadi:
- **meat**
- **horse meat**
- **pork**
- atau `'-'` jika gambar bukan daging
