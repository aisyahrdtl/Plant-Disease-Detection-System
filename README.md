🌿 Plant Disease Detection using Computer Vision
📋 Deskripsi
Program ini merupakan aplikasi sederhana berbasis Python yang bertujuan untuk melakukan deteksi penyakit pada daun tanaman (plant disease detection) menggunakan teknik computer vision dan image processing, yaitu:

Multi-color Space Analysis (HSV, LAB, RGB),
Morphological Operations untuk noise reduction,
CLAHE (Contrast Limited Adaptive Histogram Equalization) untuk enhancement,
Color-based Segmentation untuk deteksi area yang terinfeksi.

Program ini berjalan di lingkungan Google Colab, menggunakan pustaka seperti OpenCV, NumPy, SciPy, dan Matplotlib.

⚙️ Fitur Utama

Upload gambar daun (format .jpg / .png) melalui Google Colab.
Pre-processing menggunakan Gaussian blur dan sharpening.
Enhancement menggunakan CLAHE untuk meningkatkan kontras.
Analisis multi-color space (HSV, LAB, RGB).
Deteksi area penyakit menggunakan color thresholding.
Segmentasi daun untuk membatasi area analisis.
Perhitungan persentase tingkat keparahan penyakit.
Visualisasi hasil deteksi secara berdampingan (input, mask, overlay).


🔧 Teknologi & Pustaka yang Digunakan

Python 3.x
Google Colab
OpenCV
NumPy
SciPy
Matplotlib


🚀 Cara Menjalankan Program

Buka Google Colab dan unggah notebook .ipynb yang berjudul:
Viskom Final Project.ipynb
Jalankan semua sel secara berurutan.
Ketika diminta, upload gambar daun yang ingin dianalisis.
Program akan menampilkan:
Gambar asli dan hasil enhancement,
Analisis berbagai color space (HSV, LAB, RGB),
Mask deteksi penyakit dari berbagai metode,
Hasil segmentasi daun,
Overlay hasil deteksi dengan persentase keparahan,
Klasifikasi tingkat keparahan (Very Light, Light, Moderate, Severe, Very Severe).




📊 Contoh Output
Program akan menghasilkan visualisasi lengkap yang menunjukkan:

Original Image: Gambar daun asli
Enhanced Image: Hasil setelah CLAHE enhancement
Color Space Analysis: Breakdown HSV, LAB, dan RGB channels
Disease Masks: Mask deteksi dari berbagai metode
Final Detection: Overlay hasil deteksi dengan statistik
Disease Percentage: Persentase area yang terinfeksi
Severity Classification: Klasifikasi tingkat keparahan

Contoh output persentase:
Leaf area: 145230 pixels
Sick pixels: 8924
Disease percentage: 6.14%
Severity: Light

📈 Evaluasi

Multi-method Approach: Kombinasi HSV, LAB, dan RGB analysis memberikan deteksi yang lebih robust.
Adaptive Thresholding: Penggunaan CLAHE dan morphological operations meningkatkan akurasi segmentasi.
Conservative Boundary Detection: Sistem boundary detection yang konservatif untuk menghindari false positive.
Severity Classification: Sistem klasifikasi 5 tingkat untuk penilaian keparahan yang praktis.


👨‍🎓 Penulis
Siti Aisyah Raodahtul Jannah - Universitas Hasanuddin Program Studi Teknik Informatika Tugas Besar Mata Kuliah Visi Komputer

📄 Lisensi
Proyek ini dibuat untuk keperluan akademik. Bebas digunakan untuk pembelajaran dan pengembangan lanjutan dengan mencantumkan atribusi yang sesuai.

