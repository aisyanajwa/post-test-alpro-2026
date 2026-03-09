# Tugas Pendahuluan Praktikum 3 – Fungsi Python

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
  
Kumpulkan di: https://bit.ly/Pengumpulan_TP_0502

---

# Soal 1
Buatlah fungsi dalam Python untuk menghitung **total harga belanja** berdasarkan harga barang dan jumlah barang.  
Jika total belanja **lebih dari atau sama dengan 100000**, maka pembeli mendapatkan **diskon 10%**.

## Flowchart
*(Letakkan gambar flowchart di sini)*

## Kode Program
```python
def hitung_total(harga, jumlah):
    total = harga * jumlah
    
    if total >= 100000:
        total = total - (0.1 * total)
        
    return total

harga = int(input("Masukkan harga barang: "))
jumlah = int(input("Masukkan jumlah barang: "))

hasil = hitung_total(harga, jumlah)

print("Total pembayaran:", int(hasil))
