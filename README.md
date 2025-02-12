# 50-command-ubuntu
Informasi Sistem:

    1.uname -a – Menampilkan informasi sistem.
 
   2. hostname – Menampilkan atau mengatur hostname sistem.
  
   3. uptime – Menampilkan berapa lama sistem sudah berjalan.
  
    4.lsb_release -a – Menampilkan informasi distribusi Linux.
 
   5.top – Menampilkan penggunaan sumber daya sistem secara real-time.
 
   6. htop – Penampil proses interaktif (install via sudo apt install htop).
 
   7.free -h – Menampilkan penggunaan memori.

   8. df -h – Menampilkan penggunaan ruang disk.

  9.  du -sh <dir> – Menampilkan penggunaan disk untuk direktori.
   10. vmstat – Menampilkan kinerja sistem.

  11.  lscpu – Menampilkan informasi arsitektur CPU.

  12.  lsblk – Menampilkan perangkat blok (misalnya hard drive).
 
   13. lspci – Menampilkan perangkat PCI.
 
   14. lsusb – Menampilkan perangkat USB.
 
   15. dmesg – Menampilkan log boot dan log sistem.

Manajemen Pengguna dan Grup:

  16.  whoami – Menampilkan pengguna yang sedang login.

  17.  id – Menampilkan informasi pengguna dan grup.
 
  18.  useradd <username> – Menambah pengguna baru.
 
  19.  passwd <username> – Mengubah kata sandi pengguna.
 
  20.  usermod -aG <group> <username> – Menambahkan pengguna ke grup.

  21.  groupadd <groupname> – Menambahkan grup baru.

 22 .  groups <username> – Menampilkan grup tempat pengguna berada.

  23 . deluser <username> – Menghapus pengguna.

  24. delgroup <groupname> – Menghapus grup.

  25.  chown <user>:<group> <file> – Mengubah pemilik dan grup file.
 
  26.  chmod 755 <file> – Mengubah izin akses file.

Manajemen File:

   27. ls – Menampilkan isi direktori.

  28.  cd <dir> – Pindah ke direktori lain.

  29.  cp <source> <destination> – Menyalin file atau direktori.

  30.  mv <source> <destination> – Memindahkan atau mengganti nama file/direktori.
 
   31. rm <file> – Menghapus file.
 
   32. rmdir <dir> – Menghapus direktori kosong.

33. mkdir <dir> – Membuat direktori baru.

34.  touch <file> – Membuat file kosong.
 
   35. cat <file> – Menampilkan isi file.
  
  36. nano <file> – Membuka file dengan editor teks nano.

 37.  vim <file> – Membuka file dengan editor teks vim.
   
   38. find <dir> -name <filename> – Mencari file.
  
   39. locate <filename> – Menemukan lokasi file (gunakan sudo updatedb untuk memperbarui database).

  40.  file <filename> – Menampilkan tipe file.

Manajemen Paket (APT):

 41.   sudo apt update – Memperbarui daftar paket.
 
 42.   sudo apt upgrade – Memperbarui paket yang terpasang.
 
 43.   sudo apt install <package> – Menginstal paket.
 
 44.   sudo apt remove <package> – Menghapus paket.
 
 45.   sudo apt purge <package> – Menghapus paket beserta file konfigurasi.

 46.   sudo apt autoremove – Menghapus paket yang tidak terpakai.

 47.  dpkg -l – Menampilkan daftar paket yang terpasang.
 
  48.  sudo apt search <package> – Mencari paket.

 49.  sudo apt show <package> – Menampilkan informasi paket.

 50.  sudo apt-get clean – Membersihkan file paket yang sudah diunduh.
