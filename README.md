# 📷 OpenCV Lab

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" alt="OpenCV"/>
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy"/>
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter"/>
  <a href="https://colab.research.google.com/github/pranataa-labs/opencv-lab/blob/main/belajar-opencv.ipynb" target="_blank">
    <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab" style="height: 28px;"/>
  </a>
</p>

Repositori latihan interaktif untuk belajar pengolahan citra (*image processing*) dan Computer Vision menggunakan **OpenCV** dari dasar hingga tingkat lanjut.

---

## 📌 Topik Pembelajaran

- **Dasar OpenCV & I/O Citra**: Import OpenCV & NumPy, Membaca Gambar (`imread`), Menampilkan Gambar (`cv2_imshow` / Matplotlib), Menyimpan Gambar (`imwrite`), Properti Citra (Resolusi & Channel), Akses & Modifikasi Piksel BGR, Membuat Kanvas Kosong.
- **Transformasi Geometri & Menggambar**: Mengubah Ukuran (`resize`), Pemotongan (*Cropping*), Translasi (`warpAffine`), Rotasi Matriks, Membalik Gambar (`flip`), Menggambar Garis, Persegi & Lingkaran, Menambahkan Teks (`putText`).
- **Ruang Warna & Thresholding**: Konversi Grayscale (`cvtColor`), Ruang Warna HSV, Split & Merge Channel, Simple Thresholding, Adaptive Gaussian Thresholding, Otsu's Thresholding, Membalik Warna (*Invert*).
- **Filtering, Blurring & Deteksi Tepi**: Custom Kernel (Konvolusi 2D), Averaging Blur, Gaussian Blur, Median Blur, Bilateral Filter, Deteksi Tepi Sobel, Laplacian, Canny Edge Detection.
- **Morfologi Matematika & Analisis Kontur**: Operasi Erosi, Dilasi, Opening, Closing, Deteksi Kontur (`findContours`), Menggambar Kontur (`drawContours`), Bounding Box, Perhitungan Luas Area & Keliling.
- **Fitur Lanjutan, Masking & Pemrosesan Video**: Operasi Bitwise (AND, OR, XOR), Image Masking, Kalkulasi Histogram Warna, Histogram Equalization, CLAHE, Template Matching, Deteksi Wajah (Haar Cascades), Membaca Video (`VideoCapture`), Ekstraksi Frame, Menyimpan Video (`VideoWriter`).

---

## 🚀 Cara Menjalankan

### Opsi A: Google Colab
Klik badge **Open in Colab** di atas atau buka file `belajar-opencv.ipynb` langsung di Google Colab.

### Opsi B: Lokal / JupyterLab
```bash
# Clone repository
git clone https://github.com/pranataa-labs/opencv-lab.git
cd opencv-lab

# Install dependencies
pip install -r requirements.txt

# Jalankan JupyterLab
jupyter lab
```

---

<p align="center">
  Crafted with curiosity by <a href="https://github.com/pranataa-labs"><b>pranataa-labs</b></a>.
</p>
