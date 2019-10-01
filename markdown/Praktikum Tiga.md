# Praktikum 3: Shell, Perintah Dasar, Teks Editor

![bash](img/bash.png)

## Outline

- [Shell.](##Shell)
- [Perintah Dasar.](##Perintah Dasar)
- [Vim.](##Vim)
- [Challenge.](##Challenge)

## Shell

#### Teori

- Apa itu Shell?
- Jenis-jenis Shell:
  - Korn.
  - C.
  - Bourne.
  - **Bash (Bourne-Again Shell)**.

#### Praktikum

- Mengecek versi Shell: `echo $0`.

## Perintah Dasar

#### Teori

- Command atau perintah.
- Perintah dasar terminal:
  - `ls`: melihat isi direktori.
  - `cd`: pindah direktori.
  - `pwd`: cek posisi sekarang.
  - `mkdir`: membuat direktori.
  - `touch`: membuat file.
  - `cp`: mengcopy file atau direktori.
  - `mv`: memindahkan file atau direktori.
  - `cat`: membaca file.

#### Praktikum

Syntax penulisan command: `command-name [-options] <argument>`.

**1. Cek posisi sekarang:** `pwd`

- cek posisi sekarang: `pwd`

**2. Melihat isi direktori:** `ls`

- Melihat isi direktori: `ls`
- Melihat isi direktori (format list): `ls -l`
- Melihat isi direktori Download: `ls -l Download`

**3. Berpindah direktori:** `cd`

- Cek posisi sekarang: `pwd`
- Pindah ke direktori Download: `cd Download`
- Cek posisi sekarang: `pwd`

**4. Membuat direktori:** `mkdir`

- Membuat direktori belajar: `mkdir Belajar`
- Pindah ke direktori belajar: `cd Belajar`
- Cek posisi sekarang: `pwd`

**5. Membuat file:** `touch`

- Membuat file praktikum: `touch praktikum`
- Membuat file index.html: `touch index.html`
- Melihat isi direktori: `ls -l`

**6. Menghapus folder kosong:** `rmdir`

- Membuat direktori HTML: `mkdir HTML`
- Menghapus direktori HTML: `rmdir HTML`

**7. Menghapus file atau folder:** `rm`

- **Menghapus file**
  - Membuat file index.php: `touch index.php`
  - Menghapus file index.php: `rm index.php`
- **Menghapus direktori (Not Empty)**
  - Membuat direktori PHP: `mkdir PHP`
  - Membuat file index.php di direktori PHP: `touch PHP/index.php`
  - Menghapus direktori PHP: `rmdir PHP`
  - Meihat isi direktori PHP: `ls -l PHP`
  - Menghapus direktori PHP: `rm -r PHP`
  - Melihat isi direktori: `ls -l`

**8. Mengcopy file atau folder:** `cp`

- Membuat file index.html: `touch index.html`
- Mengcopy file index.html: `cp index.html contact.html`
- Membuat direktori HTML: `mkdir HTML`
- Mengcopy direktori HTML: `cp HTML HTML-BACKUP`

## Vim

#### Teori

- Apa itu Vim?
- Jenis teks editor:
  - Sublime Text 3.
  - Visual Studio Code.
  - Vi atau Vim.

#### Praktikum

**1. Membuka Vim**

- Buka vim: `vim.tiny` atau `vim.tiny nama-file`

**2. Mode Vim**

- **Editor**: mode untuk menjalankan perintah.
- **Insert**: mode untuk menulis.

**3. Menulis di Vim**

- tekan tombol `a` atau `i`.
- tulis kalimat berikut: **Belajar Teks Editor Vim**.

**4. Menyimpan file**

- masuk ke mode **editor** (tekan `esc`).
- simpan file: `:wq`.

## Challenge

1. Buat direktori HTML
   - pindah ke direktori HTML.
   - cek posisi sekarang.
   - buat file index.html dan style.css.
2. Buat direktori belajar
   - pindahkan direktori HTML ke direktori belajar.
   - masuk ke direktori belajar.
   - cek posisi sekarang.
   - tampilkan isi direktori sekarang (belajar).
3. Hapus direktori belajar
   - tampilkan isi direktori sekarang
4. Buat file latihan di vim
   - tuliskan biodata diri yang berisi: nama, alamat, umur, kuliah, jurusan, nim.
   - simpan file tersebut
5. Apa evaluasi praktikum ketiga? apa masukan dan saran?