# Dataset

[![kaggle](https://img.shields.io/badge/Kaggle%20dataset-disini-blue?logo=kaggle)](https://www.kaggle.com/wahyusetianto/bdc-2021)

Dataset hasil preprocessing dan augmentasi dari kelompok Blazing Trio | `SD20210000722`.

**Mapping**

```
data/
  | --- Testing/
  | --- Training/
  | --- preprocessed.zip
  | --- preprocessed-augmented.zip
  | --- submission.csv
  | --- train.csv
```

1. `Testing` adalah folder utama tempat dari setiap data gambar untuk dilakukan peramalan.
2. `Training` adalah folder utama tempat dari setiap data gambar yang digunakan untuk melatih model sebelum melakukan peramalan pada data test.
3. `submission.csv` adalah file tempat menyimpan `id` data gambar yang ada di data test untuk dilakukan peramalan dan sebagai format untuk submissi.
4. `train.csv` adalah file tempat `id`, `age`, dan `gender` dari setiap data gambar pada `Training` directory.
5. `preprocessed.zip` adalah file yang berisi gambar - gambar yang telah dilakukan proses preprocessing oleh tim `SD20210000722`. Pada file ini terdiri dari:

   ```
   train/ - 3023 gambar
   test/  - 990  gambar
   preprocessed.csv
   ```

6. `preprocessed-augmented.zip` adalah file yang berisi gambar - gambar yang telah dilakukan proses preprocessing dan augmentasi oleh tim `SD20210000722`. Pada file ini terdiri dari:
   ```
   train/ - 12092 gambar
   test/  - 990  gambar
   preprocessed.csv
   ```

© Blazing Trio 2021
