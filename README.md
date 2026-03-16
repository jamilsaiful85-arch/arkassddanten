# Aplikasi RKAS - SD Negeri 1 Srimenganten

**NPSN: 10804776** | Kec. Pulau Panggung, Kab. Tanggamus, Prov. Lampung

Aplikasi web untuk mengelola **Rencana Kegiatan dan Anggaran Sekolah (RKAS)** Tahun Anggaran 2026 berbasis BOSP Reguler.

---

## Fitur Aplikasi

| Fitur | Keterangan |
|-------|-----------|
| 📊 Dashboard | Ringkasan anggaran, realisasi, dan progress per standar |
| 📋 Data RKAS | 109 item kegiatan lengkap dengan kode rekening |
| 🎯 8 Standar | Klasifikasi berdasarkan 8 Standar Nasional Pendidikan |
| ✅ Input Realisasi | Catat pengeluaran dengan validasi pagu anggaran |
| 📄 Laporan | Generate laporan realisasi per triwulan |
| 🖨️ Cetak Dokumen | Bukti Kas Pengeluaran, Kwitansi, Nota Pembelian |
| 🤖 AI Asisten | Analisis anggaran berbasis data real via Claude AI |
| ⏰ Jam Real-time | Tampilan waktu dan tanggal berjalan |

---

## Data Anggaran

- **Sumber Dana:** BOSP Reguler
- **Total Anggaran:** Rp 109.800.000
- **Distribusi Triwulan:** TW I-IV masing-masing Rp 27.450.000

### Anggaran per Standar

| Standar | Jumlah |
|---------|--------|
| 02 - Standar Isi | Rp 644.000 |
| 03 - Standar Proses | Rp 12.035.000 |
| 04 - Standar Tenaga Kependidikan | Rp 1.395.000 |
| 05 - Standar Sarana & Prasarana | Rp 52.754.500 |
| 06 - Standar Pengelolaan | Rp 21.235.500 |
| 07 - Standar Pembiayaan | Rp 11.560.000 |
| 08 - Standar Penilaian | Rp 10.176.000 |

---

## Cara Menggunakan di GitHub Pages

### 1. Upload ke GitHub

```bash
# Clone repository Anda
git clone https://github.com/USERNAME/NAMA-REPO.git

# Copy file ke folder repo
cp index.html NAMA-REPO/

# Push ke GitHub
cd NAMA-REPO
git add index.html README.md
git commit -m "Upload Aplikasi RKAS SDN 1 Srimenganten"
git push origin main
```

### 2. Aktifkan GitHub Pages

1. Buka repository di GitHub.com
2. Klik **Settings** (tab di atas)
3. Scroll ke **Pages** (menu kiri)
4. Di **Source**, pilih **Deploy from a branch**
5. Pilih branch: **main**, folder: **/ (root)**
6. Klik **Save**
7. Tunggu 1-3 menit
8. URL aplikasi: `https://USERNAME.github.io/NAMA-REPO/`

### 3. Embed di Blog (opsional)

Setelah GitHub Pages aktif, embed ke blog dengan:

```html
<iframe 
  src="https://USERNAME.github.io/NAMA-REPO/" 
  width="100%" 
  height="900" 
  frameborder="0" 
  style="border:none; width:100%; min-height:900px"
  allow="clipboard-write">
</iframe>
```

---

## Pejabat Sekolah

| Jabatan | Nama | NIP |
|---------|------|-----|
| Kepala Sekolah | Saiful Jamil, S.Pd. | 198508102014061003 |
| Bendahara | Adi Sucipto, S.Pd. | 199009252023211006 |
| Komite Sekolah | Soma Wijaya | - |
| Pengawas Ahli Madya | Dedi Supriyadi, S.Pd.SD., M.Pd. | 197706202000121003 |

---

## Teknologi

- HTML5, CSS3, JavaScript (Vanilla - tanpa framework)
- AI: Claude API (Anthropic) - `claude-sonnet-4-20250514`
- Tidak memerlukan server backend
- Berjalan sepenuhnya di browser

---

*SD Negeri 1 Srimenganten | Jl. Raya Babakan Linggar RT 001 RW 002, Kec. Pulau Panggung, Kab. Tanggamus, Prov. Lampung*
