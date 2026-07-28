# Panduan Step-by-Step Implementasi di Canva

## Fase 1: Setup Canvas & Persiapan Awal

### Step 1: Buat Canvas Baru
1. Login ke Canva (https://www.canva.com)
2. Klik **"Create a design"** → **"Custom size"**
3. Masukkan ukuran:
   - **Width:** 60 cm (termasuk bleed 0,3 cm di kiri-kanan = 59,4 + 0,3 + 0,3)
   - **Height:** 42,6 cm (termasuk bleed 0,3 cm atas-bawah = 42 + 0,3 + 0,3)
   - Unit: **Centimeters**
4. Klik **"Create"**

### Step 2: Pengaturan Guide & Safe Area
1. Buka menu **View** → cari opsi **Guides** atau **Rulers**
2. Tambahkan guide manual:
   - **Horizontal guides** di: 0,3 cm (bleed atas), 1,2 cm (safe margin atas), 41,3 cm (safe margin bawah), 42,3 cm (bleed bawah)
   - **Vertical guides** di: 0,3 cm (bleed kiri), 1,2 cm (safe margin kiri), 58,8 cm (safe margin kanan), 59,7 cm (bleed kanan)
3. Enable **Snap to Guides** agar elemen otomatis snap ke guide saat digeser

### Step 3: Latar Dasar & Background
1. Klik **Background** (panel kanan bawah) atau double-click canvas kosong
2. Pilih **Color** → masukkan HEX: `#FCFBF7` (Krem)
3. Opsional (untuk tekstur): Upload hasil **Magic Design** sebagai lapis paling bawah
   - Gunakan prompt AI Canva:
     ```
     Desain latar belakang poster A2 landscape bertema islami modern
     minimalis untuk sekolah dasar islam terpadu, dominan warna hijau
     tua, tosca, emas, dan krem, elegan dan bersih dengan aksen garis
     geometris islami tipis di sudut, banyak ruang kosong di tengah
     dan bawah untuk grid kalender dan panel informasi, gaya flat vector
     ```
   - **Penting:** Hasilnya akan menjadi satu gambar raster (flat)—gunakan HANYA sebagai lapis 1 paling bawah, bangun semua elemen lain di atasnya

---

## Fase 2: Membuat Header Band

### Step 4: Bentuk Background Header
1. Klik **Elements** → cari **Rectangle** atau **Shape**
2. Drag bentuk persegi ke atas kanvas (area header)
3. Atur ukuran:
   - **Width:** 57,0 cm (lebar usable tanpa margin)
   - **Height:** 6,0 cm
   - **Position X:** 1,5 cm (dari kiri trim + margin 1,2 + gutter), **Y:** 0,3 cm (bleed atas)
4. **Fill color:** `#1F5C46` (Hijau Tua)
5. **Stroke:** None
6. **Name di Layer:** `Bg_Header`

### Step 5: Masukkan Logo Yayasan (Kiri)
1. Klik **Elements** → cari **"circle frame minimal"** atau frame Logo lainnya
2. Drag frame ke area kiri header (±4×4 cm)
3. Atur posisi:
   - **Width/Height:** 4,0 cm × 4,0 cm
   - **Position X:** 1,5 cm (margin aman kiri), **Y:** 1,3 cm (centered vertikal di header)
4. Upload gambar logo Yayasan:
   - Klik **Upload media** (ikon +)
   - Pilih file logo
   - Drag ke dalam frame
5. **Rename layer:** `Logo_Yayasan`
6. **Lock layer** (klik ikon gembok) setelah posisi final

### Step 6: Masukkan Logo SDIT (Kanan)
1. Ulangi Step 5 untuk area kanan header
2. **Position X:** 54,5 cm (dari kiri, area margin aman kanan), **Y:** 1,3 cm
3. **Rename layer:** `Logo_SDIT`
4. **Lock layer**

### Step 7: Buat Grup Teks Judul (H1/H2/H3)
1. Klik **Text** tool atau drag elemen teks
2. **H1 — "KALENDER AKADEMIK"**
   - Font: Poppins, ExtraBold, 100pt
   - Color: `#FCFBF7` (Krem)
   - Align: Center
   - Width: 40,0 cm
   - Position X: 10,0 cm (center horizontal), Y: 0,6 cm
   - Teks hanya: `KALENDER AKADEMIK`
   
3. **H2 — "SDIT YAA BUNAYYA"**
   - Font: Poppins, SemiBold, 60pt
   - Color: `#FCFBF7`
   - Align: Center
   - Width: 40,0 cm
   - Position X: 10,0 cm, Y: 1,8 cm
   - Teks hanya: `SDIT YAA BUNAYYA`

4. **H3 — "TAHUN AJARAN 2026/2027"**
   - Font: Poppins, Medium, 30pt
   - Color: `#FCFBF7`
   - Align: Center
   - Width: 40,0 cm
   - Position X: 10,0 cm, Y: 3,1 cm
   - Teks hanya: `TAHUN AJARAN 2026/2027`

5. **Garis Emas Pemisah** (di bawah H3)
   - Klik Elements → **Line** (atau draw line)
   - **Color:** `#C9A227` (Emas)
   - **Stroke width:** 0,75pt
   - **Width:** 30,0 cm
   - **Position X:** 15,0 cm (center), **Y:** 4,3 cm
   - **Rotate:** 0° (horizontal)

6. Pilih semua elemen teks (H1, H2, H3, garis) → Klik kanan → **Group**
7. **Rename:** `Grup_Teks_Judul`
8. **Lock** setelah selesai

---

## Fase 3: Membuat Grid Kalender (12 Blok Bulan)

### Step 8: Buat Template Satu Blok Bulan

**Persiapan struktur satu blok bulan yang akan di-duplikasi 11 kali:**

1. **Background Blok Bulan**
   - Klik Elements → Rectangle
   - Ukuran: 13,9 cm (width) × 7,8 cm (height)
   - Fill: `#FCFBF7` (Krem) atau transparent (hanya garis border)
   - Stroke: 1pt, Color `#D8D6CE` (Garis Tipis)
   - Radius: 0,3 cm
   - Position X: 1,5 cm, Y: 6,7 cm (untuk blok pertama—Juli 2026)
   - **Rename:** `Bg_Blok_[NamaBulan]`

2. **Bar Judul Bulan**
   - Rectangle baru:
   - Ukuran: 13,8 cm (width) × 0,9 cm (height)
   - Fill: `#1F5C46` (Hijau Tua) atau `#2F6E4E` (Hijau sedikit lebih terang)
   - Stroke: None
   - Radius: 0,3 cm (top-left & top-right saja)
   - Position: Dalam blok, Y offset 0
   - **Teks di atasnya:** Font Poppins Bold 20pt, Color Krem, Text: "JULI 2026" (uppercase)
   - **Rename:** `Bar_Judul_[Bulan]`

3. **Baris Label Hari (Ahad–Sabtu)**
   - Buat 7 sel label hari horizontal
   - Setiap sel: 2,0 cm (width) × 0,5 cm (height)
   - Label: AHAD, SENIN, SELASA, RABU, KAMIS, JUM'AT, SABTU
   - Font: Nunito Bold 11pt
   - Color Teks: `#22302A` (Teks Utama)
   - **Latar kolom Ahad:** `#F6E3DE` (Tint merah pucat) — gunakan Rectangle fill di belakang
   - **Latar kolom Jum'at:** `#DDEDE3` (Tint hijau pucat)
   - **Latar kolom lain:** `#EEEDE7` (Abu Muda)
   - Posisi Y: Bar judul + 0,9 cm = Y 0,9 cm dalam blok
   - **Group:** Pilih semua → Group → Rename: `Label_Hari_[Bulan]`

4. **Grid Sel Tanggal (5–6 baris × 7 kolom)**
   - Ukuran sel: 2,0 cm (width) × 1,05 cm (height)
   - Fill sel: White atau transparent (latar tint sudah ada di atas)
   - Stroke: 0,5pt, Color `#D8D6CE`
   - Radius: 0,15 cm
   - **Layout:** 7 kolom horizontal, 5–6 baris vertikal sesuai jumlah hari bulan
   - **Posisi Y dalam blok:** 1,4 cm (setelah label hari)
   
   **Untuk setiap sel:**
   - Masukkan **teks nomor tanggal** di pojok kiri-atas (font Nunito SemiBold 13pt, color `#22302A`)
   - Jika ada agenda di tanggal itu, tambahkan **dot warna** (circle radius 0,2 cm) di pojok kanan-bawah sel
     - Warna dot sesuai kategori (lihat Section 5 spesifikasi)
   - Jika >1 kategori di tanggal sama: tampilkan >1 dot (geser posisi agar tidak overlap)
   - Label agenda super-singkat (jika ruang): teks 7pt di bawah nomor tanggal (hanya bila sel lapang)
   
   - **Rename sel:** `Sel_[Bulan]_Tgl[Nomor]`
   - **Group semua sel:** Rename: `Grid_Tanggal_[Bulan]`

5. **Group Keseluruhan Blok Bulan**
   - Pilih: Background, Bar Judul, Label Hari, Grid Tanggal
   - Klik kanan → **Group**
   - **Rename:** `Grup_Bulan_[NamaBulan][Tahun]` (contoh: `Grup_Bulan_Juli2026`)
   - **Lock** setelah struktur final

### Step 9: Duplikasi & Posisi 12 Blok Bulan

1. Pilih `Grup_Bulan_Juli2026` → Klik kanan → **Duplicate** (atau Ctrl+D)
2. Ubah nama grup duplikat menjadi `Grup_Bulan_Agustus2026`
3. Edit elemen di dalam:
   - Ubah teks judul bar dari "JULI 2026" → "AGUSTUS 2026"
   - Ubah nomor tanggal & dot kategori sesuai isi bulan Agustus (lihat pemetaan agenda)
4. Atur posisi: **Kolom 2, Baris 1**
   - Position X: 17,4 cm (1,5 cm margin + 13,9 cm + 0,5 cm gutter)
   - Position Y: 6,7 cm (sama dengan kolom 1)
5. Ulangi langkah 1–4 untuk 10 bulan berikutnya
   - **Baris 1** (Y: 6,7 cm): Juli, Agustus, September, Oktober
     - X: 1,5 cm, 17,4 cm, 33,3 cm, 49,2 cm
   - **Baris 2** (Y: 15,1 cm): November, Desember, Januari, Februari
     - X: 1,5 cm, 17,4 cm, 33,3 cm, 49,2 cm
   - **Baris 3** (Y: 23,5 cm): Maret, April, Mei, Juni
     - X: 1,5 cm, 17,4 cm, 33,3 cm, 49,2 cm

6. **Alignment final:** Pilih semua 12 grup bulan → Menu **Arrange** (atau kanan-klik) → **Tidy Up** atau **Align** untuk memastikan grid presisi

---

## Fase 4: Membuat Footer Band

### Step 10: Background Footer
1. Rectangle baru:
   - Ukuran: 57,0 cm (width) × 8,4 cm (height)
   - Fill: `#FCFBF7` (Krem)
   - Stroke: 1pt top, Color `#D8D6CE`
   - Position: X 1,5 cm, Y 31,5 cm (setelah grid + gap)

2. **Rename:** `Bg_Footer`

### Step 11: Legenda Warna (Panel 1)
1. Container rectangle:
   - Ukuran: 25,1 cm (width) × 7,0 cm (height)
   - Fill: transparent (atau putih tipis)
   - Stroke: None
   - Position: X 1,5 cm, Y 31,5 cm
   - **Rename:** `Container_Legenda`

2. **Judul:** "LEGENDA" (Font Lato SemiBold 11pt, Bold, Teks Utama)
   - Position: Y 31,7 cm

3. **12 Item Kategori** (2–3 kolom):
   - Setiap item: Dot warna (circle 0,6 cm) + Teks kategori (10pt Lato SemiBold)
   - Layout grid 2 kolom (atau 3 kolom jika diperlukan agar muat):
     - **Kolom 1:** PBM, Libur, Ujian, Tahfizh, Outing, Kajian
     - **Kolom 2:** Administrasi, Ekstrakurikuler, Remedial, Classmeeting, Laporan, Kelulusan
   - Spacing: 0,15 cm antar item vertikal, 0,2 cm antar kolom

4. **Ikon kategori** (opsional):
   - Jika ada ruang, tambahkan ikon line 0,4×0,4 cm sebelum dot warna
   - Cari di Elements dengan kata kunci dari Step 7 SPESIFIKASI_DESAIN.md
   - **Rename:** `Item_Legenda_[Kategori]`

5. **Group semua legenda:** `Grup_Footer_Legenda`

### Step 12: Kontak & Sosial Media (Panel 2)
1. Container rectangle: 11,2 cm (width) × 7,0 cm
   - Position: X 27,1 cm (setelah legenda + gutter 0,4 cm), Y 31,5 cm
   - **Rename:** `Container_Kontak`

2. **Judul:** "KONTAK & SOSIAL" (Lato SemiBold 11pt Bold)

3. **Item kontak:**
   - ☎️ Telepon: [Isi no sekolah]
   - 📍 Alamat: [Isi alamat singkat]
   - 🌐 Website: [URL]
   - 📱 Instagram: [@username]
   
   Font: Lato Regular 9pt
   Color: `#6E6E68` (Teks Sekunder)
   
   **Ikon:** Cari di Elements (phone icon, location pin, website, instagram)
   - Icon size: 0,3 cm × 0,3 cm
   - Posisi: Sebelum teks, dengan spacing 0,1 cm

4. **Rename:** `Grup_Footer_Kontak`

### Step 13: QR Code (Panel 3)
1. Container rectangle: 6,7 cm (width) × 7,0 cm (height)
   - Position: X 38,7 cm, Y 31,5 cm
   - Stroke: None
   - **Rename:** `Container_QR`

2. **Placeholder QR Code:**
   - Rectangle: 2,5 cm × 2,5 cm
   - Fill: White
   - Stroke: 2pt, Style dashed/putus-putus, Color `#D8D6CE`
   - Position: Center dalam panel (X 39,95 cm, Y 33,45 cm)
   - **Label teks bawah:** "SCAN INFO LENGKAP" (Lato Regular 8pt, center)
   - **Setelah design final:** Replace placeholder dengan QR code asli yang di-generate dari Google Charts atau QR Code Generator (Anda isi URL sekolah)

3. **Rename:** `Grup_Footer_QR`

### Step 14: Catatan Penting (Panel 4)
1. Container rectangle: 12,8 cm (width) × 7,0 cm (height)
   - Position: X 45,9 cm, Y 31,5 cm
   - **Rename:** `Container_Catatan`

2. **Judul:** "CATATAN PENTING" (Lato SemiBold 10pt Bold)

3. **Bullet points** (Lato Regular 9pt, color `#22302A`):
   - • Tanggal merah = hari libur nasional
   - • Tanggal biru = ujian sekolah
   - • Informasi lengkap dapat diakses via QR code
   - [Optional] • **12 Juli 2027:** Hari Pertama Masuk TA 2027/2028

4. Spacing antar bullet: 0,2 cm

5. **Rename:** `Grup_Footer_Catatan`

### Step 15: Strip Document Control (Lapis Bawah Footer)
1. Rectangle background strip:
   - Ukuran: 57,0 cm (width) × 1,4 cm (height)
   - Fill: `#EEEDE7` (Abu Muda)
   - Stroke: 1pt top, Color `#D8D6CE`
   - Position: X 1,5 cm, Y 38,9 cm
   - **Rename:** `Bg_DocControl`

2. **Garis vertikal pembagi** (4 field sejajar):
   - 3 garis 0,5pt vertikal, color `#D8D6CE`
   - Posisi X: 15,5 cm, 29,5 cm, 43,5 cm (membagi 4 field)
   - Height: 1,4 cm

3. **Empat field teks** (Lato Regular 9pt, color `#6E6E68`):
   - **Field 1 (Versi Dokumen):** "Versi 1.0" — X 2,0 cm, Y 39,1 cm
   - **Field 2 (Tanggal Revisi):** "Tgl: [TBD]" — X 16,0 cm, Y 39,1 cm
   - **Field 3 (Nomor Revisi):** "Rev: 01" — X 30,0 cm, Y 39,1 cm
   - **Field 4 (Disusun/Disetujui):** "Disusun: [Nama] / Disetujui: [Nama]" — X 44,0 cm, Y 39,1 cm

4. **Group semua:** `Grup_Footer_DocControl`

---

## Fase 5: Finalisasi & Quality Control

### Step 16: Lock Elemen Dekoratif
1. Pilih layer: `Bg_Header`, `Bg_Footer`, `Bg_DocControl`, `Logo_Yayasan`, `Logo_SDIT`, `Grup_Teks_Judul`
2. Klik kanan → **Lock** pada setiap layer
3. Ini mencegah elemen tidak sengaja tergeser saat mengedit teks/agenda

### Step 17: Cek Layer Panel
Pastikan struktur layer (panel kanan Canva) mengikuti urutan Z-index dari Section 5 SPESIFIKASI_DESAIN.md:
