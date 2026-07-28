# Checklist Kualitas Sebelum Cetak & Produksi

Gunakan checklist ini untuk memastikan desain kalender akademik lulus quality control sebelum dikirim ke percetakan.

---

## ✅ FASE 1: AKURASI KALENDER & TANGGAL

### Verifikasi Jumlah Hari per Bulan
- [ ] **Juli 2026** = 31 hari (Hari pertama: Kamis)
- [ ] **Agustus 2026** = 31 hari (Hari pertama: Jumat)
- [ ] **September 2026** = 30 hari (Hari pertama: Senin)
- [ ] **Oktober 2026** = 31 hari (Hari pertama: Rabu)
- [ ] **November 2026** = 30 hari (Hari pertama: Sabtu)
- [ ] **Desember 2026** = 31 hari (Hari pertama: Senin)
- [ ] **Januari 2027** = 31 hari (Hari pertama: Rabu)
- [ ] **Februari 2027** = 28 hari (Hari pertama: Sabtu) — *2027 bukan tahun kabisat*
- [ ] **Maret 2027** = 31 hari (Hari pertama: Sabtu)
- [ ] **April 2027** = 30 hari (Hari pertama: Selasa)
- [ ] **Mei 2027** = 31 hari (Hari pertama: Kamis)
- [ ] **Juni 2027** = 30 hari (Hari pertama: Jumat)

### Verifikasi Kolom Hari
- [ ] Semua **Ahad** (tanggal berlatar merah pucat `#F6E3DE`) berada di kolom 1 untuk semua 12 bulan
- [ ] Semua **Sabtu** berada di kolom 7 untuk semua 12 bulan
- [ ] Semua **Jum'at** (berlatar hijau pucat `#DDEDE3`) berada di kolom 6 untuk semua 12 bulan
- [ ] Label hari di setiap blok bulan: AHAD, SENIN, SELASA, RABU, KAMIS, JUM'AT, SABTU (tidak ada typo)

### Verifikasi Urutan Blok Bulan
- [ ] **Baris 1 (atas):** Juli, Agustus, September, Oktober 2026 (kiri ke kanan)
- [ ] **Baris 2 (tengah):** November, Desember 2026, Januari, Februari 2027 (kiri ke kanan)
- [ ] **Baris 3 (bawah):** Maret, April, Mei, Juni 2027 (kiri ke kanan)

---

## ✅ FASE 2: KELENGKAPAN AGENDA

### Item dari Pemetaan Agenda
Cocokkan setiap item di PEMETAAN_AGENDA.md dengan desain:

