# IDOYSTORE – Premium Jastip

Halaman pesan jastip. Pesanan dikirim langsung ke WhatsApp.

## Isi
- `index.html`: seluruh halaman (foto sudah tertanam, tidak perlu folder gambar)
- `.nojekyll`: supaya GitHub Pages menampilkan file apa adanya

## Deploy ke GitHub Pages
1. Buat repository baru di GitHub (misalnya `idoystore`), set **Public**.
2. Klik **Add file → Upload files**, unggah `index.html`, `.nojekyll`, dan `README.md`, lalu **Commit changes**.
3. Buka **Settings → Pages**.
4. Di **Build and deployment**, pilih **Deploy from a branch**, branch `main`, folder `/ (root)`, lalu **Save**.
5. Tunggu 1–2 menit. Alamat situs: `https://USERNAME.github.io/idoystore/`

## Mengubah isi
- Nomor WhatsApp: ubah `WA_NUMBER` di dalam `index.html` (format 62, tanpa + atau 0 di depan).
- Barang yang bisa dipesan: daftar `products`.
- Koleksi mewah (tidak bisa diklik): daftar `luxury`.
