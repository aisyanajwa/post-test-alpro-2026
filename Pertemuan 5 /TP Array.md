# Tugas Pendahuluan Praktikum 5 – Rekursif

## Format Pengumpulan
File dikumpulkan dalam 1 dokumen PDF yang berisi:

Kode program
1. Flowchart sederhana (boleh digambar tangan atau digital)
2. Screenshot hasil running (output)
3. Penjelasan alur logika program untuk setiap soal dalam 1 paragraf
4. Deadline : 06/04/2026 08.00 WIB

Catatan:

- Penjelasan boleh ditulis langsung di dokumen (misalnya Word) atau dalam bentuk komentar/markdown pada kode program (pdf ipynb).
- Kode program juga boleh ditampilkan dalam bentuk screenshot per bagian atau dituliskan langsung di dokumen.
- Format penyusunan bebas, yang penting seluruh komponen di atas tersedia dan dikumpulkan dalam 1 file PDF.

Kumpulkan di: https://drive.google.com/drive/folders/1R2S7G08tBNEGRFZzoTPBKLhWPzDe5Jxd?usp=sharing

# Studi Kasus: Penataan Dagangan Buah

## Deskripsi
Bu Surti adalah seorang penjual buah. Ia menata dagangannya secara **horizontal (menyamping)** berdasarkan jenis buah.

Dalam suatu hari, Bu Surti ingin mengubah susunan dagangannya menjadi **vertical (ke bawah)** agar lebih rapi dan mudah dilihat pembeli.

---

## Contoh Data Awal (Horizontal)

```python
buah = [
    ["Apel", "Apel", "Apel", "Apel", "Apel", "Apel", "Apel"],
    ["Melon", "Melon", "Melon", "Melon", "Melon", "Melon", "Melon"],
    ["Pisang", "Pisang", "Pisang", "Pisang", "Pisang", "Pisang", "Pisang"],
    ["Jeruk", "Jeruk", "Jeruk", "Jeruk", "Jeruk", "Jeruk", "Jeruk"],
    ["Nanas", "Nanas", "Nanas", "Nanas", "Nanas", "Nanas", "Nanas"]
]```

Menjadi : 

```python
buah = [
    ["Apel", "Melon", "Pisang", "Jeruk", "Nanas"],
    ["Apel", "Melon", "Pisang", "Jeruk", "Nanas"],
    ["Apel", "Melon", "Pisang", "Jeruk", "Nanas"],
    ["Apel", "Melon", "Pisang", "Jeruk", "Nanas"],
    ["Apel", "Melon", "Pisang", "Jeruk", "Nanas"],
    ["Apel", "Melon", "Pisang", "Jeruk", "Nanas"],
    ["Apel", "Melon", "Pisang", "Jeruk", "Nanas"]
]```
