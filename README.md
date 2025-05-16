# Deskewing Image with Multiple Methods
*Implementasi algoritma dari paper: Boiangiu et al. (2020) - Voting-Based Document Image Skew Detection*

Repo ini berisi implementasi Python untuk mendeteksi dan mengoreksi kemiringan gambar (deskewing) menggunakan tiga metode berbeda dengan pendekatan voting seperti yang diusulkan dalam penelitian:

**Referensi Utama**:  
Boiangiu, C.-A., Dinu, O.-A., Popescu, C., Constantin, N., & Petrescu, C. (2020).  
[Voting-Based Document Image Skew Detection](https://doi.org/10.3390/app10072236).  
Applied Sciences, 10(7), 2236.  

**Dataset Uji**:  
📂 [Kaggle - rdocuments](https://www.kaggle.com/datasets/) *(sekitar 950 gambar dokumen dengan variasi kemiringan)*  
Repo ini berisi implementasi Python untuk mendeteksi dan mengoreksi kemiringan gambar (deskewing) menggunakan tiga metode berbeda: Analisis FFT, Projection Profiling, dan Hough Transform. Program ini dijalankan di Google Colab dan cocok untuk pemrosesan dokumen yang mengalami kemiringan saat discan/difoto.

## Fitur Utama
✅ **3 Metode Deteksi Kemiringan**:
   - **FFT (Fast Fourier Transform)**: Analisis frekuensi gambar.
   - **Projection Profiling**: Analisis variansi proyeksi vertikal.
   - **Hough Transform**: Deteksi garis lurus dominan.

✅ **Sistem Voting Otomatis**:
   - Memilih hasil terbaik berdasarkan confidence level.

✅ **Visualisasi Lengkap**:
   - Menampilkan hasil setiap tahap proses.

✅ **Kompatibel dengan Google Colab**:
   - Support upload gambar langsung dari komputer.

## Cara Menggunakan
1. Buka file `Deskewing_Image.ipynb` di Google Colab.
2. Jalankan semua sel (Runtime > Run all).
3. Upload gambar ketika diminta.
4. Program akan menampilkan:
   - Hasil deteksi dari setiap metode.
   - Sudut kemiringan terdeteksi.
   - Gambar yang sudah dikoreksi.

## Contoh Hasil
![Contoh Hasil](https://github.com/arezyhs/Python-Digital-Image-Processing-Projects/blob/main/hasil.png)

## Requirement
- Python 3.6+
- Libraries:
- /repo
- │── PCD-Voting-Based-Documents.ipynb # Main notebook
- │── README.md # Dokumentasi
- └── gambar-sampel/ # Contoh gambar uji
