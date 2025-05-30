# Tugas-Akhir-Viskom

Nama    : Nurfadillah Umar
NIM     : D121221022


**Tentang Kode Program**
Program ini merupakan sistem sederhana untuk pemindaian dokumen dalam bahasa pemrograman python dengan menggunakan library seperti OpenCV dan Numpy. Sistem dalam pemindaian dokumen ini menggunakan konvolusi Sobel untuk deteksi tepi dan kontur sehingga dapat diidentifikasi dengan jelas batas dokumen serta penerapan transformasi perspektif untuk menghasilkan gambar dokumen yang lurus(seperti hasil scanner).

**Dataset Citra Input**
1. Citra input untuk sampel uji dapat diakses melalui folder images
2. Cara lainnya yaitu mengunduh gambar dari Google Drive berikut: https://drive.google.com/drive/folders/19iH6iq-Ei3OSUeBw_WFyUzM_aRbGFeSL?usp=sharing


**Cara Menjalankan Program(Google Colab)**
1. Buka Google Colab: https://colab.research.google.com
2. Upload file Python atau salin seluruh kode program ke sebuah sel dalam notebook google colab
3. Upload file citra input ke dalam lingkungan kerja(/content) menggunakan ikon 📁 di sidebar kiri
4. Sesuaikan path citra input jika nama berbeda
5. Jalankan sel program utama dengan menekan ▶️ atau dengan menekan ctrl + enter

**Cara Menjalankan Program di Lokal**
1. Clone atau salin kode program
2. Install dependensi yang dibutuhkan
3. Menyesuaikan path citra input
4. Jalankan program

**Dependensi**
Google Colab sudah menyertakan sebagian besar library yang dibutuhkan. Namun jika menjalankan di lokal, maka harus install OpenCV dan Numpy dengan menjalankan perintah berikut di terminal:
pip install opencv-python numpy
