# OpenCV Lab — Computer Vision & Image Processing

**Tech Stack:** Python 3.10+, OpenCV (`cv2`), NumPy, Matplotlib, Jupyter Notebook.  
**Standards & Operating Workflow:** Terintegrasi penuh dengan [Workflow Master](.workflow/README.md).

---

## 1. Operating Discipline & Engineering Workflow
Semua pekerjaan computer vision dan coding pada repositori ini WAJIB mematuhi 9 tahapan alur kerja di `.workflow/workflows/00-engineering-workflow-ai-coding.md`:
1. **Triage:** Pahami tujuan pemrosesan citra/video (filtering, deteksi kontur, transformasi geometri, deteksi wajah).
2. **Discover:** Periksa format input gambar/video, channel warna (BGR vs RGB), resolusi, dan tipe data matriks (`uint8` vs `float32`).
3. **Design:** Tentukan alur algoritma pipeline (preprocessing, thresholding, morphological ops, feature extraction).
4. **Plan:** Tentukan file notebook atau modul script yang dikembangkan.
5. **Implement:** Tulis kode pemrosesan citra yang teroptimasi, modular, dan terhindar dari kebocoran memori pada loop video streaming.
6. **Verify:** Validasi visualisasi hasil, release window (`cv2.destroyAllWindows()`), dan release video capture (`cap.release()`).
7. **Review:** Evaluasi ketepatan deteksi dan latensi per frame (FPS).
8. **Release:** Simpan parameter threshold terbaik ke dalam file konfigurasi/script.
9. **Report:** Laporkan visualisasi komparasi (Before vs After) dan akurasi deteksi secara transparan.
