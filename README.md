# Proyek Pertama: Menyelesaikan Permasalahan Perusahaan Jaya-Jaya Maju

## Business Understanding

Jaya Jaya Maju merupakan salah satu perusahaan multinasional yang telah berdiri sejak tahun 2000. Ia memiliki lebih dari 1000 karyawan yang tersebar di seluruh penjuru negeri. 

### Permasalahan Bisnis

Walaupun telah menjadi menjadi perusahaan yang cukup besar, Jaya Jaya Maju masih cukup kesulitan dalam mengelola karyawan. Hal ini berimbas tingginya attrition rate (rasio jumlah karyawan yang keluar dengan total karyawan keseluruhan) hingga lebih dari 10%.

### Cakupan Proyek

- Pengumpulan dan persiapan data karyawan
- Analisis deskriptif dengan python
- Identifikasi faktor utama attrition
- Membuat visualisasi data dengan metabase
- Rekomendasi insight untuk HR

### Persiapan

Sumber data: https://github.com/dicodingacademy/dicoding_dataset/tree/main/employee

Setup environment:

```
# 1. Buat virtual environment
python -m venv env

# 2. Install library yang dibutuhkan
pip install pandas

# 3. Jalankan Jupyter Notebook
jupyter notebook

```

akun metabase :
email “root@mail.com”
password “root123”

## Business Dashboard

Menjelaskan tentang attrition rate global dan per divisi departmen,job role. Kemudian menampilkan persentase fatkor yang mempengaruhi keluarnya karyawan berdasarkan kerja lembur, umur, keseimbangan hidup. Mencari korelasi terhadap pendapatan perbulan

## Conclusion

Analisis ini bertujuan untuk memahami pola attrition (tingkat pengunduran diri) pada karyawan dengan pendekatan berbasis data. Setelah proses pembersihan data, didapatkan attrition rate keseluruhan sebesar **16,92%**.

Beberapa temuan penting dari analisis ini antara lain:

- Departemen dengan tingkat attrition tertinggi adalah *Sales* sebesar *20,69%*, diikuti oleh *Human Resources* (*16,79%*) dan *R&D* (*15,26%*).
- Job role paling rentan terhadap attrition adalah *Sales Representative* dengan angka mencapai *43,1%*.
- 75% karyawan yang mengalami attrition tercatat memiliki status lembur (OverTime), menunjukkan korelasi antara beban kerja dan niat keluar.
- Usia di bawah 30 tahun menjadi kelompok umur dengan attrition tertinggi, yaitu sebesar *44%*.
- Dari sisi keseimbangan hidup (Work-Life Balance), karyawan dengan kondisi "Poor" mengalami attrition sebesar 38%.
- Berdasarkan penghasilan, karyawan dengan pendapatan di kuartil pertama (*1k–3k*) memiliki attrition rate sebesar *29,6%*, menunjukkan potensi hubungan antara kompensasi rendah dan tingkat keluar masuknya karyawan.

Temuan-temuan ini memberikan gambaran yang kuat bagi manajemen untuk merumuskan strategi retensi yang lebih tepat sasaran, seperti peningkatan kesejahteraan karyawan, peninjauan beban kerja, dan program pengembangan karir terutama bagi karyawan muda dan posisi rentan.


### Rekomendasi Action Items (Optional)

Berikan beberapa rekomendasi action items yang harus dilakukan perusahaan guna menyelesaikan permasalahan atau mencapai target mereka.

- Memberikan perhatian pada pekerja terutama bagian sales untuk evaluasi terkait keadaan overtime
- Perusahan mulai beradaptasi terhadap workflow umur 30 tahun kebawah yang dimana mengedepankan worklifebalance yang baik
