Averose Arthur R
254107020042
TI - 1H

Latihan 1.1
Jelaskan 5 fungsi utama sistem operasi dengan contoh konkret dari minimal 2
OS berbeda (Windows, macOS, atau Linux).

1.Management process
2.Memory Management
3.File System Management
4.Device Management
5.Security

Windows
1.Task Manager
2.Virtual Memory
3.NTFS + File Explorer
4.Device Manager
5.Windows Security
proof

![Task Manager](./images/1.1_images/w1.taskmanager.jpg)

![Windows Explorer](./images/1.1_images/w3.winexplorer.jpg)

![Windows Security](./images/1.1_images/w5.windowsSecurity.jpg)

Linux (command)
1.top, ps
2.free, swap
3.ext4 + chmod
4.lsusb, lspci
5.sudo + permission system

proof

![Top Command](./images/1.1_images/lx1.top.jpg)

![Sudo Permission](./images/1.1_images/lx5.sudo.jpg)

Latihan 1.2
Kapan sebaiknya menggunakan Windows vs Linux vs macOS? Analisis
berdasarkan use case: gaming, development, server, creative work, dan enterprise.

A.Gaming
Windows Ketika ingin memainkan game dengan stabil dan kompatibel
LX game yang opensource/indie
MacOs hardware kurang untuk game

B.Development
Win = .Net dan GameDev
Lx =  Banyak Support thd linux
MacOs = Bisa Fullstack mirip linux

C.Server
Win = Enterprise Specific
Lx = Mayoritas server dunia pakai Linux
MacOs = Jarang digunakan untuk server production

D.CreativeWork
Win = GPU high-end support, Banyak software profesional tersedia
Lx = Ada, Namun kurang
MacOs = Optimasi hardware-software Apple & aplikasi premium apple

E.Enterprise
Win = The Common choices
Lx = Cheap,Better for Dev
MacOs = Bagus Untuk Startup

Latihan 1.3
Install Ubuntu Server 22.04 LTS di VirtualBox dengan langkah berikut:
1. Download Ubuntu Server ISO dari website resmi
2. Create VM baru di VirtualBox (RAM: 2GB, Disk: 25GB)
3. Install dengan automatic partitioning (guided)
4. Buat user account dengan password yang kuat
5. Reboot dan login ke sistem
6. Dokumentasikan proses instalasi dengan screenshot key steps

1.Opening VM

![Making New VM](./images/1.3_images/1making_new_vm1.jpg)

2.New Vm and mounting linux iso

![New VM with ISO](./images/1.3_images/2making_new_vm3.jpg)

3.After install linux and making new account

![After Login](./images/1.3_images/3after_login.jpg)

Latihan 1.4
Setelah instalasi Ubuntu Server, lakukan tasks berikut:
1. Update package list: sudo apt update
2. Upgrade packages: sudo apt upgrade
3. Install neofetch: sudo apt install neofetch
4. Jalankan neofetch dan screenshot hasilnya
5. Check disk usage dengan df -h
6. Check memory dengan free -h
7. Dokumentasikan output dari setiap command

1.UpdateALL

![Update All](./images/1.4_images/1allupdate.jpg)

2.NeoFetch

![NeoFetch](./images/1.4_images/2neofetch.jpg)

3.df -h

![Disk Usage](./images/1.4_images/3dfh.jpg)

4.free -h

![Memory Usage](./images/1.4_images/4freeh.jpg)

Latihan 1.5
Eksplorasi sistem yang baru diinstall:
1. Tampilkan informasi OS: cat /etc/os-release
2. Tampilkan versi kernel: uname -r
3. List partisi: lsblk
4. Check network connectivity: ping -c 4 google.com
5. Install dan jalankan htop untuk melihat resource usage
6. Buat laporan singkat tentang konfigurasi sistem Anda

1.

![OS Release](./images/1.5_images/checkcat.jpg)

2.

![Uname](./images/1.5_images/unameR.jpg)

3.

![Partition](./images/1.5_images/lsblk.jpg)

4.

![Ping Test](./images/1.5_images/pingtest2.jpg)

5.

![HTOP](./images/1.5_images/htop.jpg)

6. sistem telah mengunakan versi terbaru, terhubung dengan internet, dan bekerja normal

Latihan 1.6
Ceritakan pengalaman Anda dengan sistem operasi:
1. Sistem operasi apa yang Anda gunakan sehari-hari? (Windows, macOS,
Linux, atau lainnya)
2. Berapa lama Anda menggunakan sistem operasi tersebut?
3. Apa yang Anda sukai dari sistem operasi tersebut?
4. Apa tantangan atau masalah yang pernah Anda hadapi?
5. Apakah Anda pernah menggunakan sistem operasi lain? Bandingkan
pengalaman Anda.
6. Setelah mempelajari bab ini, apakah ada sistem operasi lain yang ingin
Anda coba? Mengapa?
Tulis refleksi Anda dalam 300-500 kata disertai dengan dokumentasi.

1.Saya sering menggunakan Operating system Windows

2.Hampir seumur hidup

3.Banyak aplikasi yang lebih mendukung ke Windows Os

4.Update windows 

5.Linux, tepatnya Distro linux mint, saya menggunakan linux mint saat mencoba menghidupkan kembali komputer tua saya, Linux mint dan Windows hampir Mirip namun di linux mint kebanyakan harus menggunakan aplikasi eksternal seperti Wine atau melakukan download via command

6. Mungkin saya akan menunggu ketersediaan support Aplikasi dari Distro2 OS Linux, karena penggunaan hardware yang terkadang dikatakan sangat minim dari os tersebut, menjadi alternatif saya ketika Os Windows mendapatkan update besar, yang membuat banyak sekali komputer maupun laptop yang spesifikasinya sudah bisa dikatakan ketinggalan zaman, dan juga bisa menghemat biaya dari pemalakan key windows yang sangat menggangu maupun Update yang kini juga membahayakan pengguna karena update yang dikeluarkan menghasilkan bug-bug yang diluar kendali orang awam 
Berikut adalah pilihan saya jika ingin bermain game menggunakan distro linux

![Gaming Linux Distro](./images/final_picture.jpg)

