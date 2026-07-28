# Spesifikasi Desain Kalender Akademik SDIT Yaa Bunayya TA 2026/2027

## 1. LAYOUT LENGKAP — Wireframe Deskriptif

Kanvas dibaca sebagai tiga zona horizontal yang ditumpuk, dengan margin aman 1,2 cm di keempat sisi.

### a) Header Band — tinggi 6,0 cm, lebar penuh

- **Kiri:** Logo Yayasan Pendidikan Islam Al Atsariyyah, area aman ±4×4 cm
- **Tengah:** Blok judul tiga baris
  - H1: "KALENDER AKADEMIK" (Poppins ExtraBold, 96–108pt)
  - H2: "SDIT YAA BUNAYYA" (Poppins SemiBold, 56–64pt)
  - H3: "TAHUN AJARAN 2026/2027" (Poppins Medium, 28–32pt)
  - Disusun rata tengah dengan satu garis tipis emas pemisah di bawah H3
- **Kanan:** Logo SDIT Yaa Bunayya, area aman ±4×4 cm, ukuran visual seimbang dengan logo yayasan
- **Opsional:** Motif geometris Islami tipis (opacity 6–10%) di area kosong sebagai tekstur

### b) Grid Kalender Utama — tinggi 24,4 cm, lebar penuh

- **12 blok bulan** dalam 4 kolom × 3 baris
- **Urutan blok** (kiri→kanan, atas→bawah):
  - **Baris 1:** Juli, Agustus, September, Oktober 2026
  - **Baris 2:** November, Desember 2026, Januari, Februari 2027
  - **Baris 3:** Maret, April, Mei, Juni 2027

#### Struktur Satu Blok Bulan (±13,9 × 7,8 cm)
- Bar judul bulan: tinggi 0,9 cm
- Baris label hari (Ahad–Sabtu): tinggi 0,5 cm
- Grid tanggal: 5–6 baris minggu, sisa tinggi 6,4 cm
  - **Tinggi sel tanggal:** ±1,05–1,1 cm
  - **Lebar sel tanggal:** ±2,0 cm

#### Sel Tanggal (±2,0 × 1,05 cm)
- Angka tanggal di pojok kiri-atas
- 1–2 titik warna kecil (dot kategori) di pojok kanan-bawah bila ada agenda
- Jika >2 kategori di tanggal sama, tambahkan tanda "+" kecil di sebelah dot
- Label super-singkat (maks 10–12 karakter) hanya di sel lapang & peristiwa besar

#### Highlight Kolom
- **Kolom Ahad:** Latar sel ditinting merah muda pucat (#F6E3DE)
- **Kolom Jum'at:** Latar sel ditinting hijau muda pucat (#DDEDE3)
- **Kolom lain:** Latar netral putih/abu sangat muda (#EEEDE7)

### c) Footer Band — tinggi 8,4 cm, lebar penuh

#### Lapis Atas (7,0 cm) — 4 kolom sejajar

| Panel | Proporsi | Lebar | Konten |
|---|---|---|---|
| Legenda Warna | 45% | ±25,1 cm | 12 kategori dengan swatch & teks |
| Kontak & Sosial | 20% | ±11,2 cm | Telepon, alamat singkat, website, Instagram |
| QR Code | 12% | ±6,7 cm | Kotak placeholder ±2,5×2,5 cm, border putus-putus |
| Catatan Penting | 23% | ±12,8 cm | 2–3 bullet + catatan item 12 Juli 2027 |

#### Lapis Bawah (1,4 cm) — Strip Document Control
Bergaya kop gambar teknik, 4 field sejajar dipisah garis vertikal tipis:
- Versi Dokumen
- Tanggal Revisi
- Nomor Revisi
- Disusun/Disetujui Oleh

---

## 2. STRUKTUR DESAIN — Grouping & Organisasi di Canva

Gunakan hierarki Grup berikut agar desain tetap aman saat direvisi:
