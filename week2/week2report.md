# Averose Arthur R
| 254107020042 | TI - 1H |

## Praktikum 2.1

![free-h](https://github.com/Weelyst/OperatingSystemLearning/blob/main/week2/images/2.1/free-h.jpg)
![lscpu](https://github.com/Weelyst/OperatingSystemLearning/blob/main/week2/images/2.1/lscpu.jpg)

### Latihan 2.1
Catat: (1) jumlah CPU(s), core/thread, (2) total RAM, (3) total swap. Jelaskan perbedaan RAM vs swap dalam 2–3 kalimat.

1. 1 core, 1 thread
2. 1.9G
3. 2.0G

**Swap** adalah storage yang dapat menggantikan RAM ketika proses RAM penuh.

---

## Praktikum 2.2

1. lspci test

![lspci](https://github.com/Weelyst/OperatingSystemLearning/blob/main/week2/images/2.2/lspci.jpg)

2. lspci nnk

![lspci_nnk](https://github.com/Weelyst/OperatingSystemLearning/blob/main/week2/images/2.2/lspci_nnk.jpg)

3. ls usb list

![lsusb_t](https://github.com/Weelyst/OperatingSystemLearning/blob/main/week2/images/2.2/lsusb_t.jpg)

### Latihan 2.2
Temukan 1 perangkat PCI (misal NIC) dan tuliskan: Vendor:Device ID (angka heksadesimal), nama driver/modul kernel, dan deskripsi singkat fungsinya.

**Answer:** Ethernet controller: Intel Corp 82540EM Gigabit Ethernet Controller (Rev 02) memberi akses menghubungkan internet.

---

## Praktikum 2.3 — Identifikasi Storage dan Filesystem

1. ![lsblkf](https://github.com/Weelyst/OperatingSystemLearning/blob/main/week2/images/2.3/1.lsblkf.jpg)

2. ![sudoblkid](https://github.com/Weelyst/OperatingSystemLearning/blob/main/week2/images/2.3/2.sudoblkid.jpg)

3. ![findmnt](https://github.com/Weelyst/OperatingSystemLearning/blob/main/week2/images/2.3/findmnt.jpg)

---

## Praktikum 2.4 — Melihat Modul Aktif dan Informasinya

1. ![unameR](https://github.com/Weelyst/OperatingSystemLearning/blob/main/week2/images/2.4/unameR.jpg)

2. ![lsmodhead](https://github.com/Weelyst/OperatingSystemLearning/blob/main/week2/images/2.4/2.lsmodhead.jpg)

3. ![modinfoloop](https://github.com/Weelyst/OperatingSystemLearning/blob/main/week2/images/2.4/3.modinfoloop.jpg)

---

## Praktikum 2.5 — Konfigurasi Auto-load dan Blacklist

1. ![create_fileautoload](https://github.com/Weelyst/OperatingSystemLearning/blob/main/week2/images/2.5/1.create_fileautoload.jpg)

2. ![looptest](https://github.com/Weelyst/OperatingSystemLearning/blob/main/week2/images/2.5/looptest.jpg)

---

## Praktikum 2.6 — Mengenali Block vs Character Device

1. ![devsda](https://github.com/Weelyst/OperatingSystemLearning/blob/main/week2/images/2.6/1.devsda.jpg)

2. ![devtty](https://github.com/Weelyst/OperatingSystemLearning/blob/main/week2/images/2.6/2devtty.jpg)

3. ![lsblk](https://github.com/Weelyst/OperatingSystemLearning/blob/main/week2/images/2.6/3.lsblk.jpg)

### Latihan 2.3
Dari output `ls -l`, jelaskan perbedaan penanda file untuk block device dan character device. (Hint: karakter pertama pada permission string)

- **Block Device:** Menggunakan `b`
- **Character Device:** Menggunakan `c`

---

## Praktikum 2.7 — Melihat Informasi udev

![lihatatribut_udev](https://github.com/Weelyst/OperatingSystemLearning/blob/main/week2/images/2.7/1.lihatatribut_udev.jpg)

---

## Praktikum 2.8 — Membuat Workspace Praktikum

![making_and_changing_directory](https://github.com/Weelyst/OperatingSystemLearning/blob/main/week2/images/2.8/making_and_changing_directory.jpg)

![filecontoh](https://github.com/Weelyst/OperatingSystemLearning/blob/main/week2/images/2.8/2.filecontoh.jpg)

![cat_data_log](https://github.com/Weelyst/OperatingSystemLearning/blob/main/week2/images/2.8/cat_data_log.jpg)

![lessdatalog](https://github.com/Weelyst/OperatingSystemLearning/blob/main/week2/images/2.8/lessdatalog.jpg)

---

## Praktikum 2.9 — Pencarian Pola dengan grep

![grep1](https://github.com/Weelyst/OperatingSystemLearning/blob/main/week2/images/2.9/1.grep.jpg)

![grep2](https://github.com/Weelyst/OperatingSystemLearning/blob/main/week2/images/2.9/2.grep.jpg)

![grep3](https://github.com/Weelyst/OperatingSystemLearning/blob/main/week2/images/2.9/3.grep.jpg)

![grep4](https://github.com/Weelyst/OperatingSystemLearning/blob/main/week2/images/2.9/4.grep.jpg)

---

## Praktikum 2.10 — Substitusi dengan sed (Aman di File Latihan)

![sed1](https://github.com/Weelyst/OperatingSystemLearning/blob/main/week2/images/2.10/1..jpg)

![sed2](https://github.com/Weelyst/OperatingSystemLearning/blob/main/week2/images/2.10/2..jpg)

![sed3](https://github.com/Weelyst/OperatingSystemLearning/blob/main/week2/images/2.10/3..jpg)

![sed4](https://github.com/Weelyst/OperatingSystemLearning/blob/main/week2/images/2.10/4..jpg)

### Latihan 2.4
Gunakan grep untuk menampilkan hanya baris yang mengandung INFO atau WARN dari data.log. (Hint: gunakan `grep -E` dengan pola alternatif)

![training2.4](https://github.com/Weelyst/OperatingSystemLearning/blob/main/week2/images/training2.4.jpg)

---

## Praktikum 2.11 — Ekstraksi Kolom dengan awk

![awk1](https://github.com/Weelyst/OperatingSystemLearning/blob/main/week2/images/2.11/1..jpg)

![awk2](https://github.com/Weelyst/OperatingSystemLearning/blob/main/week2/images/2.11/2..jpg)

![awk3](https://github.com/Weelyst/OperatingSystemLearning/blob/main/week2/images/2.11/3..jpg)

---

## Praktikum 2.12 — Melihat Proses dengan ps

![ps1](https://github.com/Weelyst/OperatingSystemLearning/blob/main/week2/images/2.12/1.jpg)

![ps2](https://github.com/Weelyst/OperatingSystemLearning/blob/main/week2/images/2.12/2..jpg)

---

## Praktikum 2.13 — Monitoring Real-time dengan top

![top](https://github.com/Weelyst/OperatingSystemLearning/blob/main/week2/images/2.13/top.jpg)

---

## Praktikum 2.14 — Menghentikan Proses dengan kill

![kill1](https://github.com/Weelyst/OperatingSystemLearning/blob/main/week2/images/2.14/1..jpg)

![kill2](https://github.com/Weelyst/OperatingSystemLearning/blob/main/week2/images/2.14/2..jpg)

![kill3](https://github.com/Weelyst/OperatingSystemLearning/blob/main/week2/images/2.14/3..jpg)

![kill4](https://github.com/Weelyst/OperatingSystemLearning/blob/main/week2/images/2.14/4.jpg)

---

## Praktikum 2.15 — Cek Disk, Load, dan Service

![chck_disk](https://github.com/Weelyst/OperatingSystemLearning/blob/main/week2/images/2.15/1.chck_disk.jpg)

![bigdir](https://github.com/Weelyst/OperatingSystemLearning/blob/main/week2/images/2.15/2.bigdir.jpg)

![uptime](https://github.com/Weelyst/OperatingSystemLearning/blob/main/week2/images/2.15/3.uptime.jpg)

![check_fail](https://github.com/Weelyst/OperatingSystemLearning/blob/main/week2/images/2.15/4.check_fail.jpg)

---

## Praktikum 2.16 — Monitoring Port dan Koneksi (Network Basics)

![ip_a](https://github.com/Weelyst/OperatingSystemLearning/blob/main/week2/images/2.16/1.ip_a.jpg)

![ip_r](https://github.com/Weelyst/OperatingSystemLearning/blob/main/week2/images/2.16/2.ip_r.jpg)

![listentulpn](https://github.com/Weelyst/OperatingSystemLearning/blob/main/week2/images/2.16/3.listentulpn.jpg)

### Latihan 2.5
Pilih satu port yang listening dari output `ss -tulpn` (misal port 22), lalu tuliskan service/proses yang membukanya. Jelaskan kegunaan port tersebut secara singkat.

![test2](https://github.com/Weelyst/OperatingSystemLearning/blob/main/week2/images/2.16/test2.jpg)

**Port 22** secara standar digunakan untuk protokol SSH (Secure Shell).

---

## Latihan 2.A
Jalankan `lspci -nnk`. Pilih 1 perangkat PCI dan tuliskan: nama perangkat, ID vendor:device, dan kernel driver in use.

- **Perangkat:** USB Controller
- **ID Vendor:** 8086
- **Kernel Driver in Use:** ehci-pci

---

## Latihan 2.B
Tentukan device root filesystem dengan `findmnt /`. Lalu cocokkan dengan `lsblk -f` dan tuliskan tipe filesystem serta UUID-nya.

- **Device:** sda3
- **Tipe:** LVM2_member
- **UUID:** E7JcKp-Fq7f-AXFc-0ftQ-BbAH-zfr9-oiGDvcca

---

## Latihan 2.C
Buat file server.log berisi minimal 10 baris dengan variasi kata: INFO, WARN, ERROR. Gunakan grep untuk menampilkan hanya baris ERROR.

![PRAC_C](https://github.com/Weelyst/OperatingSystemLearning/blob/main/week2/images/PRAC_C.jpg)

---

## Latihan 2.D
Gunakan sed untuk mengganti semua kata server menjadi node pada file latihan. Tunjukkan sebelum dan sesudah.

![PRAC_D](https://github.com/Weelyst/OperatingSystemLearning/blob/main/week2/images/PRAC_D.jpg)

---

## Latihan 2.E
Gunakan `df -h` lalu awk untuk menampilkan filesystem yang penggunaan disk di atas 70%.

**Hasil:** Tidak Ada

---

## Latihan 2.F
Jalankan `sleep 600 &`. Temukan PID-nya dengan ps. Hentikan dengan SIGTERM. Jelaskan beda SIGTERM vs SIGKILL.

![PRAC_F](https://github.com/Weelyst/OperatingSystemLearning/blob/main/week2/images/PRAC_F.jpg)

- **SIGTERM:** Dapat membunuh proses yang ringan dengan graceful shutdown
- **SIGKILL:** Dapat membunuh proses yang sulit diakhiri secara paksa

---

## Latihan 2.G
Gunakan `systemctl --failed`. Jika tidak ada yang gagal, pilih satu service aktif (misal ssh) dan tampilkan status serta 30 baris log terakhirnya.

![PRAC_G](https://github.com/Weelyst/OperatingSystemLearning/blob/main/week2/images/PRAC_G.jpg)

