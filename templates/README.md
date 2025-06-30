# Judul Project

## Deskripsi

Tuliskan deskripsi singkat project anda.

## Struktur Folder

jika anda ingin project anda lebih terstruktur, anda bisa menggunakan struktur project seperti berikut:

```
.
├── data/           # untuk menyimpan data
│   ├── external    # untuk menyimpan data eksternal yang tidak berubah
│   ├── raw         # untuk menyimpan data mentah
│   └── processed   # untuk menyimpan data yang sudah diproses
├── models          # untuk menyimpan model
├── reports         # untuk menyimpan laporan bisa plot, analisis, atau hasil evaluasi
├── src             # untuk menyimpan kode sumber atau custom package
│   └── __init__.py # untuk membuat src sebagai package
└── notebook.ipynb  # file notebook utama
```

> jika anda terbiasa menggunakan satu file notebook.ipynb, anda dapat mereferensi `crisp_dm_emplate.ipynb` 
untuk project yang membutuhkan framework CRISP-DM. Selengkapnya, anda dapat mempelajari pada [materi ini](../guides/crisp_dm_material.pdf).
Sesuaikan dengan kebutuhan project anda yaa.
