---
title: Cara Mendapatkan dan Mengelola Lisensi (Key)
icon: key
category:
  - Panduan
tag:
  - Buku Pemula
  - Lisensi
author: Schvis, NatsumeAoii, Chloe, RodanZ
order: 1
---

## Panduan Verifikasi Lisensi

<div class="iframe-container"><iframe width="1280" height="720" src="https://www.youtube.com/embed/x_fIDmyQJiI" title="How to use Pertamax" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe></div>

::: danger PERINGATAN PENTING
JANGAN menautkan kartu lisensi baru jika Anda sudah memiliki langganan aktif. Tindakan ini akan **MENGHANGUSKAN** sisa langganan Anda saat ini tanpa ada kompensasi.
:::

### Langkah 1: Akses Bot Verifikasi
-   Temukan channel `★⋅micah-bot-verify⋅★` di server atau klik [di sini](https://discord.com/channels/1069057220802781265/1203687333107335198).
    ![img.png](/assets/images/docs/202402/verify-1.png)
-   Anda akan melihat pesan dari Micah-bot dengan beberapa tombol.

### Langkah 2: Ikat Lisensi Anda
-   **Untuk Lisensi Gratis:** Ikuti panduan di [halaman ini](free.md).
-   **Untuk Lisensi Berbayar (PERTAMAX):** Jika Anda membeli kunci dari reseller, klik tombol `Bind card str` dan masukkan kunci yang Anda terima.
-   **Untuk Menambah Durasi:** Jika Anda sudah punya lisensi aktif dan ingin menambah durasinya, gunakan tombol `Stack card str`.

### Langkah 3: Dapatkan File Verifikasi
::: info Jika Anda sudah memiliki file `enc.json` di folder Korepi, hapus file tersebut terlebih dahulu.
:::
1.  Jalankan `injector.exe` sekali untuk mendapatkan `HWID` (ID Perangkat) Anda. `HWID` akan muncul di jendela command prompt.
2.  Kembali ke Micah-bot, klik `Get verification file`, lalu masukkan `HWID` yang baru saja Anda dapatkan.
3.  Bot akan mengirimkan file `enc.json`. Unduh file ini dan letakkan di dalam folder Korepi Anda.

---
## Opsi Manajemen Lisensi

### Melihat Informasi Langganan
Klik `View Subscription Information` untuk melihat detail dan sisa masa aktif lisensi Anda.

### Menjeda Lisensi (Pause)
Klik `Pause Card` dan ketik `YES` untuk konfirmasi. Fitur ini akan menghentikan sementara hitungan mundur langganan Anda. Anda dapat melanjutkannya (unpause) kapan saja.
::: info Anda hanya dapat menjeda lisensi setiap 30 hari sekali.
:::

### Mengubah HWID (ID Perangkat)
Jika Anda berganti PC, Anda bisa mengubah HWID.
1. Klik `Unbind (Change HWID)`, lalu masukkan `HWID` baru Anda.
2. Dapatkan kembali file `enc.json` baru seperti pada Langkah 3 di atas.
::: info Anda hanya dapat mengubah HWID setiap 7 hari sekali.
:::

### Masalah Verifikasi MD5
Jika Anda mendapatkan error MD5, itu berarti file `enc.json` Anda tidak valid.
- Pastikan Anda menggunakan `enc.json` yang paling baru diunduh.
- Jika masih error, coba dapatkan kembali file `enc.json` dari bot.