# Akuisisi Data Cuaca Kota Denpasar

## 1. Identitas Tugas

- Mata Kuliah: Akuisisi dan Manajemen Data
- Nama: Jack Apolinarisa
- NIM: 2501010333
- Program Studi: Informatika
- Institusi: INSTIKI

## 2. Sumber Data

- Nama sumber: Open-Meteo Weather API
- Penerbit: Open-Meteo
- Website: https://open-meteo.com/
- Endpoint API: https://api.open-meteo.com/v1/forecast
- Metode akuisisi: Mengambil data menggunakan API dengan Python melalui Google Colab.
- Lokasi data: Kota Denpasar, Bali.
- Periode data: Prakiraan cuaca selama 7 hari.
- Zona waktu: Asia/Makassar.

## 3. Tujuan Akuisisi

Tujuan pengambilan data ini adalah untuk memperoleh informasi cuaca di Kota Denpasar. Data ini dapat digunakan untuk melihat perubahan kondisi cuaca setiap jam dan menjadi informasi pendukung bagi kegiatan masyarakat maupun sektor pariwisata.

## 4. Kolom Data

Data yang dikumpulkan memiliki 6 kolom, yaitu:

1. `lokasi`: Nama lokasi pengambilan data.
2. `waktu`: Waktu prakiraan cuaca.
3. `suhu_c`: Suhu udara dalam derajat Celsius.
4. `curah_hujan_mm`: Curah hujan dalam milimeter.
5. `tutupan_awan_persen`: Persentase tutupan awan.
6. `kecepatan_angin_kmh`: Kecepatan angin dalam kilometer per jam.

## 5. Etika Pengambilan Data

Pengambilan data menggunakan API publik Open-Meteo untuk keperluan pendidikan dan tidak untuk tujuan komersial.

Batasan yang diterapkan:
- Menggunakan API resmi Open-Meteo.
- Mengikuti ketentuan penggunaan dan lisensi sumber data.
- Memberikan jeda minimal 1 detik apabila melakukan permintaan API berulang.
- Menggunakan timeout dan memeriksa status respons API.
- Tidak mengambil data pribadi pengguna.
- Tidak menggunakan atau membagikan API key rahasia.
- Data sumber disimpan dalam bentuk raw tanpa mengubah isi aslinya.

Lisensi data: CC BY 4.0.

Ketentuan lisensi: https://creativecommons.org/licenses/by/4.0/

Atribusi sumber: Weather data by Open-Meteo.

## 6. Struktur Folder

```text
rtm1_2501010333/
├── notebooks/
│   └── akuisisi_openmeteo.ipynb
├── data/
│   └── raw/
│       └── openmeteo_denpasar_YYYYMMDD.csv
├── docs/
│   ├── provenance.json
│   └── data_ethics_checklist.csv
└── README.md
```

## 7. Cara Menjalankan Notebook

1. Buka Google Colab.
2. Buka file `akuisisi_openmeteo.ipynb`.
3. Jalankan setiap kode dari bagian paling atas sampai selesai.
4. Pastikan proses pengambilan data berhasil.
5. Pastikan file CSV berhasil dibuat.
6. Simpan hasil notebook dan data ke dalam folder repository GitHub.

## 8. Referensi

- Open-Meteo Website: https://open-meteo.com/
- Open-Meteo API Documentation: https://open-meteo.com/en/docs
- Open-Meteo Terms: https://open-meteo.com/en/terms
- Creative Commons CC BY 4.0: https://creativecommons.org/licenses/by/4.0/
