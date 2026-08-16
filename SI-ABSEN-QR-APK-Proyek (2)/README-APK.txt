SI-ABSEN QR - APK ANDROID

Tujuan:
APK ini adalah pembungkus Android untuk aplikasi web SI-ABSEN QR SMP Negeri Hubakma.
Alamat web yang dibuka:
https://absenhubakma.github.io/si-absen-qr-hubakma/

Fitur:
- Membuka aplikasi SI-ABSEN QR dalam WebView.
- Meminta izin kamera Android.
- Mendukung kamera untuk scan QR melalui halaman web.
- Data tetap diproses oleh backend Google Apps Script/Google Sheets yang sekarang.
- Tidak mengubah database atau log absensi.

CARA MEMBUAT APK MELALUI GITHUB ACTIONS:
1. Upload seluruh isi folder proyek ini ke repository GitHub.
2. Pastikan file index.html aplikasi web tetap ada jika repository yang sama juga digunakan untuk GitHub Pages.
3. Buka tab Actions.
4. Jalankan workflow "Build SI-ABSEN QR APK".
5. Setelah selesai, buka hasil workflow dan bagian Artifacts.
6. Download "SI-ABSEN-QR-debug".
7. Ekstrak ZIP dan install app-debug.apk pada Android.

CATATAN:
- APK debug cocok untuk pengujian internal.
- Android mungkin meminta izin instalasi dari sumber yang tidak dikenal.
- APK ini memerlukan internet karena aplikasi tetap terhubung ke backend/web yang sekarang.
