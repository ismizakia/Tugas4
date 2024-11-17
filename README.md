## Identitas
- Nama  : Ismi Zakia
- NPM  : 2210010020
- Kelas  : 5B Non Reguler Banjarmasin

# PenghitungHari

**PenghitungHari** adalah aplikasi Java berbasis GUI yang digunakan untuk menghitung jumlah hari dalam suatu bulan pada tahun tertentu. Aplikasi ini memungkinkan pengguna untuk memilih bulan dan tahun, kemudian menampilkan jumlah hari pada bulan tersebut.

## Fitur

- **Pemilihan Bulan**: Pengguna dapat memilih bulan dari daftar combo box.
- **Pemilihan Tahun**: Pengguna dapat memilih tahun dengan menggunakan spinner.
- **Perhitungan Jumlah Hari**: Setelah memilih bulan dan tahun, pengguna dapat menekan tombol **Hitung** untuk melihat jumlah hari pada bulan tersebut.
- **Hasil Perhitungan**: Aplikasi akan menampilkan jumlah hari di bulan yang dipilih pada label hasil.

## Prasyarat

- **Java Development Kit (JDK)** versi 8 atau lebih baru.
- IDE seperti NetBeans, IntelliJ, atau Eclipse yang mendukung pengembangan aplikasi GUI berbasis Java Swing.

## Cara Menjalankan

1. **Kloning atau Unduh Proyek**:
   - Kloning repositori ini atau unduh file `.java`.
   
2. **Kompilasi dan Jalankan Program**:
   - Di terminal:
     ```bash
     javac PenghitungHari.java
     java PenghitungHari
     ```
   - Atau buka menggunakan IDE seperti NetBeans atau IntelliJ dan jalankan proyek.

## Struktur Antarmuka Pengguna

1. **ComboBox Bulan**:
   - Memilih bulan yang ingin dihitung jumlah harinya (Januari - Desember).
   
2. **Spinner Tahun**:
   - Memilih tahun yang diinginkan untuk menghitung jumlah hari pada bulan tersebut.
   
3. **Tombol Hitung**:
   - Menekan tombol ini untuk menghitung jumlah hari di bulan dan tahun yang dipilih.
   
4. **Label Hasil**:
   - Menampilkan hasil perhitungan jumlah hari.

## Logika Perhitungan

- Program menggunakan **Java LocalDate** untuk menghitung jumlah hari dalam bulan yang dipilih:
  1. Pengguna memilih bulan dan tahun.
  2. Aplikasi membuat objek `LocalDate` untuk tanggal pertama bulan yang dipilih pada tahun yang ditentukan.
  3. Aplikasi kemudian menggunakan metode `lengthOfMonth()` untuk mendapatkan jumlah hari dalam bulan tersebut.

## Contoh Penggunaan

1. Jalankan aplikasi.
2. Pilih bulan dari **ComboBox**.
3. Pilih tahun menggunakan **Spinner**.
4. Klik tombol **Hitung**.
5. Lihat hasil jumlah hari pada bulan yang dipilih ditampilkan di **Label Hasil**.

## Catatan Tambahan

- Aplikasi menggunakan **Swing** untuk membuat antarmuka grafis pengguna.
- Pastikan **tahun** yang dimasukkan valid dan sesuai dengan kalender yang berlaku.
