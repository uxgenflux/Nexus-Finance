# Nexus Finance

Aplikasi manajemen keuangan pribadi (HTML, CSS, JavaScript murni, tanpa build step).

## Deploy ke GitHub Pages

1. Buat repository baru di GitHub (mis. `nexus-finance`).
2. Upload **isi** zip ini (bukan folder pembungkusnya) ke root repository, sehingga `index.html` berada di root.
3. Buka **Settings > Pages**.
4. Pada **Build and deployment**, pilih **Deploy from a branch**, branch `main`, folder `/ (root)`, lalu **Save**.
5. Tunggu 1-2 menit. Situs tersedia di `https://<username>.github.io/nexus-finance/`.

## Catatan

- Data disimpan di `localStorage` browser, jadi tersimpan per perangkat dan per domain. Mengganti domain atau menghapus data browser akan mengosongkan data.
- Ikon ada di root repository: `apple-touch-icon.png` (180 px, iOS), `icon-192.png` dan `icon-512.png` (Android/PWA), serta `icon-maskable-512.png`. Konfigurasi aplikasi ada di `manifest.json`.
- Untuk memasang di beranda: iPhone lewat Safari > Bagikan > Tambah ke Layar Utama; Android lewat Chrome > menu > Instal aplikasi / Tambahkan ke layar utama. Jika sebelumnya sudah ditambahkan, hapus shortcut lama dulu.
