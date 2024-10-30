# AplikasiPerhitunganHari
 
## Identitas
Nama: Ayu Atut Khofifah

NPM: 2210010553

## Penjelasan Program

**Aplikasi Perhitungan Hari**

Aplikasi ini bertujuan untuk menghitung jumlah hari dalam suatu bulan tertentu dan tahun tertentu yang ditentukan oleh pengguna. Pengguna dapat memilih bulan dan tahun menggunakan antarmuka berbasis GUI. Berikut adalah penjelasan mengenai bagian-bagian dari aplikasi ini:

1. **Deskripsi Program**:
   - Pengguna memilih bulan dari komponen `JComboBox` dan memasukkan tahun menggunakan komponen `JSpinner`.
   - Pengguna juga dapat memilih tanggal spesifik menggunakan `JCalendar`, memberikan fleksibilitas dalam memilih bulan dan tahun.
   - Setelah pengguna menentukan pilihan bulan dan tahun, aplikasi akan menghitung jumlah hari dalam bulan tersebut dan menampilkan hasilnya ketika tombol "Hitung" ditekan.

2. **Komponen GUI**:
   - Aplikasi ini menggunakan berbagai komponen GUI, termasuk `JFrame` untuk jendela utama, `JPanel` sebagai panel penampung komponen, `JLabel` untuk label teks, `JComboBox` untuk pilihan bulan, `JSpinner` untuk input tahun, `JButton` sebagai tombol untuk menghitung, dan `JCalendar` untuk memilih tanggal.

3. **Logika Program**:
   - Logika utama program menggunakan API tanggal `LocalDate` yang memungkinkan aplikasi menghitung jumlah hari dalam bulan yang dipilih, serta mempertimbangkan tahun kabisat jika diperlukan.
   - Aplikasi ini mengkalkulasi jumlah hari dengan memastikan logika pembacaan tanggal dan tahun berjalan sesuai aturan kalender.

4. **Events (Peristiwa)**:
   - Program menggunakan `ActionListener` untuk mendeteksi ketika tombol "Hitung" ditekan, memicu perhitungan hari berdasarkan bulan dan tahun yang dipilih.
   - `ChangeListener` diterapkan pada `JSpinner` untuk memperbarui input tahun secara dinamis saat pengguna melakukan perubahan.

5. **Variasi (Pengembangan Fitur Tambahan)**:
   - Program ini juga dapat menampilkan informasi tambahan, seperti hari pertama dan hari terakhir dalam bulan yang dipilih, memberikan gambaran lebih lengkap kepada pengguna.
   - Terdapat fitur untuk menghitung selisih hari antara dua tanggal yang dipilih, memberikan kemampuan tambahan untuk pengguna yang ingin melakukan perhitungan waktu antara dua periode.
  
## Keungulan Program

1. **Mudah Dipakai**  
   Program ini punya tampilan yang gampang dipahami, jadi semua orang bisa pakai dengan mudah, bahkan yang nggak terlalu paham soal teknologi. Pilih bulan dan tahun dengan gampang, langsung kelihatan hasilnya!

2. **Hitungan yang Akurat**  
   Dengan pakai `LocalDate`, program ini bisa ngitung jumlah hari dengan tepat, termasuk tahun kabisat. Jadi, nggak perlu khawatir hasilnya meleset dari kalender aslinya.

3. **Fleksibel dalam Memasukkan Data**  
   Pengguna bisa pilih bulan lewat `JComboBox`, input tahun dengan `JSpinner`, atau langsung pakai `JCalendar`. Banyak pilihan input ini bikin program lebih fleksibel dan sesuai sama kebutuhan pengguna.

4. **Info Kalender Tambahan**  
   Selain jumlah hari, program ini juga bisa ngasih info hari pertama dan terakhir di bulan yang dipilih. Jadi, pengguna dapat gambaran lengkap soal bulan tersebut, nggak cuma jumlah harinya aja.

5. **Bisa Hitung Selisih Hari**  
   Fitur lain yang keren, program ini bisa hitung selisih hari antara dua tanggal. Jadi, kalau mau tahu jarak waktu antara dua acara atau sekadar ngebandingin dua tanggal, tinggal masukin aja dan hasilnya langsung muncul.

6. **Langsung Responsif Sama Perubahan**  
   Program ini responsif banget! Kalau ada perubahan di input bulan atau tahun, hasilnya langsung diperbarui. Jadi pengguna nggak perlu klik ulang atau reset, hasilnya langsung terlihat secara real-time.

7. **Mudah Dikembangkan**  
   Karena pakai komponen GUI standar kayak `JFrame`, `JPanel`, `JComboBox`, dll., program ini gampang dikembangkan lebih lanjut. Jadi kalau nanti butuh fitur tambahan atau modifikasi, pengembang lain juga bisa ngejarnya tanpa ribet.

## Ini dia Screenshot Programnya

**1.** ![ss an AplikasiPerhitunganHari](https://github.com/user-attachments/assets/8b911d78-75be-4e40-b5f2-d2601f81d7ad)


**2.** ![ss an AplikasiPerhitunganHari2](https://github.com/user-attachments/assets/caf6b60d-dc06-480c-9e8b-55722b69ff27)


**3.** ![ss an AplikasiPerhitunganHari3](https://github.com/user-attachments/assets/28a7ba58-8136-4186-8b6e-0f97f1dd1d5b)


**4.** ![ss an AplikasiPerhitunganHari4](https://github.com/user-attachments/assets/f5ded8de-6339-4b13-a43d-525a426406ac)



