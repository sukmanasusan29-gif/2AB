BALAPAN PINTAR 3D — PAKET PWA
Khusus Kelas 2 MIS An Najiyah
Pembuat: Susan Sukmana
Tanpa musik dan tanpa suara.

ISI PAKET
- index.html: game yang bisa dimainkan
- manifest.json: identitas aplikasi PWA
- sw.js: cache dasar untuk penggunaan offline
- icon-192.png dan icon-512.png: ikon aplikasi

CARA MENCOBA DI KOMPUTER
1. Ekstrak ZIP.
2. Buka index.html untuk mencoba game dasar. Instalasi PWA tidak bekerja jika dibuka langsung sebagai file.
3. Untuk PWA, unggah seluruh isi folder ke GitHub repository dan aktifkan GitHub Pages.

CARA UNGGAH KE GITHUB PAGES
1. Masuk ke github.com dan buka repository baru (misalnya balapan-pintar).
2. Pilih Add file > Upload files.
3. Unggah SEMUA file dalam folder ZIP yang sudah diekstrak: index.html, manifest.json, sw.js, icon-192.png, icon-512.png, README.txt.
4. Klik Commit changes.
5. Buka Settings > Pages.
6. Pada Build and deployment, pilih Deploy from a branch.
7. Pilih branch main dan folder /(root), lalu Save.
8. Tunggu hingga GitHub Pages menampilkan alamat website.
9. Buka alamat tersebut di Chrome/Edge HP. Android: menu ⋮ > Install app atau Tambahkan ke layar utama. iPhone: Safari > Share > Add to Home Screen.

CATATAN PENTING
- Instalasi PWA memerlukan HTTPS atau localhost. Jangan menguji instalasi dengan membuka index.html langsung.
- Game ini merupakan versi awal 3D-rasa/visual perspektif menggunakan CSS, bukan engine 3D penuh seperti Unity. Mekanik, tampilan, dan kompatibilitas perangkat perlu diuji setelah diunggah.
- Offline cache hanya berlaku setelah game dibuka online dan service worker berhasil aktif.
- Progres disimpan lokal di browser perangkat dan tidak otomatis tersinkron antarperangkat.
- Semua permainan tanpa musik dan suara.
