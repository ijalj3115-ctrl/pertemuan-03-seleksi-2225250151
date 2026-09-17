# Pertemuan 03 Seleksi Python

Nama: Rijal Munawarudin  
NIM: 2225250151  
Kelas: 3F  

## Tujuan
Menulis program seleksi if, if-else, kondisi majemuk, dan nested if.

## Cara Menjalankan
Jalankan program melalui terminal VS Code dengan perintah:

```bash
python3 tugas/analisis_persamaan_kuadrat.py
```

## Algoritma Tugas
1. Memasukkan nilai koefisien a, b, dan c.
2. Memeriksa apakah nilai a sama dengan 0.
3. Jika a sama dengan 0, program menampilkan bahwa persamaan bukan persamaan kuadrat.
4. Jika a tidak sama dengan 0, program menghitung diskriminan dengan rumus D = b² - 4ac.
5. Jika D lebih besar dari 0, program menghitung dan menampilkan dua akar real yang berbeda.
6. Jika D sama dengan 0, program menghitung dan menampilkan satu akar real kembar.
7. Jika D kurang dari 0, program menampilkan bahwa persamaan tidak memiliki akar real.

## Hasil Pengujian

| No. | Input (a, b, c) | Keluaran yang Diharapkan | Keluaran Aktual | Status |
|---|---|---|---|---|
| 1 | 1, -3, 2 | Dua akar real berbeda, yaitu 2 dan 1 | Dua akar real berbeda, yaitu 2 dan 1 | Berhasil |
| 2 | 1, -2, 1 | Akar real kembar, yaitu 1 | Akar real kembar, yaitu 1 | Berhasil |
| 3 | 1, 0, 1 | Tidak memiliki akar real | Tidak memiliki akar real | Berhasil |
| 4 | 0, 2, 1 | Bukan persamaan kuadrat | Bukan persamaan kuadrat | Berhasil |

## Refleksi
Kesalahan logika yang dapat terjadi adalah menggunakan kondisi a != 0 untuk menentukan apakah persamaan memiliki akar real. Padahal, nilai a hanya digunakan untuk memastikan bahwa persamaan tersebut merupakan persamaan kuadrat.

Perbaikannya adalah memeriksa nilai a terlebih dahulu. Jika a tidak sama dengan 0, program baru menghitung diskriminan untuk menentukan jenis akar persamaan.