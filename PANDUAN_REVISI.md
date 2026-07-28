# Panduan Revisi & Update Kalender Akademik

Gunakan panduan ini untuk melakukan edit & revisi aman pada kalender di Canva tanpa merusak grid struktur.

---

## Kapan Perlu Revisi?

- Perubahan tanggal agenda (tambah/hapus/ubah)
- Update informasi kontak sekolah
- Perbaikan typo teks
- Revisi versi dokumen (Versi 1.0 → 1.1)
- Perubahan design elemen (warna, ukuran font, dll)

---

## Sebelum Memulai Revisi

### 1. Buat Duplicate Design (Backup)
1. Di halaman design Canva, klik menu **⋮** (More)
2. Pilih **Duplicate design**
3. Rename jadi: `[Nama Original]_v1.1_DRAFT` atau `[Nama Original]_BACKUP_[TanggalRevisi]`
4. Simpan sebagai referensi jika revisi tidak sesuai harapan

### 2. Buka Design Original di Browser Tab Baru
- Jaga original design tetap bisa diakses sebagai referensi
- Bekerja di duplicate design (bukan original)

---

## Tipe Revisi & Cara Mengerjakannya

### REVISI TIPE 1: Ubah/Tambah Tanggal & Agenda di Sel Tanggal

**Skenario:** Tanggal 15 Agustus ada agenda baru, atau ubah kategori yang sudah ada.

**Langkah:**

1. **Masuk ke Grup Bulan**
   - Cari layer `Grup_Bulan_Agustus2026` di panel Layers
   - Double-click nama grup (atau double-click di canvas)
   - Anda sekarang "masuk" ke dalam grup (kurset canvas berubah, menunjukkan hirarki)

2. **Temukan Sel Tanggal Target**
   - Cari sel tanggal 15 (scroll atau cari di struktur layer)
   - Klik sel untuk select

3. **Edit Nomor Tanggal (jika perlu)**
   - Double-click teks nomor "15" di dalam sel
   - Edit angka (jika tanggal berubah)
   - Klik di luar untuk confirm

4. **Tambah/Ubah Dot Kategori**
   - **Tambah dot baru:**
     - Cari salah satu dot kategori yang sudah ada di sel lain (contoh: dot Ujian biru di tanggal 21)
     - Klik dot → Klik kanan → **Copy** (Ctrl+C)
     - Klik di sel target (tanggal 15) → **Paste** (Ctrl+V)
     - Dot paste akan muncul di tengah sel
     - Geser dot ke pojok kanan-bawah
     - Double-click dot → ubah warna di panel color sesuai kategori yang diinginkan
     - **Penting:** Jangan bikin shape baru (Circle) — selalu copy-paste dot yang sudah ada agar ukurannya konsisten

   - **Ubah dot yang sudah ada:**
     - Klik dot di sel → panel color kanan → ubah HEX ke warna kategori baru
     - Jangan geser posisi (kecuali ada alasan spesifik)

5. **Tambah/Edit Label Agenda Mikro (Optional)**
   - Jika sel lapang & agenda penting (contoh "Hari Pertama", "17 Agustus")
   - Double-click di area bawah nomor tanggal → edit teks (maks 10–12 karakter)
   - Font: Lato Regular 7pt
   - Jangan paksakan teks panjang

6. **Keluar dari Grup**
   - Klik area kosong di canvas atau tekan **Escape** untuk keluar dari dalam grup
   - Struktur grid harus tetap rapi, tidak ada elemen yang tergeser

---

### REVISI TIPE 2: Update Informasi Kontak di Footer

**Skenario:** Nomor telepon sekolah berubah, atau website diperbarui.

**Langkah:**

1. **Buka Grup Footer Kontak**
   - Layer: `Grup_Footer_Kontak` → Double-click
   - Anda masuk ke dalam grup

2. **Edit Teks Kontak**
   - Klik teks nomor telepon → double-click → edit nomor
   - Klik teks alamat → double-click → edit alamat (singkat max 2 baris)
   - Klik teks website → double-click → edit URL
   - Klik teks Instagram → double-click → edit handle (gunakan @username format)

3. **Jangan Ubah Ikon Posisi**
   - Ikon (phone, location, globe, instagram) jangan digeser
   - Jika ada ikon yang salah, ganti ikon bukan geser posisi

4. **Keluar Grup**
   - Klik area kosong atau Escape

---

### REVISI TIPE 3: Update Legenda Warna

**Skenario:** Nama kategori typo, atau ubah urutan kategori.

**Langkah:**

1. **Buka Grup Footer Legenda**
   - Layer: `Grup_Footer_Legenda` → Double-click

2. **Edit Nama Kategori**
   - Cari teks nama kategori (contoh "PBM") → double-click → edit
   - **Jangan ubah warna swatch** (dot) — swatch warna harus tetap fix per kategori
   - Jika ingin ubah urutan kategori, lebih baik duplicate & ubah struktur (lihat Revisi Tipe 4)

