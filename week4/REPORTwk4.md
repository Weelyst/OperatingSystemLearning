## NAMA : Averose Arthur R // Kelas : TI-1H/04
 **tugas pendahuluan**
 1. Perintah Dasar Direktori
pwd (Print Working Directory): Menampilkan jalur (path) lengkap dari direktori tempat Anda berada saat ini.
-
cd (Change Directory): Digunakan untuk berpindah dari satu direktori ke direktori lain.
-
mkdir (Make Directory): Digunakan untuk membuat direktori atau folder baru.
-
rmdir (Remove Directory): Digunakan untuk menghapus direktori yang kosong. Jika direktori berisi file, perintah ini akan gagal.

2. Manipulasi File
cp, Meng-Copy File/Directory (cp[sumber][tujuan])
-
mv Memindahkan atau mengubah nama file/directory
-
rm remove File/Directory

3. Perbedaan Hard Link vs Soft Link
Hard Link (Direct):

Merujuk langsung ke inode (data fisik) yang sama di hard drive.
Jika file asli dihapus, file hard link tetap bisa diakses karena datanya masih ada selama masih ada link yang mengarah ke sana.
Tidak bisa lintas partisi/sistem file.

Soft Link / Symbolic Link (Indirect):
Hanya berupa shortcut atau penunjuk jalan yang berisi alamat/jalur ke file asli.
Jika file asli dihapus, soft link akan rusak (broken link) karena alamat yang ditujunya sudah hilang.
Bisa digunakan lintas partisi atau direktori.


4. Perintah Pencarian dan Filter
file: Digunakan untuk melihat tipe file karena di Linux ekstensi file tidak selalu menentukan jenisnya.

find: Mencari file secara real-time di dalam hierarki direktori 

which: Menunjukkan lokasi file executable (aplikasi) yang dijalankan saat kita mengetik sebuah perintah di terminal.

locate: Mencari file dengan cepat menggunakan database indeks 

grep: Digunakan untuk mencari pola teks tertentu di dalam sebuah file atau dari hasil output perintah lain.

## Percobaan 1 Directory
