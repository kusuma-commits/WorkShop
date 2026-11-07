# 📓 Catatan Pembelajaran - Day 1 Workshop Expectik 2026

**Nama Peserta:** Habib Muhammad Kusuma  
**Program Studi:** Teknik Informatika  
**Institusi:** Politeknik Negeri Jakarta  
**Tanggal:** 7 November 2026  

---

## 1. Poin-Poin Penting Git & Version Control

- **Version Control System (VCS)** adalah sistem yang mencatat perubahan pada sebuah atau sekumpulan berkas dari waktu ke waktu sehingga kita dapat memanggil kembali versi tertentu di kemudian hari.
- **Git** bekerja secara terdistribusi (*distributed VCS*), artinya setiap pengembang memiliki salinan lengkap dari riwayat proyek di komputer lokal masing-masing.
- Tiga status utama dalam Git:
  1. **Working Directory:** Area kerja tempat kita mengedit file.
  2. **Staging Area (Index):** Area persiapan sebelum file diabadikan ke dalam commit.
  3. **Repository (.git):** Tempat penyimpanan permanen seluruh histori commit.

### Perintah Penting:
```bash
# Inisialisasi repositori lokal baru
git init

# Menghubungkan lokal repository ke GitHub
git remote add origin https://github.com/kusuma-commits/WorkShop.git

# Memeriksa status file
git status

# Menambahkan perubahan ke staging area
git add README.md
git add .

# Menyimpan perubahan ke repository lokal
git commit -m "docs: menambahkan dokumentasi Day 1 workshop"

# Mengirimkan commit lokal ke GitHub
git push origin main
```

---

## 2. Praktik Terbaik Penulisan Markdown (`README.md`)

- Gunakan heading (`#`, `##`, `###`) secara hierarkis dan konsisten.
- Gunakan tabel untuk menyajikan data identitas atau ringkasan agar mudah dibaca oleh penilai.
- Tambahkan blockquote (`>`) untuk penekanan refleksi pribadi atau catatan khusus.
- Gunakan code block (tiga backticks ```) dengan penanda sintaks bahasa pemodelan/pemrograman.
- Pastikan tautan (*links*) bersifat aktif dan mengarah ke URL yang valid.

---

## 3. Catatan Terkait Lingkungan Akademik TIK PNJ

- **Sistem Pembelajaran OBE:** Penilaian berfokus pada capaian kompetensi riil mahasiswa, tidak hanya hafalan materi.
- **PBL (Project-Based Learning):** Mahasiswa dilatih memecahkan permasalahan dunia nyata melalui proyek nyata berkelompok.
- **Etika Laboratorium TIK:** Disiplin waktu, menjaga kebersihan dan kelayakan perangkat, serta mematuhi protokol keselamatan kerja di lingkungan laboratorium komputer.
