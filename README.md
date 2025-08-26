<p align="center">
  <strong>New Guinea Highland Wild Dog (NGHWD)</strong>
</p>

**Singkatan:** NGHWD — *New Guinea Highland Wild Dog*

## Ringkasan

Repositori ini berisi dokumentasi, data, dan skrip pendukung penelitian mengenai *New Guinea Highland Wild Dog* (NGHWD). Tujuan utama adalah mengumpulkan, mengorganisir, dan menyajikan hasil-hasil lapangan, data morfometrik, rekaman perilaku, serta data genetik pendukung konservasi dan pemahaman taksonomi canid ini.

> Catatan: README ini ditujukan agar mudah dibaca oleh peneliti, mahasiswa, dan kontributor non-spesialis. Jika Anda ingin menggunakan data untuk publikasi, mohon ikuti pedoman sitasi pada bagian *Sitasi*.

---

## Tujuan Proyek

1. Mengumpulkan dan menjelaskan data morfometrik dan perilaku NGHWD.
2. Menyediakan metadata dan protokol pengambilan data (mis. camera trap, transek, wawancara etnozoologi).
3. Mendukung analisis taksonomis dan konservasi berbasis bukti (mis. analisis genetik, pemetaan sebaran).
4. Menjadi repositori terbuka untuk kolaborasi antar-peneliti dan mahasiswa.

---

## Latar Belakang Singkat

NGHWD adalah populasi canid endemik dataran tinggi New Guinea yang memiliki nilai ekologis dan kultural tinggi. Pengetahuan ilmiah tentang status populasi, distribusi, dan variasi genetiknya masih terbatas, sehingga penelitian lapangan dan analisis multidisipliner sangat penting.

---

## Informasi Taksonomi (ringkasan)

* **Nama umum:** New Guinea Highland Wild Dog (NGHWD)
* **Nama ilmiah (sementara):** *Canis* sp. (penamaan taksonomi perlu konfirmasi genomik)
* **Keluarga:** Canidae

> Catatan: Gunakan kajian genetik yang terbaru untuk rekomendasi taksonomi definitif.

---

## Karakteristik Morfologi & Perilaku (ringkasan)

* **Morfologi:** Tubuh kompak, bulu tebal di dataran tinggi, variasi warna dari cokelat kemerahan sampai hitam, dimorfisme seksual moderat.
* **Perilaku:** Cenderung soliter atau hidup dalam kelompok kecil; aktivitas sering terjadi pada dini hari dan senja; vocalization khas yang mirip "nyanyian" pada beberapa populasi penjagaan captive NGSD.
* **Ekologi:** Pemangsa oportunistik—makanan utama berupa mamalia kecil hingga menengah, kadang memanfaatkan sumber makanan antropogenik.

---

## Metodologi Penelitian (protokol ringkas)

1. **Camera traps**

   * Penempatan: jalur satwa, sumber air, dan dekat area perburuan.
   * Interval pengambilan: foto dan video (resolusi tinggi jika memungkinkan).
2. **Transek dan pengamatan langsung**

   * Catat waktu, lokasi (GPS), kondisi cuaca, perilaku yang diamati.
3. **Sampling genetik**

   * Pengumpulan sampel non-invasif (kotoran, bulu). Simpan dalam buffer/etanol sesuai protokol molekuler.
4. **Wawancara etnobiologi**

   * Struktur wawancara: pengetahuan lokal, hubungan manusia-satwa, persepsi ancaman.
5. **Morfometri**

   * Pengukuran standar: berat, tinggi bahu, panjang tubuh, panjang kepala, lingkar dada, panjang gigi carnassial.

---

## Struktur Repositori

```
/ (root)
├─ data/                # Data mentah (foto, video, CSV, FASTA)
├─ scripts/             # Skrip analisis (R, Python)
├─ docs/                # Dokumen tambahan: protokol, metadata
├─ results/             # Hasil analisis: peta, grafik, tabel
├─ LICENSE
└─ README.md            # (Anda sedang membaca ini)
```

> *Catatan:* Data mentah sensitif (lokasi spesifik hewan terancam) dapat disimpan dengan akses terbatas. Pastikan anonymization metadata sebelum publikasi jika perlu.

## Cara Berkontribusi

1. Fork repositori ini.
2. Buka issue jika ingin menambahkan data atau fitur.
3. Buat pull request dengan perubahan yang jelas dan dokumentasi.
4. Sertakan metadata lengkap untuk setiap dataset (format: CSV/TSV + README dataset).

---

## Etika & Perlindungan Data

* Tidak mempublikasikan koordinat lokasi sensitif dari pengamatan individu yang berisiko.
* Ikuti peraturan lokal dan perizinan pengumpulan sampel biologis.
* Dapatkan persetujuan informan lokal sebelum menyebarkan materi etnografi.

---

## Lisensi

Lisensi default: **CC BY 4.0** untuk dokumentasi dan data non-sensitif. Untuk skrip analisis gunakan **MIT License** kecuali dinyatakan lain.

---

## Sitasi

Jika menggunakan data atau analisis dari repositori ini, mohon sitasi sebagai berikut (contoh):

> Numberi, L.A., Surbakti, S., Maury, H.K. (2025). *New Guinea Highland Wild Dog (NGHWD) dataset and analyses*. GitHub repository.

---

## Kontak

* Leonardo A. Numberi — `leoashr@gmail.com`
* Tim penelitian: Suriani Surbakti, Hendra K. Maury

---

## Roadmap (ide fitur / pengembangan)

* Menambahkan dashboard interaktif untuk visualisasi sebaran.
* Pipeline otomatis untuk memproses gambar camera trap (deteksi objek).
* Integrasi metadata genetik (FASTA) dan metadata morfologi untuk analisis komprehensif.

---

Terima kasih telah berkontribusi!
