# Pertemuan 10 - String dan Pengolahan Teks

**Nama:** AKIFAH SALSABILA  
**NIM:** 2225250137 
**Kelas:** 3F

## Tujuan

Mengolah dan menormalisasi data teks menggunakan string Python, termasuk membersihkan spasi, mengubah kapitalisasi, menghitung jumlah kata, membuat inisial, dan menormalkan kode kelas.

## Cara Menjalankan

Pastikan Python sudah terpasang dan terminal berada di folder utama proyek.

Jalankan program tugas dengan perintah:

```bash
python tugas/normalisasi_data_mahasiswa.py
```

Masukkan nama mahasiswa dan kode kelas ketika diminta oleh program.

## Algoritma

Program dimulai dengan menerima input nama mahasiswa dan kode kelas. Nama mahasiswa dibersihkan menggunakan `strip()` dan `split()` untuk menghilangkan spasi berlebih, kemudian dirapikan menggunakan `title()`. Setelah itu, nama dipisahkan menjadi beberapa kata untuk menghitung jumlah kata dan mengambil huruf pertama setiap kata sebagai inisial. Kode kelas diubah menjadi huruf kapital menggunakan `upper()`, lalu setiap bagiannya digabungkan kembali menggunakan `join()` dengan tanda hubung sebagai pemisah. Terakhir, program menampilkan nama bersih, kode kelas, jumlah kata, dan inisial mahasiswa.

## Test Case

| No. | Input Nama | Input Kode Kelas | Hasil yang Diharapkan | Hasil Aktual | Status |
|---|---|---|---|---|---|
| 1 | `aan hendrayana` | `pmat a 2026` | Aan Hendrayana; PMAT-A-2026; 2; AH | Isi setelah diuji | Belum diuji |
| 2 | `fATHIYYAH mUTHMAINNAH` | `kelas b` | Fathiyyah Muthmainnah; KELAS-B; 2; FM | Isi setelah diuji | Belum diuji |
| 3 | `BUDI` | `pmtk 01` | Budi; PMTK-01; 1; B | Isi setelah diuji | Belum diuji |
| 4 | `siti nur aisyah` | `kelas c` | Siti Nur Aisyah; KELAS-C; 3; SNA | Isi setelah diuji | Belum diuji |

## Refleksi

Salah satu masalah yang ditemukan dalam pengolahan teks adalah penulisan nama dan kode kelas yang tidak konsisten, seperti penggunaan huruf besar dan kecil serta spasi berlebih. Masalah tersebut dapat diperbaiki menggunakan method string seperti `strip()`, `split()`, `title()`, dan `upper()`. Dengan normalisasi teks, data menjadi lebih rapi dan mudah digunakan untuk proses selanjutnya.

## Sumber dan Bantuan

Sumber utama: Bahan Ajar Algoritma dan Pemrograman Pertemuan 10, String dan Pengolahan Teks dalam Python.

Bantuan AI: ChatGPT, digunakan untuk membantu memahami instruksi, menyusun kode, dan menjelaskan proses pengerjaan. Kode dan hasil pengujian diperiksa kembali oleh mahasiswa.