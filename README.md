# ApkPenghitungKataFrame

Aplikasi ini adalah aplikasi desktop berbasis Java Swing yang berfungsi untuk menghitung jumlah kata, karakter, kalimat, paragraf, serta mencari jumlah kemunculan kata tertentu dalam teks yang dimasukkan oleh pengguna.

## Deskripsi
Aplikasi Penghitung Kata (ApkPenghitungKataFrame) memungkinkan pengguna untuk menghitung berbagai statistik dari teks yang dimasukkan, seperti jumlah kata, karakter, kalimat, paragraf, serta pencarian kata tertentu. Aplikasi ini juga memiliki fitur untuk menyimpan teks dan hasil perhitungan ke dalam file. Aplikasi ini dibangun menggunakan Java Swing dan dapat dijalankan di sistem operasi yang mendukung Java.

## Fitur
- *Penghitungan Statistik Teks*:
  - Jumlah Kata
  - Jumlah Karakter
  - Jumlah Kalimat
  - Jumlah Paragraf

- *Pencarian Kata*:
  - Pengguna dapat mencari kata tertentu di dalam teks, dan aplikasi akan menampilkan jumlah kemunculan kata tersebut.

- *Simpan ke File*:
  - Pengguna dapat menyimpan teks dan hasil perhitungan ke dalam file .txt di lokasi yang dipilih.

- *Pengaturan UI*:
  - Tombol interaktif yang membantu pengguna untuk menghitung, menyimpan, menghapus teks, dan keluar dari aplikasi.

## Keunggulan
- *User-Friendly*: Antarmuka yang sederhana dan mudah digunakan dengan tombol yang terpisah untuk setiap fungsi.
- *Multifungsi*: Selain menghitung kata dan karakter, aplikasi ini juga dapat menghitung kalimat, paragraf, dan kemunculan kata tertentu.
- *Penyimpanan Hasil Perhitungan*: Hasil perhitungan dapat disimpan dalam format .txt, memudahkan pengguna untuk mendokumentasikan hasil analisis teks.
- *Tampilan Responsif*: Menggunakan Java Swing yang responsif di berbagai platform yang mendukung Java.

## Komponen GUI
1. *JFrame*: Komponen utama yang menjadi jendela aplikasi.
2. *JPanel* (jPanel1): Panel utama yang digunakan untuk menampung semua komponen lainnya.
3. *JScrollPane* (jScrollPane1): Panel dengan scrollbar untuk menampung area teks, memungkinkan teks yang panjang dapat di-scroll.
4. *JTextArea* (jTextArea1): Area teks di mana pengguna dapat memasukkan atau menempelkan teks yang ingin dihitung.
5. *JTextField* (jTextField1): Kolom input untuk pengguna memasukkan kata yang ingin dicari di dalam teks.
6. *JLabel*:
   - jLabel1: Label untuk menginstruksikan pengguna mengisi teks di bawah ini.
   - jLabel2: Label untuk menunjukkan tempat pencarian kata tertentu.
   - jLabel3: Label yang menampilkan jumlah kata di teks.
   - jLabel4: Label yang menampilkan jumlah karakter di teks.
   - jLabel5: Label yang menampilkan jumlah kalimat di teks.
   - jLabel6: Label yang menampilkan jumlah paragraf di teks.
   - jLabel7: Label yang menampilkan jumlah kemunculan kata yang dicari.
7. *JButton*:
   - jButton1 ("Hitung Kata"): Tombol untuk menghitung jumlah kata, karakter, kalimat, paragraf, dan hasil pencarian kata tertentu.
   - jButton2 ("Simpan Kata"): Tombol untuk menyimpan teks beserta hasil perhitungan ke dalam file.
   - jButton3 ("Hapus"): Tombol untuk menghapus teks dan mereset semua hasil perhitungan.
   - jButton4 ("Keluar"): Tombol untuk keluar dari aplikasi.

### Tampilan Layout
Komponen-komponen ini diatur dalam *JPanel* menggunakan GroupLayout untuk memberikan tampilan yang terstruktur dan mudah dibaca oleh pengguna. Berikut ini adalah rincian layout-nya:
- *Panel Teks*: jTextArea1 diletakkan dalam jScrollPane1 sehingga teks panjang dapat di-scroll.
- *Panel Pencarian Kata*: jTextField1 dan jLabel2 ditempatkan di bagian atas untuk memudahkan pengguna memasukkan kata yang akan dicari.
- *Panel Hasil*: Label hasil perhitungan (jLabel3 hingga jLabel7) ditempatkan di bawah area teks untuk menampilkan jumlah kata, karakter, kalimat, paragraf, dan hasil pencarian kata.
- *Panel Tombol*: Tombol aksi seperti "Hitung Kata", "Simpan Kata", "Hapus", dan "Keluar" ditempatkan di bawah label hasil untuk memudahkan akses.

Penggunaan *GroupLayout* di dalam *JPanel* (jPanel1) memungkinkan posisi komponen disusun dengan baik dan responsif sesuai ukuran jendela aplikasi.

## Cara Menggunakan
1. *Masukkan Teks*: Ketik atau tempel teks di area JTextArea yang tersedia.
2. *Hitung Statistik*: Klik tombol "Hitung Kata" untuk melihat jumlah kata, karakter, kalimat, paragraf, dan kemunculan kata yang diinput.
3. *Pencarian Kata*: Masukkan kata yang ingin dicari di kolom "Cari Kata", kemudian klik "Hitung Kata".
4. *Simpan Hasil*: Klik "Simpan Kata" untuk menyimpan teks dan hasil perhitungan ke file.
5. *Hapus Teks*: Klik "Hapus" untuk mengosongkan teks dan hasil perhitungan.
6. *Keluar dari Aplikasi*: Klik "Keluar" untuk menutup aplikasi.

## Teknologi yang Digunakan
- Java SE (Swing GUI)
- Java I/O (untuk menyimpan file)



## Struktur Kode
- *initComponents()*: Metode ini menginisialisasi semua komponen GUI.
- *countText()*: Metode untuk menghitung jumlah kata, karakter, kalimat, paragraf, dan pencarian kata tertentu.
- *saveToFile()*: Metode untuk menyimpan teks dan hasil perhitungan ke dalam file .txt.
- *resetLabels()*: Mengatur ulang label hasil perhitungan ketika teks dihapus.

## Pembuat Aplikasi
 willy Rahman 2210010103

## Demo
![Demo GIF](https://github.com/willyrahman/ApkPenghitungKata/blob/main/img/Demo%20penghitungKata%20tugas%205.gif)

