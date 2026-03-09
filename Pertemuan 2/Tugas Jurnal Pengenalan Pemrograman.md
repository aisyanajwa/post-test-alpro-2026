# Tugas Pendahuluan Praktikum 2 – Pengenalan Pemrograman

## Format Pengumpulan

File dikumpulkan dalam **1 dokumen PDF** yang berisi:

1. Kode program  
2. Flowchart sederhana (boleh digambar tangan atau digital)  
3. Screenshot hasil running (output)  
4. Penjelasan alur logika program untuk setiap soal dalam **1 paragraf**

**Catatan:**
- Penjelasan boleh ditulis langsung di **dokumen (misalnya Word)** atau dalam bentuk **komentar/markdown pada kode program**.
- Kode program juga boleh ditampilkan dalam bentuk **screenshot per bagian** atau dituliskan langsung di dokumen.
- Format penyusunan **bebas**, yang penting seluruh komponen di atas tersedia dan dikumpulkan dalam **1 file PDF**.
  
Kumpulkan di: https://forms.gle/nk3X1RYpCKSoQJz76

---

# Post-Test Praktikum 2 
Modul: Dasar Python, Percabangan, Perulangan

## Soal 1

Buatlah program Python yang meminta pengguna memasukkan beberapa data melalui keyboard:

- Nama pengguna  
- Umur  
- Tinggi badan (dalam cm)

Program harus melakukan proses berikut:

1. Menampilkan kembali data yang dimasukkan pengguna dengan format yang rapi menggunakan `print()`.
2. Menampilkan **tipe data dari setiap variabel** menggunakan fungsi `type()`.
3. Menggunakan **percabangan (if-elif-else)** untuk menentukan kategori umur dengan ketentuan berikut:
   - Umur < 13 → Anak-anak  
   - Umur 13 – 17 → Remaja  
   - Umur ≥ 18 → Dewasa
4. Menggunakan **operator logika** untuk mengecek apakah pengguna memenuhi syarat berikut:
   - Umur ≥ 18 **dan** tinggi badan ≥ 160 cm

Program harus menampilkan:
- Nama pengguna
- Umur
- Tinggi badan
- Kategori umur
- Hasil pengecekan kondisi logika
- Tipe data dari setiap variabel

---

## Soal 2

Buatlah program Python yang meminta pengguna memasukkan **dua buah bilangan bulat**.

Program kemudian harus menampilkan beberapa operasi matematika berikut:

- Penjumlahan
- Pengurangan
- Perkalian
- Pembagian
- Sisa bagi (modulus)
- Pangkat

Setelah menampilkan hasil operasi tersebut, program harus:

1. Menggunakan **perulangan (`while`)** untuk menanyakan kepada pengguna apakah ingin melakukan perhitungan lagi.
2. Jika pengguna memasukkan **"y"**, maka program akan meminta dua bilangan baru dan melakukan perhitungan kembali.
3. Jika pengguna memasukkan **"n"**, maka program berhenti.

Program juga harus menampilkan **tipe data dari hasil operasi** menggunakan fungsi `type()`.
