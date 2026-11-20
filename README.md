# Pooly Bloom

Pooly Bloom adalah aplikasi statis HTML, CSS, dan JavaScript. Aplikasi tidak memakai PHP atau MySQL. Data disimpan di `localStorage` browser yang digunakan.

## Menjalankan aplikasi

- Buka `index.html` langsung di browser, atau letakkan folder proyek di `htdocs` dan buka `http://localhost/PoolyEl/` melalui Apache XAMPP. MySQL tidak perlu dinyalakan.
- Login awal: **admin** / **Bloom@12345**. Ganti kata sandi melalui menu Pengaturan.
- Data hanya tersedia di browser/perangkat tersebut. Gunakan **Pengaturan → Unduh backup JSON** untuk mencadangkan; impor file itu untuk memulihkan atau memindahkan data.

## Periode dan perhitungan

Satu siklus berjalan dari tanggal 23 hingga tanggal 22 berikutnya; tanggal gajian adalah 22. Pemasukan kotor menjumlahkan harga pesanan non-cancel, kas/modal buket menjumlahkan modal pesanan, untung bersih adalah pemasukan kotor dikurangi modal, dan pembayaran diterima menjumlahkan DP serta pelunasan yang tercatat pada siklus.

## Fitur

- Pesanan katalog atau custom, DP/pelunasan, dan perubahan status.
- Data produk dengan foto, harga jual, dan modal yang dapat diedit.
- Resep per bunga dengan foto, jumlah bulu kawat, dan putik.
- Inventaris bahan dan alat dengan form ringkas.
- Dashboard, keuangan, laporan per siklus, CSV, cetak, serta backup/impor JSON.

Foto dikompres di browser dan disimpan sebagai data lokal. Gunakan backup secara rutin agar data tidak hilang saat data browser dibersihkan.
