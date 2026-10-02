DOTОUS V2 — Final Revision

Domain:
- CNAME: dotous.my.id

Revisi utama:
- Splash screen premium dengan logo Dotous yang sama.
- Logo yang sama dipakai untuk header, favicon, PWA 192, PWA 512, dan icon.png.
- PWA standalone dengan nama Dotous.
- Pilih Random memiliki 2 tab: Pilihan dan Spinner.
- Pilihan tersimpan di localStorage, tidak hilang saat pindah/refresh/keluar-masuk.
- Hapus pilihan satu per satu dengan tombol silang.
- Tombol Ulangi untuk reset pilihan dan hasil.
- Hasil Pilih Random tetap tersimpan.
- Spinner menyimpan pilihan dan hasil.
- Hasil Spinner tidak langsung hilang setelah spin.
- Setelah spin muncul popup dengan pilihan Hapus atau Batalkan.
- Service worker diperbarui untuk loading cepat, offline fallback, update otomatis, dan pembersihan cache versi lama.
- Tidak memakai library eksternal sehingga bundle tetap ringan.

Catatan:
- URL navigasi internal tetap memakai history/hash seperti versi project saat ini.
- CNAME siap untuk GitHub Pages custom domain.
