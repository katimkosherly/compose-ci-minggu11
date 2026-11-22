# compose-ci-minggu11

![Compose Check](https://github.com/katimkosherly/compose-ci-minggu11/actions/workflows/compose-check.yml/badge.svg)

Stack WordPress + MySQL dengan Docker Compose. File Compose divalidasi otomatis oleh GitHub Actions setiap ada push ke `main` atau pull request.

## Cara menjalankan stack

1. Salin contoh konfigurasi: `cp .env.example .env`
2. Edit `.env` dan isi kata sandi sendiri.
3. Jalankan: `docker compose up -d`
4. Buka http://localhost:8000

File `.env` tidak ikut ke GitHub karena sudah ada di `.gitignore`.

## Catatan

Dibantu Claude (AI) untuk penjelasan langkah dan contoh file. Pengujian dan refleksi saya kerjakan sendiri.
