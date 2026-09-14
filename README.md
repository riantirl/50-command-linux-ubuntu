# 50-command-linux-ubuntu

# 1. Menampilkan lokasi direktori saat ini
pwd
<img width="1280" height="800" alt="VirtualBox_ubuntu26_14_09_2026_21_30_05" src="https://github.com/user-attachments/assets/53130203-7e15-4c69-9f50-c0d2dccd1308" />

# 2. Melihat isi direktori
ls
<img width="1280" height="800" alt="VirtualBox_ubuntu26_14_09_2026_21_31_37" src="https://github.com/user-attachments/assets/1f5adbd2-fd7c-4e9c-b19c-21aaddc11e72" />

# 3. Melihat isi direktori secara detail
ls -l
<img width="1280" height="800" alt="VirtualBox_ubuntu26_14_09_2026_21_31_37" src="https://github.com/user-attachments/assets/27fe382e-178b-4b89-9367-7069c79f167c" />

# 4. Berpindah direktori
cd Documents
<img width="1280" height="800" alt="VirtualBox_ubuntu26_14_09_2026_21_37_56" src="https://github.com/user-attachments/assets/fb7daad3-0764-4967-9c36-c83fb3824551" />

# 5. Kembali ke direktori sebelumnya
cd ..
<img width="1280" height="800" alt="VirtualBox_ubuntu26_14_09_2026_21_40_08" src="https://github.com/user-attachments/assets/12402409-3c59-4009-b1e6-ba498690b2ff" />

# 6. Membuat direktori baru
mkdir tugas
<img width="1280" height="800" alt="VirtualBox_ubuntu26_14_09_2026_21_42_07" src="https://github.com/user-attachments/assets/1b57989d-8ed8-488b-9060-24f1ee3663e8" />


# 7. Menghapus direktori kosong
rmdir tugas
<img width="1280" height="800" alt="VirtualBox_ubuntu26_14_09_2026_21_46_32" src="https://github.com/user-attachments/assets/0a6040df-efc8-4e98-a921-4e32e212126b" />

# 8. Membuat file baru
touch data.txt
<img width="1280" height="800" alt="VirtualBox_ubuntu26_14_09_2026_21_50_55" src="https://github.com/user-attachments/assets/75d4a47c-1a2d-4b8a-91bc-e6340bdb252a" />

# 9. Menyalin file
cp data.txt backup.txt
<img width="1280" height="800" alt="VirtualBox_ubuntu26_14_09_2026_21_52_12" src="https://github.com/user-attachments/assets/95c581be-a1af-45a3-bce0-0d03bcba5bac" />

# 10. Memindahkan atau mengganti nama file
mv data.txt dokumen.txt
<img width="1280" height="800" alt="VirtualBox_ubuntu26_14_09_2026_21_55_49" src="https://github.com/user-attachments/assets/e8d8c8d3-3f49-421f-91a4-188d9d88cdb4" />

# 11. Menghapus file
rm dokumen.txt
<img width="1280" height="800" alt="VirtualBox_ubuntu26_14_09_2026_22_02_01" src="https://github.com/user-attachments/assets/2d257d54-395f-4946-906b-362d4f2c1ee5" />

# 12. Menampilkan isi file
cat backup.txt
<img width="1280" height="800" alt="VirtualBox_ubuntu26_14_09_2026_22_04_11" src="https://github.com/user-attachments/assets/a258158f-c340-42a1-9574-c5afddadf9db" />

# 13. Membaca file per halaman
less backup.txt
<img width="1280" height="800" alt="VirtualBox_ubuntu26_14_09_2026_22_13_55" src="https://github.com/user-attachments/assets/b6586bcd-ac33-4172-abea-c6e9e9b6ffdd" />

# 14. Menampilkan 10 baris pertama
head backup.txt
<img width="1280" height="800" alt="VirtualBox_ubuntu26_14_09_2026_22_15_32" src="https://github.com/user-attachments/assets/96eaf295-c70d-4c18-8196-122f029ca3f3" />



# 15. Menampilkan 10 baris terakhir
tail backup.txt

# 16. Mengedit file dengan Nano
nano backup.txt

# 17. Membersihkan terminal
clear

# 18. Melihat riwayat command
history

# 19. Menampilkan teks
echo "Halo Linux Ubuntu"

# 20. Menampilkan username
whoami

# 21. Melihat pengguna yang sedang login
who

# 22. Menampilkan tanggal dan waktu
date

# 23. Menampilkan kalender
cal

# 24. Menampilkan informasi sistem
uname -a

# 25. Menampilkan nama komputer
hostname

# 26. Menampilkan lama sistem berjalan
uptime

# 27. Melihat penggunaan RAM
free -h

# 28. Melihat penggunaan disk
df -h

# 29. Melihat ukuran file dan direktori
du -h

# 30. Melihat proses yang sedang berjalan
top

# 31. Menampilkan daftar proses
ps aux

# 32. Menghentikan proses berdasarkan PID
kill 1234

# 33. Mengecek koneksi internet
ping google.com

# 34. Melihat informasi jaringan
ip addr

# 35. Melihat koneksi jaringan
ss -tuln

# 36. Mengunduh file
wget https://example.com/file.zip

# 37. Mengakses URL
curl https://example.com

# 38. Menjalankan command sebagai administrator
sudo ls

# 39. Memperbarui daftar paket
sudo apt update

# 40. Memperbarui paket yang terpasang
sudo apt upgrade

# 41. Menginstal aplikasi
sudo apt install git

# 42. Menghapus aplikasi
sudo apt remove git

# 43. Mencari paket
apt search python

# 44. Membuka manual command
man ls

# 45. Mencari teks dalam file
grep "Linux" backup.txt

# 46. Mencari file berdasarkan nama
find . -name "*.txt"

# 47. Mencari lokasi file
locate backup.txt

# 48. Mengubah permission file
chmod 755 script.sh

# 49. Mengubah pemilik file
sudo chown user backup.txt

# 50. Restart komputer
sudo reboot
