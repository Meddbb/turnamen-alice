# Deployment ke GitHub Pages

Langkah singkat untuk menampilkan situs ini di GitHub Pages:

1. Buat repository GitHub dan beri nama sesuai kebutuhan:
   - Untuk situs user/organization root: `USERNAME.github.io` (ganti USERNAME).
   - Atau nama repo bebas (hasilnya: `https://USERNAME.github.io/REPO`).

2. Di lokal (pada folder project ini), jalankan:

```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/USERNAME/REPO.git
git push -u origin main
```

3. Setelah push, workflow GitHub Actions akan otomatis menjalankan dan menerbitkan ke Pages.

4. URL yang tersedia:
   - Jika repo bernama `USERNAME.github.io` → `https://USERNAME.github.io`
   - Jika repo lain → `https://USERNAME.github.io/REPO`

Catatan:
- File `index.html` dan folder `img/` sudah ada di root; workflow akan menerbitkan konten root.
- Jika Anda ingin saya membantu menjalankan `git init` dan melakukan push, berikan URL repository atau beri saya izin.
