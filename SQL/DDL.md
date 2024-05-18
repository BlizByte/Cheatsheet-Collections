# DDL (Data Definition Languange)
DDL adalah bagian dari SQL (Structured Query Language) yang digunakan untuk mendefinisikan struktur objek dalam database. Ini mencakup perintah-perintah untuk membuat, mengubah, dan menghapus objek database seperti tabel, indeks, tampilan, dan lainnya.

# Perintah DDL

- CREATE
digunakan untuk membuat atau mendefinsikan objek database baru, seperti: tabel, index atau tampilan.

CREATE untuk membuat database baru

```sql
CREATE DATABASE nama_database;
```

Contoh implementasi CREATE untuk membuat database baru

```sql
CREATE DATABASE perpustakaan;
```

CREATE untuk membuat tabel

```sql
CREATE TABLE nama_tabel (
    kolom1 tipe_data,
    kolom2 tipe_data,
);
```

Contoh Implementasi CREATE 

```sql
CREATE TABLE buku (
    no_buku int(10),
    judul_buku varchar(100),
);
```

Berikut daftar tipe data

| Tipe Data | Deskripsi                       |
|-----------|---------------------------------|
| INTEGER   | Bilangan bulat                  |
| VARCHAR   | Teks dengan panjang variabel    |
| CHAR      | Teks dengan panjang tetap       |
| DECIMAL   | Angka desimal dengan presisi    |
| DATE      | Tanggal dalam format YYYY-MM-DD |
| TIME      | Waktu dalam format HH:MM:SS     |
| BOOLEAN   | Nilai true atau false           |
| BLOB      | Data biner (gambar atau file)   |

