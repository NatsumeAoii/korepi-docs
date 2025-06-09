---
title: Daftar Masalah Umum dan Solusinya
icon: server
category:
  - Solusi
tag:
  - Mulai
author: Schvis, Chloe, NatsumeAoii
order: 2
---

## Daftar Masalah Umum dan Solusinya

### Korepi saya hilang atau terhapus sendiri.
Ini disebabkan oleh antivirus yang mendeteksinya sebagai ancaman.
1.  Nonaktifkan antivirus Anda untuk sementara.
2.  Buat folder baru khusus untuk Korepi.
3.  Tambahkan folder tersebut ke dalam daftar pengecualian (exceptions list) di antivirus Anda. Lihat caranya [di sini](./virus.md).
4.  Ekstrak kembali file Korepi ke dalam folder yang sudah dikecualikan tersebut.

![Anti-Virus](/assets/images/docs/202312/virus.png)

---
### Status: `No active subscription(s) found` atau `Invalid license key`
Lisensi Anda tidak valid atau tidak ditemukan.
-   Ambil lisensi baru di channel `🔐｜verification` dengan mengikuti panduan [di sini](../guide/getkey.md).
-   Jika Anda tidak dapat mengambil lisensi baru, kemungkinan lisensi lama Anda masih aktif. Tunggu hingga masa berlakunya habis.
-   **Sponsor** dapat menggunakan `F:Reset Key` untuk mengatur ulang lisensi mereka.

---
### Error: `[DLL injection] Process crashed, exit code 0xc000005` atau `UserAssembly.dll isn't initialized`
Kedua error ini menandakan adanya file sistem Windows yang korup atau diblokir.
1.  **Matikan semua antivirus** di komputer Anda, termasuk Windows Defender.
2.  Buka **Command Prompt (CMD)** sebagai **Administrator**.
3.  Ketik perintah `sfc /scannow` dan tekan Enter. Tunggu hingga proses selesai.
4.  Jika masalah ditemukan, restart komputer Anda.
5.  Jika tidak ada masalah atau restart tidak membantu, jalankan perintah kedua: `DISM.exe /Online /Cleanup-Image /RestoreHealth`.
6.  Setelah selesai, restart komputer Anda lagi.
7.  Jika semua gagal, pertimbangkan untuk menginstal ulang Windows.

---
### Error: `ImGUI: DirectX11 backend initialized successfully` (tapi menu tidak muncul)
Masalah ini biasanya disebabkan oleh tema yang korup. Hapus semua file di dalam folder `themes` Anda.

---
### Error: `The system did not detect MSVCP140.dll`
Ini berarti ada komponen Windows penting yang hilang.
-   Instal/perbarui [Microsoft Visual Studio C++](https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-170#visual-studio-2015-2017-2019-and-2022).
-   Instal/perbarui [DirectX](https://www.microsoft.com/en-us/download/details.aspx?id=35).

---
### Error: `File corrupted! This program has been manipulated...`

![](/assets/images/docs/202312/virus2.png)

Ini adalah tanda adanya infeksi virus atau malware di komputer Anda.
1.  Gunakan antivirus terpercaya seperti `Malwarebytes` atau `Dr.Web` untuk melakukan pemindaian penuh pada sistem.
2.  Jika virus ditemukan, bersihkan, restart komputer, dan coba lagi.
3.  Jika tidak berhasil, instal ulang Windows adalah solusi terbaik.

---
### Error: `Timeout was reached`

![](/assets/images/docs/202312/error1.png)

Masalah ini terkait dengan koneksi internet.
-   Restart router internet Anda.
-   Pastikan tidak ada aplikasi firewall atau antivirus yang memblokir koneksi Korepi.

---
### Error: `SSL connect error`

![](/assets/images/docs/202312/error4.png)

Masalah koneksi ke server.
-   Restart komputer dan router Anda.
-   Jika tidak berhasil, coba gunakan VPN.

---
### Error: `DLL Injection failed`
File `colorpicker` kemungkinan korup. Hapus folder `colorpicker` dan unduh ulang dari sumber resmi.

---
### Error: `Windows cannot access the specified device, path, or file`

![](/assets/images/docs/202312/error2.png)

Ini bisa disebabkan oleh izin folder atau blokir oleh antivirus.
1.  Ikuti panduan resmi dari [Microsoft Support di sini](https://support.microsoft.com/en-us/topic/-windows-cannot-access-the-specified-device-path-or-file-error-when-you-try-to-install-update-or-start-a-program-or-file-46361133-47ed-6967-c13e-e75d3cc29657).
2.  Jika tidak berhasil, lanjutkan dengan perbaikan file sistem (`sfc /scannow` dan `DISM`) seperti yang dijelaskan di atas.

---
### Error: `Signature checksum failed`

![](/assets/images/docs/202312/checksum.png)

Server Korepi sedang offline atau dalam pemeliharaan. Silakan tunggu hingga server kembali online.

---
### Error: `Failed to create game process with Error 5`

![](/assets/images/docs/202312/error3.png)

Hapus file `cfg.ini` dari folder Korepi Anda dan coba jalankan kembali.

---
### Error: `Failed to detect game version`
Error ini berarti versi Korepi Anda sudah usang. Silakan unduh versi terbaru dengan mengikuti [panduan unduhan](../start/download.md).

---
### Error: `File ok` (tapi tidak berjalan)
1.  Coba jalankan launcher beberapa kali. Terkadang ini bisa mengatasi masalah sementara.
2.  Hapus file `cfg.json` dari folder Korepi Anda. File ini mungkin korup.
3.  Jika masih gagal, ikuti solusi yang lebih mendalam dari [postingan Discord ini](https://discord.com/channels/1069057220802781265/1213319789964038184/1242491428441952256).

---
### Error: `Current data does not exist or server error`

![](/assets/images/docs/202312/error.png)

Lisensi Anda mungkin sedang dijeda (paused). Buka channel `🔐｜verification`, klik tombol untuk membatalkan jeda (unpause) lisensi Anda, dan coba lagi.

---
### Error: `Cannot verify current timestamp`

![](/assets/images/docs/202402/timestamp.png)

-   **Kasus 1**: Anda menggunakan VPN. Matikan VPN Anda dan coba lagi.
-   **Kasus 2**: Waktu di komputer Anda tidak sinkron. Pastikan pengaturan jam di PC Anda diatur untuk sinkronisasi otomatis dengan internet.

---
### Error: `Unable to open file to write public key`
Error ini biasanya terjadi jika game Anda terpasang di drive sekunder (seperti `D:\`) dan bukan di drive utama (`C:\`).
**Solusi:** Coba pindahkan atau instal ulang game ke drive utama (`C:\`).

---
### Error: `Failed to get response from https://md5c...`
Error ini menandakan koneksi Anda ke server verifikasi gagal.
-   Coba buka tautan `https://md5c...` tersebut langsung di browser Anda.
-   Jika halaman tidak bisa diakses, kemungkinan koneksi Anda diblokir. Gunakan VPN untuk mengatasinya.

---
### Error: `Received code is not 200 from https://md5c...`
Error ini terjadi jika lisensi (key) Anda sedang dijeda (paused).
**Solusi:** Buka channel `🔐｜verification`, klik `Unpause Key`, dan konfirmasi dengan mengetik `Yes`.