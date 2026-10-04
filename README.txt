RESPIRALAB — MPI IPA KELAS VIII
Pembaruan simulasi ilmiah & UI/UX: 5 Oktober 2026

PEMBARUAN IDENTITAS DAN AUDIO
- Layar nama/kelas hanya menampilkan Vero, dengan kartu ringkas dan tombol lanjut langsung di bawah isian.
- Musik latar musik_latar_lab_respira.mp3 disertakan dan diputar berulang setelah interaksi masuk.
- Tombol pengaturan suara tersedia pada cover, halaman belajar dan apersepsi.
- Musik dan SFX memiliki sakelar aktif/nonaktif serta volume 0–100% masing-masing.
- Volume awal: musik 25%, SFX 50%. Pilihan tersimpan otomatis di browser.
- Musik tetap berjalan saat berpindah halaman dan dijeda saat tab tidak aktif.
- Jika browser belum mengizinkan audio, buka pengaturan suara lalu tekan Jalankan musik.
- Versi single-file menyertakan MP3 secara internal; tidak perlu file musik terpisah.

PEMBARUAN MINI GAME
- Menu game kini menjadi hub Misi RespiraLab: Misteri Alveolus, Detektif Kelas Sehat, Ekspedisi Jalur Udara.
- Masing-masing memiliki 3 misi (total 9), dialog cinematic Vero/Reska/Oxy-bot, petunjuk dan umpan balik visual.
- Reska pada misi menggunakan celana olahraga.
- Tiga misi per kategori menghasilkan lencana. Timer opsional tidak membatasi keberhasilan.
- Panduan lengkap tersedia dalam PANDUAN_MISI_GAME.txt.

CARA MEMBUKA
1. Ekstrak seluruh ZIP ke satu folder.
2. Buka index.html. Folder assets harus tetap berada di samping index.html.
3. Alternatif tanpa folder aset: buka RespiraLab_MPI_Kelas8.html.
4. Windows: START_RESPIRALAB.bat tetap tersedia.

SIMULASI BARU
Lab 2: Pertukaran O2/CO2 pada potongan alveolus–kapiler.
- Membran respirasi berada di antara ruang alveolus dan kapiler.
- O2 bergerak ke darah; CO2 bergerak ke alveolus.
- Eritrosit tetap berada dalam lumen kapiler; titik O2 di eritrosit melambangkan pengikatan pada hemoglobin.
- Play/Jeda, Ulangi, kecepatan animasi dan Perbesar diagram.

Lab 3: Inspirasi dan ekspirasi tenang.
- Gerak paru, tulang rusuk dan diafragma; panah arah aliran udara.
- Panel proses, perubahan volume, tekanan alveolus dan arah udara.
- Cuplikan inspirasi/ekspirasi, Play/Jeda, Ulangi, kecepatan dan Perbesar.
- Akhir fase: tekanan alveolus seimbang dengan udara luar; aliran berhenti.

Lab 3: Praktik model bell jar.
- Karet bawah ditarik/dikembalikan; dua balon berubah ukuran.
- Play/Jeda, Ulangi, penggeser tarikan manual, cuplikan gerak dan Perbesar.
- Panel membedakan tekanan ruang botol dari tekanan di dalam balon.
- Posisi manual menunjukkan keadaan setelah ditahan, ketika aliran sudah berhenti.
- Batas model dijelaskan: botol kaku, karet digerakkan tangan, tanpa alveoli/pertukaran gas.

TATA LETAK
- Diagram dan penjelasan berdampingan pada layar lebar, tersusun vertikal pada layar sempit.
- Label SVG tetap tajam saat diperbesar.
- Pada ponsel, diagram dapat digeser mendatar agar teks tidak menjadi terlalu kecil. Gunakan Perbesar untuk melihat diagram lebih jelas.
- Penjelasan inti selalu terbuka; rincian ilmiah berada dalam panel “Pelajari lebih lanjut” / “Catatan ilmiah”.
- Animasi dimulai dengan Play. Animasi berhenti saat berpindah halaman atau tab tidak aktif.
- Gambar anatomi internal, zoom materi, checkpoint, progres, fullscreen dan pilihan audio dipertahankan.

ASET INTERNAL BARU
assets/sim_gas_ilmiah.svg
assets/sim_breath_ilmiah.svg
assets/sim_jar_ilmiah.svg
Aset juga tertanam dalam HTML untuk kebutuhan animasi dan versi single-file.

RUJUKAN ILMIAH
NHLBI, NIH — How the Lungs Work: What Breathing Does for the Body
https://www.nhlbi.nih.gov/health/lungs/breathing-benefits
Science Buddies — How Do We Breathe? (lung model)
https://www.sciencebuddies.org/stem-activities/lung-model
Diagram SVG disusun khusus untuk RespiraLab; bukan salinan gambar sumber.

CATATAN MODEL
Diagram skematis, bukan ukuran anatomi atau simulasi fisiologi kuantitatif.
Kecepatan kontrol hanya mengatur animasi, bukan frekuensi napas sebenarnya.
Jumlah, warna partikel, dan perubahan ukuran balon disederhanakan.
Progres tersimpan dalam browser/localStorage bila tersedia.
