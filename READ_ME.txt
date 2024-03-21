Tabel Profil:

ID (Primary Key)
Nama
Jurusan
Deskripsi
FotoProfil (URL ke gambar)

CREATE TABLE Profile (
    ID INT AUTO_INCREMENT PRIMARY KEY,
    Nama VARCHAR(255),
    Jurusan VARCHAR(255),
    Deskripsi TEXT,
    FotoProfil VARCHAR(255)
);

=======================

Tabel Pengalaman:

ID (Primary Key)
Judul
Deskripsi
Level

CREATE TABLE Experience (
    ID INT AUTO_INCREMENT PRIMARY KEY,
    Judul VARCHAR(255),
    Deskripsi TEXT,
    Level VARCHAR(50)
);

=======================

Tabel Proyek:

ID (Primary Key)
NamaProyek
Deskripsi
Gambar (URL ke gambar)

CREATE TABLE Projects (
    ID INT AUTO_INCREMENT PRIMARY KEY,
    NamaProyek VARCHAR(255),
    Deskripsi TEXT,
    Gambar VARCHAR(255)
);


=======================

Tabel Kontak:

ID (Primary Key)
Email
LinkedIn

CREATE TABLE Contact (
    ID INT AUTO_INCREMENT PRIMARY KEY,
    Email VARCHAR(255),
    LinkedIn VARCHAR(255)
);