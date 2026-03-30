# Tugas Jurnal Praktikum 3 – Fungsi Pyhton
## Format Pengumpulan
File dikumpulkan dalam 1 dokumen PDF yang berisi:

Kode program
1. Flowchart sederhana (boleh digambar tangan atau digital)
2. Screenshot hasil running (output)
3. Penjelasan alur logika program untuk setiap soal dalam 1 paragraf
4. Deadline : 30/03/2026 23.59 WIB

Catatan:

- Penjelasan boleh ditulis langsung di dokumen (misalnya Word) atau dalam bentuk komentar/markdown pada kode program (pdf ipynb).
- Kode program juga boleh ditampilkan dalam bentuk screenshot per bagian atau dituliskan langsung di dokumen.
- Format penyusunan bebas, yang penting seluruh komponen di atas tersedia dan dikumpulkan dalam 1 file PDF.

Kumpulkan di: https: https://drive.google.com/drive/folders/12rtzzzJIC_cja7sfBPdIs6MKFWWiVTgS?usp=sharing

# Soal 1

Buatlah sebuah **prosedur** bernama `nilai_mahasiswa` dengan parameter:
- `nama`
- `*nilai`
- `kkm` *(default = 75)*

---

## Ketentuan
Prosedur harus:
1. Menampilkan **nama mahasiswa**
2. Menampilkan **semua nilai**
3. Menghitung **rata-rata nilai**
4. Menampilkan **status**:
   - `"Lulus"` jika rata-rata ≥ kkm
   - `"Tidak Lulus"` jika rata-rata < kkm

---

## Contoh Pemanggilan
```python
nilai_mahasiswa("Budi", 80, 70, 90)
nilai_mahasiswa("Siti", 60, 65, 70, kkm=70)
```

# Soal 2 – Lambda Function

Buatlah sebuah **fungsi lambda** bernama `kategori_nilai` yang menerima satu parameter `nilai`.

---

## Ketentuan
Fungsi harus mengembalikan:
- `"A"` jika nilai ≥ 80
- `"B"` jika 70 ≤ nilai < 80
- `"C"` jika 60 ≤ nilai < 70
- `"D"` jika nilai < 60

> Gunakan **lambda** (bukan `def`) dan **if-else dalam satu baris**.

---

## Contoh Penggunaan
```python
print(kategori_nilai(85))
print(kategori_nilai(75))
print(kategori_nilai(65))
print(kategori_nilai(50))
```

Keterangan: tidak perlu dikumpulkan di drive jika di presentasikan saat jam praktikum
