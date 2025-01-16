# Ds Correspondence

Ds Correspondence adalah aplikasi berbasis web yang sepenuhnya menggunakan **Python** untuk tampilan dan backend. Aplikasi ini dirancang untuk mempermudah pengelolaan korespondensi dokumen secara digital dengan menggunakan framework **Flask**.

## Fitur

- **Manajemen Dokumen**:
  - Tambah, edit, dan hapus data dokumen.
  - Pengkategorian dokumen berdasarkan jenis.
- **Sistem Autentikasi**:
  - Login dan logout untuk memastikan keamanan data.
- **Antarmuka Dinamis**:
  - Tampilan sepenuhnya dirender menggunakan Python dan Flask tanpa bergantung pada framework frontend.
- **Fitur Pencarian**:
  - Cari dokumen dengan mudah menggunakan fitur pencarian bawaan.

## Teknologi yang Digunakan

- **Backend dan Frontend**: Python Flask
- **Database**: SQLite (atau lainnya, sesuai konfigurasi)
- **Library Pendukung**:
  - Flask-Login
  - Flask-WTF
  - Flask-SQLAlchemy

## Instalasi

1. Clone repository ini:
   ```bash
   git clone https://github.com/NURMISBA23/Ds_Correspondence.git
   ```

2. Masuk ke direktori proyek:
   ```bash
   cd Ds_Correspondence
   ```

3. Buat virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate   # Untuk Linux/Mac
   venv\Scripts\activate    # Untuk Windows
   ```

4. Install dependensi:
   ```bash
   pip install -r requirements.txt
   ```

5. Jalankan aplikasi:
   ```bash
   flask run
   ```

6. Akses aplikasi melalui browser di:
   ```
   http://127.0.0.1:5000
   ```

```

## Cara Penggunaan

1. **Login**:
   - Masuk menggunakan akun yang telah terdaftar untuk mengakses fitur aplikasi.

2. **Manajemen Dokumen**:
   - Tambahkan dokumen baru melalui halaman "Tambah Dokumen".
   - Edit atau hapus dokumen yang sudah ada dari daftar dokumen.

3. **Pencarian Dokumen**:
   - Gunakan fitur pencarian untuk menemukan dokumen berdasarkan kata kunci tertentu.

## Kontribusi

Kontribusi sangat terbuka! Silakan fork repository ini, buat branch baru untuk fitur Anda, dan ajukan pull request.

1. Fork repository ini.
2. Buat branch baru:
   ```bash
   git checkout -b fitur-baru
   ```
3. Commit perubahan Anda:
   ```bash
   git commit -m "Menambahkan fitur baru"
   ```
4. Push branch Anda:
   ```bash
   git push origin fitur-baru
   ```
5. Ajukan pull request.


## Kontak

Untuk informasi lebih lanjut atau pertanyaan, silakan hubungi:
- **Nama**: NURMISBA23
- **GitHub**: [NURMISBA23](https://github.com/NURMISBA23)
