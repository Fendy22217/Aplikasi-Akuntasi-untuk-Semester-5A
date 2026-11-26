# Apotek Accounting — Universitas Kadiri

**PROTOTIPE PERKULIAHAN — Mata Kuliah Manajemen Farmasi — Farmasi Kelas A**

Aplikasi web sederhana untuk simulasi pencatatan akuntansi apotek. Dibangun dengan HTML, CSS, dan JavaScript murni agar mudah dipublikasikan melalui GitHub Pages.

## Menjalankan lokal
Buka `index.html` menggunakan browser modern.

## Publikasi melalui GitHub Pages
1. Buat repository GitHub bernama `apotek-accounting`.
2. Unggah `index.html` dan `README.md` ke root repository.
3. Buka **Settings → Pages**.
4. Pada **Build and deployment**, pilih **Deploy from a branch**.
5. Pilih branch `main`, folder `/(root)`, lalu klik **Save**.
6. Tunggu proses publikasi. URL biasanya `https://USERNAME.github.io/apotek-accounting/`.

## Fitur
- Dashboard aset, liabilitas, ekuitas, dan laba/rugi.
- Input transaksi dengan jurnal debit-kredit otomatis.
- Jurnal umum, buku besar, neraca saldo.
- Laporan laba rugi dan laporan posisi keuangan.
- Ekspor daftar transaksi dan jurnal ke CSV.
- Cetak laporan / simpan sebagai PDF melalui dialog cetak browser.
- Data tersimpan pada localStorage browser yang digunakan.

## Jenis transaksi yang didukung
Setoran modal, saldo awal persediaan, pembelian tunai/kredit, penjualan tunai/kredit (dengan HPP), penerimaan piutang, pembayaran utang, beban operasional, prive, dan pendapatan lain-lain.

## Batasan prototipe
- Data hanya tersimpan di browser/perangkat yang digunakan; belum ada database server, login, multi-user, atau sinkronisasi.
- Gunakan data simulasi. Jangan masukkan data pasien atau data sensitif.
- Belum menangani PPN/pajak, retur, diskon, penyusutan, penyesuaian stok, metode FIFO/average, dan tutup buku.
- Saldo awal persediaan dicatat sebagai kontribusi modal dalam versi ini. Sesuaikan dengan skenario pembelajaran.
- Untuk pembukuan operasional nyata, perlu validasi akuntan dan penyesuaian terhadap kebijakan akuntansi serta regulasi yang berlaku.
