DM Gadai Android App - WebView wrapper project
=============================================

Ini adalah project Android Studio minimal yang membungkus situs web kamu di dalam sebuah WebView.
Ikuti langkah-langkah berikut untuk menghasilkan APK:

1. Upload situs kamu (file HTML/CSS/JS) ke hosting dan catat URL-nya (misal: https://dmgadai.example.com).
2. Buka file `app/src/main/java/.../MainActivity.kt` dan ganti webView.loadUrl("https://example.com/") dengan URL situs kamu.
3. Buka project ini di Android Studio (File > Open > pilih folder project ini).
4. Sinkronkan Gradle jika diminta. Jika belum punya SDK, instal komponen yang diminta.
5. Pilih Build > Build Bundle(s) / APK(s) > Build APK(s).
6. Setelah selesai, klik link di notif untuk menemukan APK debug di `app/build/outputs/apk/debug/app-debug.apk`.
7. Untuk publish ke Play Store, pelajari cara menandatangani APK dan membuat release build (release signing).

Catatan:
- Pastikan situs menggunakan HTTPS (sertifikat valid) agar WebView tidak memblokir konten.
- Jika ingin tombol WA membuka aplikasi WhatsApp, link wa.me yang ada di situs akan bekerja.
- Saya sudah menyertakan file logo (logo.jpg) di folder `app/src/main/res/raw/` untuk kemudahan; silakan gunakan sebagai ikon adaptif via Android Studio.
- 
