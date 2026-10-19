Komik Indo - proyek Android (WebView)

CARA 1: GitHub Actions (tanpa install apa pun)
1. Buat akun & repositori baru di github.com (boleh Private).
2. Unggah SEMUA isi folder ini ke repositori (termasuk folder .github).
3. Buka tab "Actions". Build jalan otomatis (atau klik "Build APK" > "Run workflow").
4. Setelah centang hijau, buka run tersebut > bagian "Artifacts" > unduh "KomikIndo-apk".
5. Ekstrak zip hasil unduhan, kirim app-debug.apk ke HP, lalu pasang
   (izinkan "Install dari sumber tidak dikenal").

CARA 2: Android Studio
Open folder ini > Build > Build APK(s).
APK: app/build/outputs/apk/debug/app-debug.apk

Isi aplikasi ada di app/src/main/assets/index.html
