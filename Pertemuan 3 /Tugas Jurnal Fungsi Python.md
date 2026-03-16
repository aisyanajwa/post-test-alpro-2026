# Tugas Jurnal Praktikum 3 – Fungsi Pyhton
## Format Pengumpulan
File dikumpulkan dalam 1 dokumen PDF yang berisi:

Kode program
1. Flowchart sederhana (boleh digambar tangan atau digital)
2. Screenshot hasil running (output)
3. Penjelasan alur logika program untuk setiap soal dalam 1 paragraf

Catatan:

- Penjelasan boleh ditulis langsung di dokumen (misalnya Word) atau dalam bentuk komentar/markdown pada kode program.
- Kode program juga boleh ditampilkan dalam bentuk screenshot per bagian atau dituliskan langsung di dokumen.
- Format penyusunan bebas, yang penting seluruh komponen di atas tersedia dan dikumpulkan dalam 1 file PDF.

Kumpulkan di: https: https://drive.google.com/drive/folders/12rtzzzJIC_cja7sfBPdIs6MKFWWiVTgS?usp=sharing

# Soal Menghitung Peluang Mendapatkan Bola Berwarna
Seorang dosen ingin mengetahui seberapa besar penyebaran nilai ujian mahasiswa dalam suatu kelas. Untuk itu, 
dosen tersebut ingin menghitung variansi dari nilai-nilai mahasiswa. Variansi digunakan untuk mengetahui apakah nilai mahasiswa 
cenderung berdekatan dengan rata-rata atau justru menyebar jauh.

Variansi dapat dihitung dengan rumus berikut:
```math
\sigma^2 = \frac{\sum (x_i - \bar{x})^2}{n}
```

Keterangan : 
- $x_i$ = setiap nilai mahasiswa  
- $\bar{x}$ = rata-rata nilai  
- $n$ = jumlah data​

Buatlah sebuah fungsi Python bernama hitung_variansi(data) yang:
1. Menerima sebuah list berisi nilai mahasiswa.
2. Menghitung rata-rata nilai.
3. Menghitung variansi dari data tersebut berdasarkan rumus di atas.
4. Mengembalikan nilai variansi.

Ketentuan:
1. Program harus menggunakan fungsi Python.
2. Perhitungan dilakukan menggunakan perulangan.
3. Tidak diperbolehkan menggunakan library statistik seperti NumPy atau Pandas.
