# Sistem Pengurusan Cuti Gantian

Sistem web untuk mengurus rekod kerja lebih masa (OT) dan permohonan cuti gantian menggunakan Google Sheets dan Google Apps Script.

## Ciri-Ciri
- Tambah, edit, dan padam rekod OT.
- Mohon cuti dengan pengiraan jam automatik.
- Papan pemuka dengan metrik baki jam, jam digunakan, dan jam akan luput.
- Carta bar untuk visualisasi data.
- Responsif untuk desktop dan mudah alih.

## Persediaan
1. **Google Spreadsheet**: Gunakan [URL ini](https://docs.google.com/spreadsheets/d/178pd06MaGzZvPfc5QbSzOL3p3o47mji-rJ_NGaJMGsg/edit) dengan helaian "DataMasuk" dan "RekodCuti".
2. **Google Apps Script**: Salin `Code.gs` dan terbitkan sebagai aplikasi web.
3. **Frontend**: Hos `index.html` di GitHub Pages (URL: https://aneep477.github.io/borang-cuti-gantian).

## Cara Menggunakan
- Buka [https://aneep477.github.io/borang-cuti-gantian](https://aneep477.github.io/borang-cuti-gantian).
- Tambah rekod OT atau mohon cuti.
- Data disimpan di Google Sheets secara automatik.

## Keselamatan
- Gunakan token API untuk pengesahan.
- CORS dihadkan kepada domain GitHub Pages.

## Titik Pemulihan
Ini adalah versi stabil. Gunakan Git untuk versi.

Dibina pada 23 September 2025.
