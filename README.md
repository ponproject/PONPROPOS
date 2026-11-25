🛍️ PONPRO POS — Minimalist Retail, Event & Stock Opname POS

PONPRO POS adalah aplikasi Point of Sale (POS) berbasis web dalam satu file ringan (zero-backend / single-file HTML) yang dirancang khusus untuk pameran, pop-up booth, bazar, dan toko retail fashion/apparel.

Dilengkapi antarmuka minimalis bergaya Monochrome & Aurora Glassmorphism, aplikasi ini langsung berjalan di iPad, tablet, laptop, maupun desktop tanpa perlu instalasi server atau database rumit.

🌐 Live Demo / Akses Aplikasi

🚀 Buka Aplikasi Online: https://ponpropos.netlify.app

✨ Fitur Utama

⚡ Kasir Cepat Mode 1-Baris (Compact Row POS)

Pencarian instan berdasarkan nama artikel atau ukuran (size).

Tampilan 1 baris per artikel dengan tombol pilihan size berwarna kontras (XS, S, M, L, XL, XXL, All Size) beserta indikator sisa stok real-time.

Setiap transaksi otomatis mengurangi sisa stok varian terkait.

⏳ Pending Transaction (Bayar Nanti)

Simpan antrean pesanan sementara beserta catatan nama pembeli agar kasir dapat melayani pelanggan berikutnya tanpa hambatan.

💸 Diskon Nominal & Metode Pembayaran Fleksibel

Input diskon nominal dengan tombol pilihan cepat (preset) yang dapat dikustomisasi dan disimpan otomatis (auto-save).

Mendukung metode pembayaran Cash (lengkap dengan kalkulator kembalian otomatis), QRIS, dan PayNow.

🌍 Multi-Currency Tanpa Konversi Kurs (IDR / SGD / MYR)

Ubah mata uang aktif langsung dari menu Pengaturan (Rp, S$, RM) mengikuti nilai angka asli di database barang.

📊 Cek Stok & Dropdown SKU Menipis / Habis

Kartu ringkasan Glassmorphism Aurora untuk memantau total artikel, total unit tersedia, serta daftar rincian dropdown untuk varian yang menipis (≤ 3 pcs) maupun habis (0 pcs).

📋 Stok Opname & Sinkronisasi Excel (.xlsx / .csv)

Upload database stok dari Excel dengan format kolom: Nama Artikel, Size, Sisa Stok, Harga HPP, Harga Jual.

Input stok fisik riil pada tabel Stok Opname untuk langsung menyesuaikan stok sistem beserta log riwayat selisih.

📈 Laporan Penjualan, Filter Tanggal & Watermarked PNG

Pantau total barang terjual, omzet kotor & bersih, akumulasi modal (HPP), serta profit bersih baik secara Semua Hari maupun Per Tanggal Tertentu menggunakan Date Picker.

Export Excel (.xlsx) dan Bagikan Laporan PNG beresolusi tinggi lengkap dengan watermark resmi toko.

🧾 Custom Store Profile & Kirim Nota Digital

Atur nama toko, nomor HP/WA, email, alamat, dan catatan kaki resi. Kirim nota pembelian langsung ke WhatsApp atau Email pembeli.

📁 Struktur Repositori

ponpro-pos/
├── index.html          # File utama aplikasi kasir PONPRO POS
├── promo.html          # (Opsional) Video perkenalan motion graphics rasio 9:16
└── README.md           # Dokumentasi repositori


💡 Catatan Penyimpanan Data

Seluruh data barang, riwayat transaksi, pengaturan toko, dan pesanan tertunda tersimpan secara lokal di browser perangkat kasir menggunakan localStorage.

Pastikan menggunakan browser dan perangkat yang sama selama acara/pameran berlangsung, serta lakukan Backup Excel secara berkala melalui menu Laporan atau Pengaturan.

☕ Dukung Pengembangan

Jika aplikasi ini membantu operasional toko atau pameran Anda, dukung pengembangan PONPRO POS melalui:
👉 https://saweria.co/ponproject
