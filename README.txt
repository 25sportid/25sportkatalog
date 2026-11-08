PAKET SETUP DECAP CMS UNTUK 25SPORT

Isi:
- index.html: website katalog membaca data produk dari data/products.json
- admin/index.html: antarmuka Decap CMS
- admin/config.yml: konfigurasi Decap CMS untuk repository 25sportid/25sportkatalog branch main
- data/products.json: katalog 6 produk awal
- images/uploads/.gitkeep: folder untuk gambar upload CMS

Cara pasang:
1. Ekstrak ZIP ini di PC.
2. Buka repository GitHub 25sportid/25sportkatalog.
3. Upload isi folder paket ke root repository (admin, data, images, index.html, README).
4. Jika diminta replace index.html yang lama, pilih replace.
5. Commit changes pada branch main.
6. Tunggu deploy Netlify status Published.
7. Buka https://25sport.netlify.app/admin/

Pengguna CMS login dengan akun GitHub yang punya akses write ke repository.
Jangan upload Client Secret ke GitHub.
