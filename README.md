# Running-Dashboard
Running Dashboard for support runner without coach

Dashboard pribadi untuk mendukung program lari. Satu file HTML, tanpa build.

## Fitur

- **Ringkasan**: hitung mundur race, block yang berjalan, jarak minggu ini (realisasi vs program).
- **Profil & Zona**: data diri dan zona heart rate 1-5 (Karvonen atau persen HR max).
- **Program Lari**: jadwal mingguan yang bisa diubah, dengan target bpm per sesi dan skala volume.
- **Training Block**: fase base, build, peak, taper dengan tanggal mulai.
- **Jadwal Race**: prioritas A/B/C, target waktu, hitung mundur.
- **Strength Training**: sesi dan gerakan yang bisa diubah.
- **Coach AI**: catat latihan dan minta feedback (hanya aktif di dalam Claude).
- **Panduan Zona HR**: penjelasan tiap zona dan faktor yang memengaruhi bacaan HR.

## Menjalankan

Buka `index.html` di browser, atau aktifkan GitHub Pages untuk repo ini.

Di luar Claude, semua data tersimpan di localStorage browser. Menu Coach AI tetap bisa mencatat latihan, tetapi feedback dari coach memerlukan Claude. Untuk coach AI di luar Claude, dibutuhkan backend yang memanggil API dengan API key.

## Catatan

Zona HR memakai HR max estimasi (208 - 0,7 x umur) bila HR max tidak diisi. Feedback coach bukan nasihat medis.
