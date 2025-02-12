# 50-command-ubuntu
sebelumnya saya minta maaf , karena saya memakai laptop teman saya untuk mengerjakan tugas ini dikarenakan divice saya kurang memadai
Informasi Sistem:

    1.uname -a – Menampilkan informasi sistem.
 ![Screenshot from 2025-02-12 13-40-31](https://github.com/user-attachments/assets/b5fe9506-cc98-48ee-b13f-6f8a334b1da0)

   2. hostname – Menampilkan atau mengatur hostname sistem.
  ![Screenshot from 2025-02-12 13-42-38](https://github.com/user-attachments/assets/73948b9b-b729-4bde-82c5-661112b3b67d)

   3. uptime – Menampilkan berapa lama sistem sudah berjalan.
  ![Screenshot from 2025-02-12 13-44-51](https://github.com/user-attachments/assets/00ae16c9-55dd-48fd-b664-e18933732b1a)

    4.lsb_release -a – Menampilkan informasi distribusi Linux.
 ![Screenshot from 2025-02-12 13-46-36](https://github.com/user-attachments/assets/5127ab77-78b4-4b67-96b4-0ae01302df01)

   5.top – Menampilkan penggunaan sumber daya sistem secara real-time.
 ![Screenshot from 2025-02-12 13-48-15](https://github.com/user-attachments/assets/f9aedc22-2e02-49d5-bb07-cf7f9cde6405)

   6. htop – Penampil proses interaktif (install via sudo apt install htop).
 ![Screenshot from 2025-02-12 13-50-46](https://github.com/user-attachments/assets/ec0fdd59-343b-49c9-972a-77e6be10cfce)

   7.free -h – Menampilkan penggunaan memori.
![Screenshot from 2025-02-12 13-51-31](https://github.com/user-attachments/assets/9201f560-307a-4de7-9857-0f300fb61f9d)

   8. df -h – Menampilkan penggunaan ruang disk.
![Screenshot from 2025-02-12 13-52-06](https://github.com/user-attachments/assets/59414645-febe-4727-873f-39937bd9840b)

  9.  du -sh <dir> – Menampilkan penggunaan disk untuk direktori.
 ![Screenshot from 2025-02-12 13-53-20](https://github.com/user-attachments/assets/b4901f5e-8216-4cf6-92ca-58d70f70c98f)

   10. vmstat – Menampilkan kinerja sistem.
![Screenshot from 2025-02-12 13-53-58](https://github.com/user-attachments/assets/2d7062e9-f489-43d2-8b98-cf411ca5be1f)

  11.  lscpu – Menampilkan informasi arsitektur CPU.
![Screenshot from 2025-02-12 13-54-55](https://github.com/user-attachments/assets/f5aa8871-e324-40ab-9b00-a30d68e288c9)

  12.  lsblk – Menampilkan perangkat blok (misalnya hard drive).
 ![Screenshot from 2025-02-12 13-55-59](https://github.com/user-attachments/assets/f55d8f33-4391-42d4-84a1-4bbdd5155105)

   13. lspci – Menampilkan perangkat PCI.
 ![Screenshot from 2025-02-12 13-56-23](https://github.com/user-attachments/assets/01fbfa46-7c0e-49cb-83b6-73f5c6bb51b0)

   14. lsusb – Menampilkan perangkat USB.
 ![Screenshot from 2025-02-12 13-57-55](https://github.com/user-attachments/assets/19e47c3b-1341-46b0-b163-5e554b3ba527)

   15. dmesg – Menampilkan log boot dan log sistem.
![Screenshot from 2025-02-12 13-58-37](https://github.com/user-attachments/assets/f18e992a-7adf-4eb1-a408-d5742fc24e87)

Manajemen Pengguna dan Grup:

  16.  whoami – Menampilkan pengguna yang sedang login.
![Screenshot from 2025-02-12 13-59-51](https://github.com/user-attachments/assets/80f942c4-d669-4dc9-9124-ab61819ee3e3)

  17.  id – Menampilkan informasi pengguna dan grup.
 ![Screenshot from 2025-02-12 14-00-22](https://github.com/user-attachments/assets/5ff0740b-4a71-4877-8e03-ba90c460ea95)

  18.  useradd <username> – Menambah pengguna baru.
 ![Screenshot from 2025-02-12 14-01-53](https://github.com/user-attachments/assets/d125aaad-c7b3-4a15-8053-20aacc28c2e0)

  19.  passwd <username> – Mengubah kata sandi pengguna.
 ![Screenshot from 2025-02-12 14-02-46](https://github.com/user-attachments/assets/b07c026f-ea77-4c9a-8d13-9d239b6f6d25)

  20.  usermod -aG <group> <username> – Menambahkan pengguna ke grup.
![Screenshot from 2025-02-12 14-03-13](https://github.com/user-attachments/assets/fcee6061-2fd2-4ecf-b350-73338b9261da)

  21.  groupadd <groupname> – Menambahkan grup baru.
![Screenshot from 2025-02-12 14-03-44](https://github.com/user-attachments/assets/be306e06-71c0-4f0a-856b-6c577689bce7)

 22 .  groups <username> – Menampilkan grup tempat pengguna berada.
![Screenshot from 2025-02-12 14-04-12](https://github.com/user-attachments/assets/ee573fad-356c-41ed-a35c-f711a0c3cf63)

  23 . deluser <username> – Menghapus pengguna.
![Screenshot from 2025-02-12 14-05-26](https://github.com/user-attachments/assets/92a5e7d2-6091-4fed-9dd5-0d4b2b9618fb)

  24. delgroup <groupname> – Menghapus grup.
![Screenshot from 2025-02-12 14-05-48](https://github.com/user-attachments/assets/207365bc-aae9-43e5-bc06-be07cb661468)

  25.  chown <user>:<group> <file> – Mengubah pemilik dan grup file.
 ![Screenshot from 2025-02-12 14-06-15](https://github.com/user-attachments/assets/693103be-ae99-4d86-88cb-335e7fc32bfb)

  26.  chmod 755 <file> – Mengubah izin akses file.
![Screenshot from 2025-02-12 14-06-15 (Copy)](https://github.com/user-attachments/assets/f1a3903c-6a5f-49b2-a926-ec6e838f58d8)

Manajemen File:

   27. ls – Menampilkan isi direktori.
![Screenshot from 2025-02-12 14-06-53](https://github.com/user-attachments/assets/aa132e69-319c-401d-8b95-42a86a03859c)

  28.  cd <dir> – Pindah ke direktori lain.
![Screenshot from 2025-02-12 14-07-42](https://github.com/user-attachments/assets/63140ca7-7829-433e-93f8-d95c2beb2ed5)

  29.  cp <source> <destination> – Menyalin file atau direktori.
![Screenshot from 2025-02-12 14-08-27](https://github.com/user-attachments/assets/1e213185-15d0-4072-b471-7552c4bf2f8a)

  30.  mv <source> <destination> – Memindahkan atau mengganti nama file/direktori.
 ![Screenshot from 2025-02-12 14-08-53](https://github.com/user-attachments/assets/c527e6d2-5c29-47ea-a4f6-0e09823ad540)

   31. rm <file> – Menghapus file.
 ![Screenshot from 2025-02-12 14-09-35](https://github.com/user-attachments/assets/cb4aec11-81e2-4a4a-b935-ff9b4c0c07da)

   32. rmdir <dir> – Menghapus direktori kosong.
![Screenshot from 2025-02-12 14-10-02](https://github.com/user-attachments/assets/c06f9681-c5a0-4014-8c7b-e04615ca2ae0)

33. mkdir <dir> – Membuat direktori baru.
![Screenshot from 2025-02-12 14-10-18](https://github.com/user-attachments/assets/b75b4f02-f143-4515-ae67-73729d24b1b8)

34.  touch <file> – Membuat file kosong.
 ![Screenshot from 2025-02-12 14-10-45](https://github.com/user-attachments/assets/f22edc97-3a64-448b-8a87-346c4e794a2f)

   35. cat <file> – Menampilkan isi file.
  ![Screenshot from 2025-02-12 14-11-18](https://github.com/user-attachments/assets/c3ad4a67-5fd7-4298-84e9-fee5a0d019e6)

  36. nano <file> – Membuka file dengan editor teks nano.
![Screenshot from 2025-02-12 14-12-21](https://github.com/user-attachments/assets/22d4a85a-1fba-4ffb-b855-8a1e3db9b513)

 37.  vim <file> – Membuka file dengan editor teks vim.
   ![Screenshot from 2025-02-12 14-12-54](https://github.com/user-attachments/assets/e48e415f-06e6-499d-bd08-954cfba66fe4)

   38. find <dir> -name <filename> – Mencari file.
  ![Screenshot from 2025-02-12 14-13-34](https://github.com/user-attachments/assets/a1f507a4-9c24-4399-9808-93dba5b5d9e7)

   39. locate <filename> – Menemukan lokasi file (gunakan sudo updatedb untuk memperbarui database).
![Screenshot from 2025-02-12 14-14-05](https://github.com/user-attachments/assets/c184d3d6-e767-45da-aadf-dc9cff682deb)

  40.  file <filename> – Menampilkan tipe file.
![Screenshot from 2025-02-12 14-14-28](https://github.com/user-attachments/assets/dd607142-0f9a-4ea0-920a-78bccf1c3b85)

Manajemen Paket (APT):

 41.   sudo apt update – Memperbarui daftar paket.
 ![Screenshot from 2025-02-12 14-15-07](https://github.com/user-attachments/assets/00f5e4f2-7764-4dc1-9496-2db9c1a3a263)

 42.   sudo apt upgrade – Memperbarui paket yang terpasang.
 ![Screenshot from 2025-02-12 14-15-24](https://github.com/user-attachments/assets/862aa47c-b6e5-4055-9094-95d80e2dc44d)

 43.   sudo apt install <package> – Menginstal paket.
 ![Screenshot from 2025-02-12 14-16-35](https://github.com/user-attachments/assets/2f957587-3745-418b-9f89-7d0cf5303d6b)

 44.   sudo apt remove <package> – Menghapus paket.
 ![Screenshot from 2025-02-12 14-18-27](https://github.com/user-attachments/assets/ea0bab51-5a67-441d-9b4f-e63a0de39ff0)

 45.   sudo apt purge <package> – Menghapus paket beserta file konfigurasi.
![Screenshot from 2025-02-12 14-28-00](https://github.com/user-attachments/assets/837ccbf3-5924-4bcf-a26f-067891cd65f4)

 46.   sudo apt autoremove – Menghapus paket yang tidak terpakai.
![Screenshot from 2025-02-12 14-28-29](https://github.com/user-attachments/assets/dead0e04-5bc5-40a2-a68b-db959bb43317)

 47.  dpkg -l – Menampilkan daftar paket yang terpasang.
 ![Screenshot from 2025-02-12 14-29-00](https://github.com/user-attachments/assets/abbaf7f6-9176-40c8-b070-0acfabb34c42)

  48.  sudo apt search <package> – Mencari paket.
![Screenshot from 2025-02-12 14-30-09](https://github.com/user-attachments/assets/4bd02c63-f1cf-4e2c-99be-31e88c60e326)

 49.  sudo apt show <package> – Menampilkan informasi paket.

 50.  ![Screenshot from 2025-02-12 14-35-08](https://github.com/user-attachments/assets/1edee64f-043d-446d-994c-669a4cae234f)


 51.  sudo apt-get clean – Membersihkan file paket yang sudah diunduh.
