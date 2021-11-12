# BDC - Satria Data 2021

[![Python](https://img.shields.io/badge/Python-3.7%20|%203.8%20|%203.9-green?logo=python)](https://www.python.org/)
[![TensorFlow 2.6](https://img.shields.io/badge/TensorFlow-2.6.0-FF6F00?logo=tensorflow)](https://github.com/tensorflow/tensorflow/releases/tag/v2.6.0)

Tim : Blazing Trio | `SD20210000722`

Repo untuk merekam segala resources dalam lomba BDC - Satria Data tahun 2021.

## Dataset

1. [Kaggle](https://www.kaggle.com/wahyusetianto/bdc-2021)
2. [Github](./data/README.md)

## [Notebook](./notebook/README.md)

Beberapa notebook yang kami gunakan untuk mengerjakan challenge.

1. `[STARTER] BDC - 2021` : Starter notebook untuk mengerjakan challenge pertama dalam `BDC - Satria Data 2021`.
2. `[GENDER] BDC - 2021` : Final notebook untuk challenge pertama yaitu gender detection.
3. `[AGE] BDC - 2021`

## Hal yang sudah di coba

**Preprocessing**

1. Menggunakan `MTCNN` untuk mengambil daerah sekitar wajah, dilakukan filtering terhadap hasil dari
   `MTCNN` dengan `confidence score > 0.95` [FINAL]

   ![MTCNN](./assets/MTCNN.png)

2. Ubah ukuran data gambar menjadi `200 x 200` pixel [FINAL]

**Modelling**

1. Pake Resnet50 butuh lebih banyak epoch utuk training agar optimal
