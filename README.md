# BDC - Satria Data 2021

Tim : Anonymous (Belom punya nama :v)

Repo untuk merekam segala resources dalam lomba BDC - Satria Data tahun 2021.

## Dataset

Kaggle Dataset : [disini](https://www.kaggle.com/wahyusetianto/bdc-2021)

## To Do's

1. Filtering data gambar yang kurang baik untuk digunakan.
2. Augmentasi Data
3. Coba Model yang berbeda.
4. Grayscale dataset

## Hal yang udah di coba

**Preprocessing**

1. Pake `MTCNN` untuk mengambil daerah sekitar muka
2. Ubah ukuran data gambar menjadi beberapa ukuran. <br>
   **Hasil** : Kurang tau semakin kecil resolusi gambar yang digunakan hasil yang
   didapatkan dari model sedikit meningkat

**Modelling**

1. Pake Resnet50 butuh lebih banyak epoch utuk training agar optimal
