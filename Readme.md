# Proyek Klasifikasi Gambar Menggunakan CNN

## Deskripsi

Proyek ini bertujuan untuk mengklasifikasikan gambar menggunakan Convolutional Neural Network (CNN) dengan dataset CIFAR-10. CIFAR-10 adalah dataset yang terdiri dari 60.000 gambar warna berukuran 32x32 piksel, terbagi menjadi 10 kelas yang berbeda, yaitu:

- Pesawat
- Mobil
- Burung
- Kucing
- Rusa
- Anjing
- Katak
- Kuda
- Kapal
- Truk

Model CNN yang dibangun dalam proyek ini berfungsi untuk mengenali dan mengklasifikasikan gambar dari berbagai kelas di atas berdasarkan fitur visual.

## Struktur Proyek

Proyek ini terdiri dari satu Jupyter Notebook (`cifar10_image_classification.ipynb`) yang mencakup langkah-langkah berikut:

### 1. Impor Pustaka
Pada langkah ini, pustaka yang diperlukan, termasuk TensorFlow dan Matplotlib, diimpor ke dalam proyek.

### 2. Muat Dataset
Dataset CIFAR-10 diunduh dan dipisahkan menjadi set pelatihan dan pengujian untuk digunakan dalam pelatihan model.

### 3. Preprocessing Data
Gambar dinormalisasi agar nilai piksel berada dalam rentang 0-1, yang membantu model dalam proses pelatihan.

### 4. Bangun Model CNN
Model CNN sederhana dibangun dengan beberapa lapisan konvolusi dan pooling untuk mengekstrak fitur dari gambar.

### 5. Latih Model
Model dilatih menggunakan data pelatihan dan divalidasi dengan data pengujian untuk mengukur kinerjanya.

### 6. Evaluasi Model
Akurasi model dievaluasi pada dataset pengujian untuk mengetahui seberapa baik model dapat mengklasifikasikan gambar.

### 7. Visualisasi Hasil
Hasil akurasi pelatihan dan validasi selama proses pelatihan divisualisasikan dalam bentuk grafik.

## Cara Menjalankan

Buka [Google Colab](https://colab.research.google.com/) dan ikuti langkah-langkah berikut:

1. Unggah file `cifar10_image_classification.ipynb` ke dalam Google Colab.
2. Jalankan sel-sel di notebook satu per satu untuk melatih dan menguji model klasifikasi gambar.

## Prasyarat

Agar dapat menjalankan proyek ini, Anda perlu memiliki akses ke Google Colab. Pengetahuan dasar tentang Python dan pembelajaran mendalam (deep learning) juga diperlukan. Pustaka yang diperlukan sudah diinstal dan akan diinstal secara otomatis di Google Colab.

## Analisis Hasil

Setelah menjalankan notebook, hasil akhir akurasi pada dataset pengujian akan dicetak. Selain itu, grafik akurasi pelatihan dan validasi akan ditampilkan, memberikan wawasan tentang kinerja model selama pelatihan.
