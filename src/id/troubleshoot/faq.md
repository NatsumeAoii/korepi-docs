---
title: FAQ (Tanya Jawab)
icon: info
category:
  - FAQ
tag:
  - Start
author: Schvis, Chloe, NatsumeAoii
order: 1
---

## Daftar Pertanyaan yang Sering Diajukan (FAQ)

### Apakah Korepi gratis?
Ya, Korepi memiliki versi gratis. Anda bisa mengikuti panduan untuk mendapatkannya di [halaman ini](../guide/free.md).

---
### Apa kata sandi untuk file .rar/.zip?
Kata sandinya adalah `1234`. Mohon untuk selalu membaca detail pada postingan unduhan dengan saksama.

---
### Mengapa konfigurasi saya tidak tersimpan?
Pastikan Anda sudah mengekstrak file `.rar` atau `.zip` ke dalam folder baru, bukan membukanya langsung dari dalam arsip. Jika masalah masih berlanjut, hubungi staf di server Discord kami untuk bantuan lebih lanjut.

---
### Di mana saya bisa menemukan tema (themes)?
Anda bisa menemukan berbagai tema buatan komunitas di channel `community-share`. Anda juga bisa membuat tema sendiri melalui menu pengaturan Korepi di bagian `Theme Customization`.

![](/assets/images/docs/202312/theme-settings.png)

---
### Bisakah saya menggunakan Korepi saat ada update game?
Tidak. Anda harus menunggu hingga Korepi diperbarui agar kompatibel dengan versi game terbaru.

::: info Menggunakan Korepi versi lama pada game versi baru tidak akan berfungsi. Proses pembaruan Korepi biasanya memakan waktu 1-2 minggu.
:::

---
### Mengapa menu Korepi tidak muncul di dalam game?
Pastikan Anda telah menonaktifkan semua program overlay (seperti MSI Afterburner, GeForce Experience, Discord Overlay, dll.) sebelum menjalankan Korepi.

---
### Di mana saya bisa mendapatkan status Sponsor dan berapa harganya?
Status Sponsor saat ini **sudah tidak tersedia lagi** dan menjadi peran legacy. Informasi lebih lanjut bisa dibaca [di sini](../start/sponsor.md).

---
### Mengapa game saya crash saat loading screen?
Jika Anda mengalami crash dengan pesan error yang mengandung `atidxx64.dll`, seperti:
`atidxx64.dll caused an Access Violation (0xc0000005) in module atidxx64.dll at 0033:43d1356c.`

Ini biasanya disebabkan oleh driver kartu grafis yang usang. Silakan perbarui driver GPU Anda ke versi terbaru.

Jika error yang Anda alami berbeda, coba tingkatkan nilai `Delay` di file `cfg.ini`.