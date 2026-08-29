# TAHU GEJROT RUSH

Mobile-first HTML5 Canvas casual game. Tidak membutuhkan framework atau build step.

## Jalankan lokal
Buka `index.html` di browser. Untuk beberapa browser, lebih stabil jika memakai static server sederhana.

## GitHub Pages
1. Upload seluruh folder ke repository GitHub.
2. Settings → Pages.
3. Source: Deploy from a branch.
4. Pilih branch `main`, folder `/ (root)`.
5. Save.

Game menyimpan High Score di `localStorage` dengan key `tahuRushHigh`.
Audio dibuat dengan Web Audio API sehingga tidak membutuhkan file musik eksternal.
