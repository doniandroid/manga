# Komik Indo (APK)

Aplikasi web `www/index.html` dibungkus dengan Capacitor dan di-build menjadi APK lewat GitHub Actions.

## Cara build
1. Upload semua isi folder ini ke repository GitHub (branch `main`).
2. Buka tab **Actions** -> workflow **Build APK** akan jalan otomatis (atau klik **Run workflow**).
3. Setelah selesai (± 5-8 menit), buka run tersebut -> **Artifacts** -> unduh `komik-indo-apk` (zip berisi `komik-indo.apk`).
4. Ekstrak, pindahkan ke HP, lalu install (izinkan "Install dari sumber tidak dikenal").

## Rilis permanen
Buat tag, misalnya `git tag v1.0.0 && git push origin v1.0.0`, maka APK otomatis muncul di tab **Releases**.

## Update aplikasi
Edit `www/index.html`, commit, push. APK baru dibuild otomatis.
