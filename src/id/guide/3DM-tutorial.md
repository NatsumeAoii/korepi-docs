---
title: Cara Menggunakan Skin Kustom (3DMigoto)
icon: magic-wand-sparkles
category:
  - Panduan
tag:
  - Buku Pemula
  - Skins
author: Schvis, NatsumeAoii, Chloe
order: 4
---

## Cara Menggunakan Skin Kustom dengan `3DMigoto (GIMI)`

![](/assets/images/docs/202312/example.png)

Untuk menggunakan skin kustom, Anda perlu menjalankan `GIMI` bersamaan dengan Korepi. Ada dua cara untuk melakukannya.

## Metode 1: Integrasi Otomatis dengan Korepi

### Langkah 1: Unduh `GIMI`
Unduh file `3dmigoto-GIMI-for-playing-mods.zip` dari [rilis resmi GIMI di GitHub](https://github.com/SilentNightSound/GI-Model-Importer/releases/tag/v7.0).

![](/assets/images/docs/202312/3dm-1.png)

### Langkah 2: Ekstrak `GIMI`
Ekstrak file zip tersebut ke sebuah folder. Salin path (alamat) dari file `d3d11.dll` yang ada di dalam folder `GIMI`. Contoh path: `C:\GIMI\d3d11.dll`.

### Langkah 3: Konfigurasi Korepi
Buka file `cfg.ini` di folder Korepi Anda. Tambahkan baris `DllPath =` di bawah `[DLL]`, lalu tempelkan path yang sudah Anda salin.

- Sebelum:

  ![](/assets/images/docs/202312/3dm-2.png)

- Sesudah:

  ![](/assets/images/docs/202312/3dm-3.png)

### Langkah 4: Jalankan Korepi
Sekarang, setiap kali Anda menjalankan Korepi, `GIMI` akan dimuat secara otomatis.

## Metode 2: Menjalankan Secara Manual

### Langkah 1: Unduh dan Ekstrak `GIMI`
Ikuti langkah 1 dan 2 dari metode pertama.

### Langkah 2: Jalankan Loader
Setiap kali Anda ingin menggunakan skin kustom, jalankan `3DMigoto Loader.exe` dari folder `GIMI` **sebelum** Anda menjalankan Korepi.

Dengan metode ini, Anda harus menjalankan loader secara manual setiap kali bermain.