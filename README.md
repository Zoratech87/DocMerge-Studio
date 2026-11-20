# 📄 DocMerge Studio

**DocMerge Studio** adalah aplikasi web statis (*client-side*) untuk menggabungkan berbagai dokumen (**PDF, Gambar, dan Teks**) menjadi satu file **PDF multi-halaman** atau **Gambar Panjang (.PNG)** lengkap dengan **keterangan gambar otomatis**.

## ✨ Fitur Utama
- **Keterangan Gambar Otomatis**: Tambahkan deskripsi pada setiap gambar (`JPG`, `PNG`, `WEBP`) dan teks akan otomatis dicetak rapi di atas atau di bawah gambar pada hasil akhir.
- **Pilihan Output Fleksibel**: Simpan hasil penggabungan sebagai **Dokumen PDF (`.pdf`)** atau **Gambar Panjang (`.png`)**.
- **Atur Urutan Mudah**: Mendukung *drag-and-drop* serta tombol naik/turun yang ramah pengguna ponsel (*mobile-friendly*).
- **100% Privat & Aman**: Seluruh proses dijalankan langsung di browser menggunakan `pdf-lib` dan `PDF.js` tanpa mengunggah file ke server mana pun.

## 🚀 Cara Hosting di GitHub Pages
1. Buat repositori baru di GitHub (misalnya `docmerge-studio`).
2. Unggah file `index.html` dan `README.md` ke cabang `main`.
3. Buka menu **Settings** > **Pages** di repositori GitHub Anda.
4. Pada bagian **Build and deployment**, pilih **Source: Deploy from a branch**, lalu pilih cabang **`main`** dan folder **`/ (root)`**, kemudian klik **Save**.
5. Tunggu 1–2 menit, aplikasi Anda akan aktif di `https://<username-anda>.github.io/docmerge-studio/`.
