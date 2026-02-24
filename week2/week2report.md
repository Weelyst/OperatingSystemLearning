Averose Arthur R
254107020042
TI - 1H

Praktikum 2.1
week2\images\2.1\free -h.jpg
week2\images\2.1\lscpu.jpg

Latihan 2.1
Catat: (1) jumlah CPU(s), core/thread, (2) total RAM, (3) total swap. Jelaskan perbedaan RAM vs swap dalam 2–3 kalimat.
1. 1 core, 1 thread
2. 1.9G
3. 2.0G

Swap adalah storage yang dapat menggantikan Ram ketika process ram

Praktikum 2.2
1.lspci test
week2\images\2.2\lspci.jpg

2.lspci nnk
week2\images\2.2\lspci _nnk.jpg

3.ls usb list
week2\images\2.2\lsusb_t.jpg

Latihan 2.2
Temukan 1 perangkat PCI (misal NIC) dan tuliskan: Vendor:Device ID (angka
heksadesimal), nama driver/modul kernel, dan deskripsi singkat fungsinya.

Answer:
Ethernet controller: Intel Corp 82540EM Gigabit Ethernet Controller (Rev 02)
memberi akses menghubungkan thd internet

Praktikum 2.3 — Identifikasi Storage dan Filesystem
1.
week2\images\2.3\1.lsblkf.jpg
2.
week2\images\2.3\2.sudoblkid.jpg
3.
week2\images\2.3\findmnt.jpg

Praktikum 2.4 — Melihat Modul Aktif dan
Informasinya
1.
week2\images\2.4\unameR.jpg
2.
week2\images\2.4\2.lsmodhead.jpg
3.
week2\images\2.4\3.modinfoloop.jpg

Praktikum 2.5 — Konfigurasi Auto-load dan Blacklist
1.create
week2\images\2.5\1.create_fileautoload.jpg
2.loop
week2\images\2.5\looptest.jpg

Praktikum 2.6 — Mengenali Block vs Character
Device
1.week2\images\2.6\1.devsda.jpg

2.week2\images\2.6\2devtty.jpg

3.week2\images\2.6\3.lsblk.jpg


Latihan 2.3
Dari output ls -l, jelaskan perbedaan penanda file untuk block device dan
character device. (Hint: karakter pertama pada permission string)

Block Device Menggunakan B
Character Device Menggunakan C

Praktikum 2.7 — Melihat Informasi udev
week2\images\2.7\1.lihatatribut_udev.jpg
Praktikum 2.8 — Membuat Workspace Praktikum
week2\images\2.8\making_and_changing_directory.jpg
week2\images\2.8\2.filecontoh.jpg
week2\images\2.8\cat_data_log.jpg
week2\images\2.8\lessdatalog.jpg
Praktikum 2.9 — Pencarian Pola dengan grep
week2\images\2.9\1.grep.jpg
week2\images\2.9\2.grep.jpg
week2\images\2.9\3.grep.jpg
week2\images\2.9\4.grep.jpg
Praktikum 2.10 — Substitusi dengan sed (Aman di File Latihan)
week2\images\2.10\1..jpg
week2\images\2.10\2..jpg
week2\images\2.10\3..jpg
week2\images\2.10\4..jpg

Latihan 2.4
Gunakan grep untuk menampilkan hanya baris yang mengandung INFO atau
WARN dari data.log. (Hint: gunakan grep -E dengan pola alternatif)
week2\images\training2.4.jpg

Praktikum 2.11 — Ekstraksi Kolom dengan awk
week2\images\2.11\1..jpg
week2\images\2.11\2..jpg
week2\images\2.11\3..jpg

Praktikum 2.12 — Melihat Proses dengan ps
week2\images\2.12\1.jpg
week2\images\2.12\2..jpg

Praktikum 2.13 — Monitoring Real-time dengan top
week2\images\2.13\top.jpg

Praktikum 2.14 — Menghentikan Proses dengan kill
week2\images\2.14\1..jpg
week2\images\2.14\2..jpg
week2\images\2.14\3..jpg
week2\images\2.14\4.jpg

Praktikum 2.15 — Cek Disk, Load, dan Service

week2\images\2.15\1.chck_disk.jpg
week2\images\2.15\2.bigdir.jpg
week2\images\2.15\3.uptime.jpg
week2\images\2.15\4.check_fail.jpg

Praktikum 2.16 — Monitoring Port dan Koneksi
(Network Basics)
week2\images\2.16\1.ip_a.jpg
week2\images\2.16\2.ip_r.jpg
week2\images\2.16\3.listentulpn.jpg

Latihan 2.5
Pilih satu port yang listening dari output ss -tulpn(misal port 22), lalu
tuliskan service/proses yang membukanya. Jelaskan kegunaan port tersebut
secara singkat

week2\images\2.16\test2.jpg
system PID
Port 22 secara standar digunakan untuk protokol SSH (Secure Shell).


Latihan 2.A
Jalankan lspci -nnk. Pilih 1 perangkat PCI dan tuliskan: nama perangkat,
ID vendor:device, dan kernel driver in use.
USB Controller, 8086
kernel driver in use : ehci-pci

Latihan 2.B
Tentukan device root filesystem dengan findmnt /. Lalu cocokkan dengan
lsblk -f dan tuliskan tipe filesystem serta UUID-nya.
sda3,LVM2_member, E7JcKp-Fq7f-AXFc-0ftQ-BbAH-zfr9-oiGDvcca

Latihan 2.C
Buat file server.log berisi minimal 10 baris dengan variasi kata: INFO,
WARN, ERROR. Gunakan grep untuk menampilkan hanya baris ERROR.
week2\images\PRAC_C.jpg
Latihan 2.D
Gunakan sed untuk mengganti semua kata server menjadi node pada file
latihan. Tunjukkan sebelum dan sesudah.
week2\images\PRAC_D.jpg

Latihan 2.E
Gunakan df -h lalu awk untuk menampilkan filesystem yang penggunaan disk
di atas 70%.

Tidak Ada

Latihan 2.F
Jalankan sleep 600 &. Temukan PID-nya dengan ps. Hentikan dengan
SIGTERM. Jelaskan beda SIGTERM vs SIGKILL.
week2\images\PRAC_F.jpg

sigterm dapat membunuh dummy yg ringan
SIGKIlL dapat membunuh dummy yang sulit di end

Latihan 2.G
Gunakan systemctl –failed. Jika tidak ada yang gagal, pilih satu service
aktif (misal ssh) dan tampilkan status serta 30 baris log terakhirnya.
week2\images\PRAC_G.jpg