**JULI 2026**
- [ ] Dot Libur (merah #B7402C) di tanggal: 1, 2, 3, 6, 7, 8, 9, 10
- [ ] Dot PBM (hijau #2F6E4E) di tanggal: 13, 14, 15, 16, 17
- [ ] Label mini "13 Juli" atau "Hari Pertama" jika ruang memungkinkan

**AGUSTUS 2026**
- [ ] Dot Ekstrakurikuler (kuning #F2C230) di tanggal: 3, 4, 5, 6, 7, 28
- [ ] Dot Administrasi (abu #8A8D91) di tanggal: 5
- [ ] **Dual-dot** di tanggal 5 (Ekstrakurikuler + Administrasi)
- [ ] Dot Libur (merah) di tanggal: 17, 25
- [ ] Label mini "17 Agustus" jika ruang

**[Lanjutkan untuk bulan berikutnya... cocokkan setiap item]**

### Dual-Dot Verification
Tanggal-tanggal dengan lebih dari satu kategori harus menampilkan **lebih dari satu dot**:
- [ ] **5 Agustus:** Ekstrakurikuler + Administrasi
- [ ] **29 September:** PBM + Remedial
- [ ] **6 April:** PBM + Remedial
- [ ] **24–25 Desember:** Libur (overlap range libur semester + libur nasional) — cukup satu dot Libur
- [ ] **7 Juni:** Kelulusan + Tahfizh
- [ ] [Cek item lain di pemetaan agenda]

---

## ✅ FASE 3: DESAIN VISUAL & LAYOUT

### Header Band
- [ ] Logo Yayasan (kiri) terlihat jelas, ukuran ≈4×4 cm, tidak terpotong
- [ ] Logo SDIT (kanan) terlihat jelas, ukuran ≈4×4 cm, seimbang dengan logo yayasan
- [ ] H1 "KALENDER AKADEMIK" terlihat dominan, font Poppins ExtraBold, warna krem (#FCFBF7)
- [ ] H2 "SDIT YAA BUNAYYA" ukuran lebih kecil dari H1, warna krem
- [ ] H3 "TAHUN AJARAN 2026/2027" ukuran lebih kecil dari H2, warna krem
- [ ] Garis emas pemisah di bawah H3 terlihat elegan (0,75pt stroke, #C9A227)
- [ ] Seluruh header berwarna dasar Hijau Tua (#1F5C46)
- [ ] Motif dekoratif Islami (jika ada) opacity rendah (6–10%), tidak mengganggu teks

### Grid Kalender (12 Blok)
- [ ] Ukuran blok bulan **konsisten** (13,9 cm lebar × 7,8 cm tinggi) di semua 12 bulan
- [ ] **Spacing antar blok** konsisten: 0,5 cm gutter horizontal & vertikal
- [ ] **Bar judul bulan:** Latar Hijau Tua atau Hijau sedikit lebih terang, tinggi 0,9 cm
- [ ] **Teks judul bulan:** Uppercase (JULI 2026, AGUSTUS 2026, dll), font Poppins Bold 20pt, warna krem
- [ ] **Baris label hari:** Tinggi 0,5 cm, warna teks gelap, background tint merah (Ahad) & hijau (Jum'at)
- [ ] **Sel tanggal:** Ukuran ≈2,0 × 1,05 cm (7 kolom × 5–6 baris per bulan)
- [ ] **Nomor tanggal:** Pojok kiri-atas sel, font Nunito SemiBold 13pt, warna teks utama (#22302A)
- [ ] **Dot kategori:** Pojok kanan-bawah sel, ukuran ±0,2–0,3 cm, warna sesuai kategori
- [ ] **Dual-dot:** Jika >1 kategori, dot kedua geser posisi agar terlihat jelas (bukan overlap)
- [ ] **Label agenda mikro:** Hanya di sel lapang & peristiwa besar (contoh "13 Juli", "17 Agustus"), font 7pt, maks 10–12 karakter
- [ ] **Grid spacing:** Garis antar sel 0,5–1pt, warna abu (#D8D6CE), tidak terlalu tebal

### Footer Band

#### Legenda Warna
- [ ] **12 swatch warna** lengkap dengan kategori:
  1. PBM — Hijau (#2F6E4E)
  2. Libur — Merah (#B7402C)
  3. Ujian — Biru (#2C5F9E)
  4. Tahfizh — Ungu (#6A4C93)
  5. Outing — Oranye (#E07A29)
  6. Kajian — Tosca (#1E8C8A)
  7. Administrasi — Abu (#8A8D91)
  8. Ekstrakurikuler — Kuning (#F2C230)
  9. Remedial — Coklat (#8B5E3C)
  10. Classmeeting — Merah Muda (#E28FA0)
  11. Laporan — Biru Tua (#16324F)
  12. Kelulusan — Emas (#C9A227)
- [ ] Setiap swatch ukuran minimum 0,6 × 0,6 cm (terbaca dari jarak)
- [ ] Teks kategori font Lato SemiBold 10–11pt, warna gelap, terbaca jelas
- [ ] Ikon kategori (jika ada) konsisten gaya line/outline, ukuran ≈0,4 × 0,4 cm
- [ ] **Judul "LEGENDA"** Bold, ukuran sedikit lebih besar dari kategori

#### Kontak & Sosial Media
- [ ] Telepon: Nomor sekolah jelas terbaca
- [ ] Alamat: Singkat, 1–2 baris
- [ ] Website: URL lengkap atau domain
- [ ] Instagram: Handle dengan @ symbol
- [ ] Ikon (phone, location, globe, instagram) konsisten line-style, ukuran 0,3 cm
- [ ] Font Lato Regular 9pt, warna teks sekunder (#6E6E68)

#### QR Code
- [ ] Placeholder QR (border putus-putus, 2,5 × 2,5 cm) terlihat jelas
- [ ] Label "SCAN INFO LENGKAP" di bawah placeholder, font Lato 8pt, center-aligned
- [ ] Kotak placeholder berada di area aman (tidak di bleed)
- [ ] **Setelah finalisasi:** QR code yang sudah di-generate bisa di-swap dengan placeholder tanpa mengubah layout

#### Catatan Penting
- [ ] **2–3 bullet point** standar (contoh: tanggal merah = libur, tanggal biru = ujian, akses info via QR)
- [ ] **Item khusus:** "12 Juli 2027: Hari Pertama Masuk TA 2027/2028" (jika diminta)
- [ ] Font Lato Regular 9pt, warna teks utama (#22302A)
- [ ] Spacing antar bullet 0,2 cm, terbaca jelas
- [ ] Judul "CATATAN PENTING" Bold

### Document Control Strip (Lapis Bawah Footer)
- [ ] Background latar abu (#EEEDE7)
- [ ] Garis top 1pt, warna abu (#D8D6CE)
- [ ] **4 field** sejajar:
  1. Versi Dokumen: "Versi 1.0" (atau versi terkini)
  2. Tanggal Revisi: "[TBD]" atau tanggal revisi terakhir
  3. Nomor Revisi: "Rev: 01" (atau nomor terakhir)
  4. Disusun/Disetujui: "[Nama] / [Nama]" (isi sesuai PIC)
- [ ] Font Lato Regular 9pt, warna teks sekunder (#6E6E68)
- [ ] Garis vertikal pembagi 0,5pt, warna abu
- [ ] Tinggi strip 1,4 cm, spacing internal 0,1–0,2 cm

---

## ✅ FASE 4: LEGIBILITAS & KONTRAS

### Teks & Warna
- [ ] **Teks gelap (#22302A) di latar terang:** Kontras tinggi, terbaca jelas (contoh: angka tanggal di sel putih)
- [ ] **Teks krem (#FCFBF7) di latar hijau tua (#1F5C46):** Kontras tinggi, readability OK (header)
- [ ] **Tint latar Ahad (#F6E3DE):** Cukup terang sehingga teks gelap masih terbaca (bukan terlalu gelap/jenuh)
- [ ] **Tint latar Jum'at (#DDEDE3):** Cukup terang sehingga teks gelap masih terbaca
- [ ] **Teks category labels di legenda:** Cukup besar (10–11pt) & warna cukup gelap agar terbaca dari jarak 1,5–2 meter
- [ ] **Dot warna:** Warna-warna 12 kategori harus **tegas berbeda satu sama lain**, terutama pasangan yang mirip:
  - Ujian (#2C5F9E) vs Laporan (#16324F) — keduanya biru tapi jelas berbeda terang/gelap
  - Ekstrakurikuler (#F2C230) vs Emas Kelulusan (#C9A227) — keduanya emas tapi berbeda

### Test Jarak Jauh (Virtual)
- [ ] **Di Canva:** Zoom out ke 25% untuk simulasi view dari jarak 2 meter
- [ ] H1 "KALENDER AKADEMIK" masih **paling dominan** & mudah dibaca
- [ ] H2 nama sekolah masih terlihat dengan jelas
- [ ] **12 blok bulan** terlihat sebagai grid rapi, bukan kacau
- [ ] Teks angka tanggal masih terbaca (meski kecil)
- [ ] Dot kategori terlihat, bukan sekadar titik kabur
- [ ] Legenda warna terlihat lengkap dengan swatch yang jelas

---

## ✅ FASE 5: BATAS AMAN & BLEED

### Safe Margin (1,2 cm)
- [ ] Semua teks header (H1, H2, H3) berada di dalam safe margin 1,2 cm dari tepi
- [ ] Semua elemen di footer (legenda, kontak, QR, catatan, doc control) di dalam safe margin 1,2 cm
- [ ] Logo yayasan & logo SDIT tidak menyentuh atau melampaui safe margin 1,2 cm
- [ ] QR code placeholder di dalam safe margin 1,2 cm
- [ ] Tidak ada teks atau logo yang menggantung di area bleed (0,3 cm dari trim)

### Bleed Area (0,3 cm)
- [ ] Latar warna (Hijau Tua header, Krem background, Abu footer) **diteruskan sampai ke garis bleed** (tidak ada garis putih tipis)
- [ ] Elemen dekoratif/tekstur juga meluas ke bleed area (jika ada)
- [ ] **Tidak ada** teks, logo, atau garis penting di area bleed 0,3 cm

### Guide Verification
- [ ] Guide di Canva sudah setup di 0,3 cm (bleed) dan 1,2 cm (safe margin) dari semua tepi
- [ ] Snap to Guides **enabled** saat positioning elemen final
- [ ] Tidak ada elemen yang sengaja melampaui safe margin area

---

## ✅ FASE 6: STRUKTUR LAYER & EDITABILITY

### Layer Organization
- [ ] **Semua layer** di panel Layers Canva mengikuti struktur hierarki:
- [ ] Kanvas A2 ├── Grup_Footer_DocControl (top/paling atas) ├── Grup_Footer_Catatan ├── Grup_Footer_QR ├── Grup_Footer_Kontak ├── Grup_Footer_Legenda ├── Bg_Footer ├── Grup_Bulan_Juni2027 ├── [... 9 grup bulan lainnya ...] ├── Grup_Bulan_Juli2026 ├── Grup_Teks_Judul ├── Logo_SDIT ├── Logo_Yayasan ├── Bg_Header └── Bg_Kanvas atau Latar_Dekoratif (bottom/paling bawah)

- [ ] 
### Lock/Unlock Status
- [ ] **Locked:** `Bg_Header`, `Logo_Yayasan`, `Logo_SDIT`, `Grup_Teks_Judul`, `Bg_Footer`, `Bg_DocControl`, elemen dekoratif
- *Alasan:* Mencegah pergeseran tidak sengaja saat edit teks
- [ ] **Unlocked:** Semua grup bulan, elemen teks tanggal/agenda, dot kategori
- *Alasan:* Sering direvisi

### No Flatten Requirement
- [ ] **Semua elemen terpisah & dapat diklik** individual (bukan satu gambar flat)
- [ ] Logo bisa di-select & di-drag
- [ ] Teks judul bisa di-edit
- [ ] Dot kategori bisa di-geser atau di-ubah warna
- [ ] Setiap blok bulan bisa di-duplikasi atau di-edit dalam grup
- [ ] **Jangan ungroup permanent** — gunakan double-click masuk ke grup jika perlu edit detail

---

## ✅ FASE 7: FONT & ELEMEN CANVA

### Font Availability
- [ ] **Poppins** (ExtraBold, SemiBold, Medium, Bold) tersedia & terpilih di akun Canva yang dipakai
- [ ] H1 "KALENDER AKADEMIK" — Poppins ExtraBold
- [ ] H2 "SDIT YAA BUNAYYA" — Poppins SemiBold
- [ ] H3 tahun — Poppins Medium
- [ ] Judul bulan — Poppins Bold
- [ ] **Nunito** (Bold, SemiBold) tersedia
- [ ] Label hari — Nunito Bold
- [ ] Angka tanggal — Nunito SemiBold
- [ ] **Lato** (Regular, SemiBold, Light) tersedia
- [ ] Legenda kategori — Lato SemiBold
- [ ] Kontak/catatan — Lato Regular/Light

### Elemen Canva (Ikon & Shape)
- [ ] **Ikon legenda:** Semua 12 ikon ditemukan & konsisten gaya line/outline
- [ ] PBM: Open book icon ✓
- [ ] Libur: Calendar X icon ✓
- [ ] Ujian: Exam paper icon ✓
- [ ] Tahfizh: Quran book icon ✓
- [ ] Outing: Bus icon ✓
- [ ] Kajian: Mosque icon ✓
- [ ] Administrasi: Clipboard icon ✓
- [ ] Ekstrakurikuler: Star/Trophy icon ✓
- [ ] Remedial: Refresh/Pencil icon ✓
- [ ] Classmeeting: Trophy/Confetti icon ✓
- [ ] Laporan: Report card icon ✓
- [ ] Kelulusan: Graduation cap icon ✓
- [ ] **Ukuran ikon legenda:** Konsisten ≈0,4 × 0,4 cm
- [ ] **Frame logo:** Dua frame placeholder untuk logo yayasan & SDIT, ratio seimbang

---

## ✅ FASE 8: EXPORT & PERCETAKAN

### File Format & Setting
- [ ] Export format: **PDF (Print)** — bukan PDF Standard
- [ ] Page size: **A2** (59,4 × 42 cm)
- [ ] **Include bleed:** Enabled (jika Canva meminta setting bleed manual)
- [ ] **Quality:** High / Best resolution (300 DPI recommended untuk print)
- [ ] **Color mode:** CMYK atau RGB (sesuai kebutuhan percetakan)
- [ ] File size: Reasonable (< 50 MB untuk PDF print)

### QR Code Finalization
- [ ] QR code sudah di-generate (dari Google Charts, QR Code Generator, atau tools lain)
- Target: URL website sekolah atau link info kalender digital
- [ ] QR code sudah **dites scan** dengan 2–3 smartphone (berbeda merk) untuk memastikan readable
- [ ] QR code **replace placeholder** di footer (posisi tetap ±2,5 × 2,5 cm, di dalam safe margin)
- [ ] QR code resolution tinggi, bukan terlalu kecil atau blur

### Persiapan Percetakan
- [ ] File PDF sudah di-send ke **percetakan yang menangani ukuran A2**
- Cek: Apakah printer/percetakan bisa handle A2 landscape?
- Jika tidak, cari percetakan lain atau downsize ke A3
- [ ] **Komunikasi dengan percetakan:**
- [ ] Confirm ukuran final: 59,4 × 42 cm (landscape)
- [ ] Confirm bleed handling: 0,3 cm semua sisi
- [ ] Confirm output: Gloss/Matte paper, thickness, quantity
- [ ] Confirm delivery timeline & cost
- [ ] **Approval proof:** Minta soft proof atau hardcopy sample sebelum cetak massal

---

## ✅ FASE 9: FINAL CHECKLIST SEBELUM APPROVAL

Tanda tangani setelah semua item di atas selesai:

- [ ] **Tanggal & Kalender:** Akurat, semua hari benar, layout grid rapi
- [ ] **Agenda:** Lengkap, dot kategori tepat, dual-dot jelas terlihat
- [ ] **Desain Visual:** Header/footer/blok bulan konsisten, warna brand tepat, logo seimbang
- [ ] **Legibilitas:** Teks terbaca dari jarak jauh, kontras tinggi, font tersedia
- [ ] **Safe Area:** Semua elemen di dalam 1,2 cm margin, tidak ada teks di bleed
- [ ] **Layer & Edit:** Struktur folder clean, tidak ada flatten, elemen masih individual
- [ ] **Export:** PDF Print 300 DPI, include bleed, A2 landscape
- [ ] **QR Code:** Sudah dites, bisa di-scan, di-replace placeholder
- [ ] **Komunikasi Percetakan:** Spec sudah disetujui, proof diterima

**Signed By:**
- Design Lead: _________________________ (Nama & Tgl)
- Approval Authority: _________________________ (Nama & Tgl)

**Catatan Tambahan/Revisi:**
[Isi di sini jika ada item yang perlu follow-up]


---

**Status:** ✅ **READY TO PRINT** / ⏳ **REVISION NEEDED** (pilih salah satu)