3. **Jangan Ubah Warna Swatch**
   - Swatch warna di legenda **HARUS sama** dengan dot di grid kalender
   - Jika ada perubahan warna kategori, ubah KEDUA tempat (grid + legenda)

4. **Keluar Grup**

---

### REVISI TIPE 4: Update Versi Dokumen & Tanggal Revisi

**Skenario:** Revisi selesai, perlu update metadata di footer.

**Langkah:**

1. **Buka Grup Footer Document Control**
   - Layer: `Grup_Footer_DocControl` → Double-click

2. **Edit 4 Field:**
   - **Versi Dokumen:** "Versi 1.0" → "Versi 1.1" (atau nomor terbaru)
   - **Tanggal Revisi:** "[TBD]" → "Tgl: 28 Juli 2026" (tanggal revisi)
   - **Nomor Revisi:** "Rev: 01" → "Rev: 02" (increment setiap revisi)
   - **Disusun/Disetujui:** Isi nama PIC (Person In Charge)

3. **Keluar Grup**

4. **Simpan File**
   - Klik **Save** (Ctrl+S) di Canva
   - Canva otomatis save, tapi pastikan untuk manual save juga

---

### REVISI TIPE 5: Ganti Logo

**Skenario:** Desain logo yayasan atau sekolah berubah.

**Langkah:**

1. **Cari Frame Logo di Layer**
   - Layer: `Logo_Yayasan` atau `Logo_SDIT` → Click-sekali (select frame, jangan masuk)

2. **Upload Gambar Logo Baru**
   - Di dalam frame terlihat gambar lama
   - Klik **Upload** (ikon +) di dalam frame
   - Pilih file logo baru (.png/.jpg)
   - Drag ke dalam frame
   - Logo baru auto-fit ke dalam frame (atau bisa di-crop/resize di dalam frame)

3. **Pastikan Rasio Logo**
   - Logo tidak boleh distort
   - Jika frame sudah 4×4 cm, logo muat dengan baik
   - Jika logo original rectangular, gunakan frame yang rectangular juga (ubah frame dimension)

4. **Lock Frame Kembali**
   - Setelah selesai, lock frame agar tidak tergeser

---

### REVISI TIPE 6: Ubah Warna Kategori (Major Change)

