EDULEARN — APK ANDROID

Isi paket ini:
- Project Android siap-build
- EduLearn PWA di app/src/main/assets
- Workflow GitHub Actions untuk membangun APK otomatis
- Landing page download di landing/index.html

CARA PALING MUDAH (TANPA GOOGLE PLAY):
1. Buat repository GitHub baru, misalnya edulearn.
2. Upload SEMUA isi folder paket ini ke repository.
3. Buka tab Actions -> Build EduLearn APK -> Run workflow.
4. Setelah selesai, buka hasil workflow -> Artifacts -> EduLearn-APK.
5. Download ZIP artifact, ekstrak, ambil app-debug.apk.
6. Kirim APK itu ke HP Android dan install.

CATATAN:
- APK debug ini untuk instal langsung/testing, bukan Play Store.
- Untuk link download publik, upload app-debug.apk ke hosting/repository release dan ubah tombol landing/index.html agar menunjuk ke file APK tersebut.
