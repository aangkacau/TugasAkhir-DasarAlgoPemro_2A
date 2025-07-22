📘 USER MANUAL – APLIKASI INVENTORI DEALER MOTOR
🛠️ 1. Deskripsi Program
Aplikasi ini merupakan program Python sederhana untuk mengelola data inventori dealer motor. Pengguna dapat:

Menambahkan motor baru (dengan kode unik)

Melihat seluruh data motor

Mengedit jumlah stok

Menghapus data motor

Menampilkan laporan stok motor secara terurut

Menyimpan data secara permanen ke file JSON (inventori_dealer.json)

💻 2. Persyaratan Sistem
Python versi 3.6 atau lebih tinggi

Bisa dijalankan di:

VS Code / Terminal (Windows/Linux/macOS)

Google Colab

📂 3. Struktur File
Nama File	Keterangan
inventori_dealer.py	File utama yang berisi seluruh kode program
inventori_dealer.json	File penyimpanan data motor dalam format JSON
user_manual.md	Dokumen panduan penggunaan program ini

▶️ 4. Cara Menjalankan Program
💻 Via Terminal / VS Code
Pastikan Python sudah terpasang

Buka terminal dan jalankan:

bash
Salin
Edit
python inventori_dealer.py
☁️ Via Google Colab
Upload file inventori_dealer.py

Jalankan sel yang memuat program

File inventori_dealer.json akan muncul otomatis di direktori kerja

📋 5. Panduan Menu Program
Saat program dijalankan, akan muncul menu berikut:

text
Salin
Edit
=== Menu Inventori Dealer Motor ===
1. Tambah Motor
2. Lihat Semua Motor
3. Edit Stok
4. Hapus Motor
5. Laporan Stok
6. Simpan & Keluar
No	Menu	Deskripsi
1	Tambah Motor	Menambahkan data motor baru (kode, nama, tahun, warna, stok)
2	Lihat Semua Motor	Menampilkan seluruh motor dan informasi detail
3	Edit Stok	Mengubah stok motor berdasarkan kode
4	Hapus Motor	Menghapus motor dari inventori
5	Laporan Stok	Menampilkan daftar motor berdasarkan stok terbanyak
6	Simpan & Keluar	Menyimpan data ke file JSON dan keluar dari program

🧾 6. Format Input
Field	Format	Contoh
Kode Motor	String tanpa spasi	DLR001
Nama Motor	String bebas	Yamaha Aerox 155
Tahun Motor	Tahun (String/Angka)	2023
Warna Motor	String bebas	Hitam Doff
Jumlah Stok	Angka bulat positif (int)	10

⚙️ 7. Fitur Optimasi & Error Handling
✅ Penanganan file menggunakan with open dan try-except
✅ Optimasi waktu eksekusi dengan time.time()
✅ Komentar jelas dan terstruktur untuk pemahaman kode
✅ Validasi agar kode motor tidak duplikat
✅ Struktur data menggunakan list of dictionary
✅ Siap dikembangkan ke fitur lanjutan seperti pencarian cepat atau ekspor data

📌 8. Catatan Tambahan
Data hanya akan disimpan saat memilih menu "Simpan & Keluar"

Jangan mengedit file JSON secara manual agar data tidak rusak

Jika inventori_dealer.json belum ada, program akan otomatis membuat file baru

💡 Saran Pengembangan (Opsional)
Implementasi pencarian cepat dengan struktur dictionary (O(1))

Validasi input stok agar hanya menerima angka positif

Tambahkan fitur ekspor laporan ke .csv atau .txt

Tambahkan pencarian berdasarkan tahun atau warna