**Skenario:** Kategori "Ujian" warna biru (#2C5F9E) diubah ke warna lain.

**Langkah:**

⚠️ **PERHATIAN:** Ini adalah perubahan besar. Perlu update di 3 tempat:
1. Dot kategori di semua sel tanggal grid (12 bulan)
2. Swatch warna di legenda footer
3. (Opsional) Ikon kategori di legenda

**Cara aman:**

1. **Update Legenda Dulu**
   - Buka `Grup_Footer_Legenda` → Temukan swatch Ujian (biru #2C5F9E)
   - Klik swatch → panel color → ubah HEX ke warna baru
   - Semua dot Ujian di grid otomatis akan terpengaruh? **TIDAK** — Anda harus update manual

2. **Update Dot di Grid** (lebih sulit)
   - Untuk setiap dot kategori Ujian di semua bulan (September, Desember, Maret, April, Mei, Juni):
     - Masuk ke `Grup_Bulan_[Nama]` → temukan dot Ujian → klik → ubah warna di panel color
   - **Alternatif:** Cari-ganti warna (#2C5F9E) ke warna baru di seluruh design
     - Canva tidak punya "Find & Replace Color" built-in
     - Solusi: Manual per dot (teliti) atau gunakan design software lain jika available

3. **Verifikasi**
   - Cek bahwa swatch legenda & semua dot di grid sudah warna yang sama

---

## WORKFLOW REVISI STANDAR

Setiap kali ada revisi, ikuti workflow ini:

### Step 1: Duplikasi Design
[Original] → Duplicate → [Nama]_v[Versi]_DRAFT


### Step 2: Edit di DRAFT
- Lakukan semua perubahan di file DRAFT
- Jangan edit original sampai revisi selesai & approved

### Step 3: QC Sendiri (Self-Check)
- Jalankan **Checklist Kualitas** (CHECKLIST_KUALITAS.md) untuk memastikan perubahan tidak membuat error
- Cek khusus:
  - [ ] Tidak ada elemen yang tergeser
  - [ ] Dot kategori masih di posisi yang benar
  - [ ] Teks masih terbaca
  - [ ] Layer structure tetap rapi

### Step 4: Update Metadata
- Ubah **Versi Dokumen** (1.0 → 1.1)
- Ubah **Tanggal Revisi** (hari ini)
- Ubah **Nomor Revisi** (01 → 02)

### Step 5: Submit untuk Approval
- Export file sebagai PDF
- Kirim ke pihak yang approve (principal, koordinator, dll)
- Tunggu feedback

### Step 6: Jika Approved
- Rename DRAFT → Final
- [Nama]_v1.1_DRAFT → [Nama]_v1.1_FINAL

- Simpan original lama sebagai archive
- [Original] → [Nama]_v1.0_ARCHIVE

- Set yang baru jadi default design

### Step 7: Jika Ada Revisi Lanjutan
- Duplicate FINAL lagi untuk round 2
- [Nama]_v1.1_FINAL → Duplicate → [Nama]_v1.2_DRAFT

- Ulangi step 2–6

---

## Troubleshooting Revisi

### Problem: Elemen Tergeser/Hilang Setelah Edit

**Penyebab:**
- Tidak masuk ke dalam grup (edit di level atas, bukan inside grup)
- Ungroup permanen (tidak bisa restore structure)

**Solusi:**
- Undo (Ctrl+Z) berkali-kali sampai kembali ke posisi sebelumnya
- Jika terlanjur, gunakan backup (duplicate design) yang dibuat di awal

### Problem: Dot Kategori Ukurannya Berbeda-beda

**Penyebab:**
- Bikin dot baru dari scratch (resize manual) alih-alih copy-paste

**Solusi:**
- Undo perubahan
- Gunakan **copy-paste dot yang sudah ada** untuk menjamin ukuran konsisten
- Hanya ubah warna & posisi, jangan resize

### Problem: Font Tidak Tersedia di Akun Lain

**Penyebab:**
- Font (Poppins/Nunito/Lato) mungkin hanya tersedia di Canva Pro atau akun tertentu

**Solusi:**
- Cek ketersediaan font di akun yang buka file
- Jika tidak ada, substitute dengan font serupa yang tersedia (misal: Poppins → Open Sans)
- Update dokumentasi font yang digunakan

### Problem: QR Code Tidak Bisa Di-scan Setelah Replace

**Penyebab:**
- QR code di-resize/crop terlalu kecil
- QR code quality rendah (image blur/pixelated)

**Solusi:**
- QR code harus minimal 2×2 cm untuk tetap scannable
- Gunakan file QR code HD (resolution tinggi, PNG atau SVG)
- Test scan dengan 2–3 smartphone sebelum finalisasi

---

## Tips & Best Practice Revisi

1. **Jangan Perubahan Struktur Besar di Akhir Produksi**
 - Kalau banyak perubahan, lebih baik redesign dari awal daripada patch-patch

2. **Gunakan Layer Naming yang Konsisten**
 - `Grup_Bulan_[NamaBulan][Tahun]` bukan `Gr1`, `Gr2`, dll
 - Memudahkan pencarian saat revisi

3. **Lock Elemen yang Sudah Final**
 - Lock header, footer, struktur — unlock hanya elemen yang sering berubah (teks agenda, dot)

4. **Backup Berkala**
 - Setiap revisi major, simpan snapshot (duplicate design) dengan nama jelas
 - Jangan delete versi lama sampai yang baru approved

5. **Dokumentasi Revisi**
 - Di **Catatan Penting** (atau file terpisah), catat perubahan per versi:
   ```
   v1.0 (28 Juli 2026) — Initial design, 12 bulan, 12 kategori
   v1.1 (1 Agustus 2026) — Fix typo "SDIT YAA BUNAYYA", update kontak
   v1.2 (5 Agustus 2026) — Ubah warna kategori Remedial, add QR code
   ```

6. **Koordinasi Tim**
 - Jika ada multiple designer/editor, gunakan sistem:
   - Design lead → buat & maintain master file
   - Editor → hanya edit di file DRAFT yang sudah dialokasikan
   - Jangan edit original bersamaan (conflict)

---

## Persiapan untuk Tahun Ajaran Berikutnya

Kalau mau reuse template untuk tahun ajaran 2027/2028:

1. **Duplikasi Design Terbaru**
2. Kalender_TA2026-2027_v1.2_FINAL → Duplicate → Kalender_TA2027-2028_v1.0


2. **Edit Minimal:**
- [ ] H3 tahun ajaran: "TAHUN AJARAN 2026/2027" → "TAHUN AJARAN 2027/2028"
- [ ] Grid tanggal: Update semua angka tanggal sesuai kalender 2027/2028 (lihat Google Calendar atau kalender masehi)
- [ ] Agenda: Update semua dot kategori & label agenda sesuai data baru TA 2027/2028
- [ ] Catatan Penting: Update "12 Juli 2027" → "12 Juli 2028" (atau tanggal hari pertama masuk tahun depan)
- [ ] Document Control: Versi 1.0, Tanggal revisi hari ini, dsb.

3. **Struktur Grid Tetap Sama**
- Jangan ubah ukuran blok bulan, margin, warna brand, font, dll
- Konsistensi visual dari tahun ke tahun
