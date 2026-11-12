# Akuisisi Data Tempat Wisata dan Lokasi Budaya di Provinsi Bali

## 1. Identitas Tugas

- Mata Kuliah: Akuisisi dan Manajemen Data
- Nama:Apolinarisa Jack Herment 
- NIM: 2501010333
- Program Studi: Informatika
- Institusi: INSTIKI

## 2. Sumber Data

- Nama sumber: OpenStreetMap
- Website: https://www.openstreetmap.org/
- API yang digunakan: Overpass API
- Endpoint: https://overpass-api.de/api/interpreter
- Metode akuisisi: Mengambil data menggunakan API melalui Python di Google Colab.
- Wilayah pengambilan data: Provinsi Bali.
- Target data: Minimal 100 tempat wisata dan lokasi budaya.

## 3. Tujuan Akuisisi

Tujuan pengambilan data ini adalah mengumpulkan informasi mengenai tempat wisata dan lokasi budaya yang ada di Bali. Data ini dapat digunakan untuk mengetahui nama tempat, kategori, serta letak geografisnya. Data tersebut juga dapat menjadi informasi pendukung dalam bidang pariwisata dan budaya.

## 4. Kolom Data

Data yang dikumpulkan memiliki beberapa kolom:

1. `nama_tempat`: Nama tempat wisata atau lokasi budaya.
2. `kategori`: Jenis atau kategori tempat.
3. `latitude`: Garis lintang lokasi.
4. `longitude`: Garis bujur lokasi.
5. `osm_id`: Identitas objek pada OpenStreetMap.
6. `jenis_objek`: Jenis objek OpenStreetMap, seperti node, way, atau relation.
7. `alamat`: Informasi alamat jika tersedia pada sumber data.

Tidak semua tempat memiliki informasi alamat yang lengkap.

## 5. Etika Pengambilan Data

Pengambilan data dilakukan menggunakan Overpass API untuk keperluan pendidikan.

Batasan yang diterapkan:
- Menggunakan data publik dari OpenStreetMap.
- Menggunakan User-Agent yang mengidentifikasi aplikasi.
- Memberikan jeda permintaan jika melakukan pengambilan data berulang.
- Menggunakan timeout dan memeriksa status respons API.
- Tidak mengambil data pribadi.
- Tidak mengubah isi data mentah yang disimpan.
- Memberikan atribusi kepada OpenStreetMap dan kontributor.

Lisensi data: Open Database License (ODbL).

Sumber lisensi: https://www.openstreetmap.org/copyright

Atribusi: © OpenStreetMap contributors.

## 6. Struktur Folder

```text
rtm1_2501010333/
├── notebooks/
│   └── akuisisi_openstreetmap.ipynb
├── data/
│   └── raw/
│       └── openstreetmap_bali_YYYYMMDD.csv
├── docs/
│   ├── provenance.json
│   └── data_ethics_checklist.csv
└── README.md
```

## 7. Cara Menjalankan Notebook

1. Buka Google Colab.
2. Buka notebook akuisisi_openstreetmap.ipynb.
3. Jalankan kode dari bagian paling atas sampai selesai.
4. Periksa apakah data berhasil diambil.
5. Simpan hasil data mentah dalam format CSV.
6. Masukkan notebook dan file hasil pengambilan data ke repository GitHub.

## 8. Referensi

- OpenStreetMap: https://www.openstreetmap.org/
- Overpass API: https://overpass-api.de/
- Lisensi OpenStreetMap: https://www.openstreetmap.org/copyright
