---

# Aplikasi Perhitungan Diskon

Aplikasi Perhitungan Diskon adalah sebuah program berbasis Java Swing yang digunakan untuk menghitung harga akhir setelah diskon dan jumlah penghematan dari harga asli. Program ini dirancang untuk mempermudah pengguna dalam melakukan perhitungan diskon dengan cepat dan efisien.

## Fitur Utama
- Input harga asli oleh pengguna.
- Pilih persentase diskon melalui **JComboBox** atau **JSlider**.
- Menampilkan hasil berupa harga akhir dan jumlah penghematan.
- Proses perhitungan berjalan otomatis tanpa menekan tombol "Hitung" apabila:
  - Input harga awal telah diisi.
  - Nilai diskon dipilih melalui **JComboBox** atau **JSlider**.
- Dukungan untuk memasukkan kode kupon diskon tambahan.
- Riwayat perhitungan diskon untuk melacak semua perhitungan yang telah dilakukan.

## Komponen GUI
- **JFrame**: Frame utama aplikasi.
- **JPanel**: Panel untuk mengelompokkan elemen GUI.
- **JLabel**: Label untuk teks keterangan.
- **JTextField**: Input field untuk harga asli.
- **JComboBox**: Dropdown untuk memilih persentase diskon.
- **JButton**: Tombol untuk menghitung (opsional, hanya sebagai cadangan jika input otomatis tidak digunakan).
- **JSlider**: Alternatif untuk memilih persentase diskon.

## Logika Program
Program menggunakan logika perhitungan aritmatika sederhana untuk menghitung harga akhir dan jumlah penghematan. Penanganan kesalahan juga diterapkan untuk memastikan input valid, misalnya, jika pengguna memasukkan karakter non-numerik di bidang harga asli.

## Event Handling
- **ActionListener** untuk tombol "Hitung".
- **ItemListener** pada **JComboBox** untuk mendeteksi perubahan pilihan persentase diskon.
- Perhitungan otomatis akan berjalan jika input harga awal dan nilai diskon telah diisi.

## Cara Menggunakan
1. Masukkan harga asli di kolom yang tersedia.
2. Pilih persentase diskon menggunakan **JComboBox** atau **JSlider**.
3. Hasil perhitungan akan langsung ditampilkan tanpa perlu menekan tombol "Hitung".
4. Untuk menambahkan kupon diskon, masukkan kodenya di bagian khusus (jika tersedia).
5. Riwayat perhitungan dapat dilihat pada panel riwayat.

## Variasi dan Pengembangan
- **Input kode kupon diskon tambahan** untuk memperbesar diskon.
- **JSlider** sebagai alternatif pemilihan persentase diskon.
- **Riwayat perhitungan diskon** untuk melacak penggunaan aplikasi.

## Teknologi yang Digunakan
- Java
- Java Swing

## Cara Menjalankan
1. Clone repository ini.
2. Import proyek ke dalam IDE yang mendukung Java (NetBeans, IntelliJ, Eclipse).
3. Jalankan file utama yang menginisialisasi JFrame aplikasi.

## Kontribusi
Silakan buka Pull Request untuk memberikan kontribusi. Pastikan untuk membuat issue terlebih dahulu jika Anda memiliki ide atau menemukan bug.

---