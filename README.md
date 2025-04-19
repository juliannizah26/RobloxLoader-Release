Roblox Loader  
Created by: JulianNizah  
Email: juliannizah.26@gmail.com  
Donate: https://saweria.co/jndev26  
Facebook: https://www.facebook.com/juliannizahyt  
===================================================

-----------------------------------------
LANGKAH INSTALASI:
-----------------------------------------

📁 Persiapan Awal:
1. Buat folder dengan nama **"Roblox Portable"** di drive yang ingin digunakan sebagai server  
   (Contoh: `D:\Roblox Portable`).
2. Ekstrak semua file hasil download ke dalam folder tersebut.

🧹 Pembersihan Instalasi Roblox Lama:
Jalankan `z_RobloxCleanup.bat`  
▸ Akan menghapus instalasi Roblox sebelumnya dan symbolic link yang tersisa.

📥 Jika Roblox Belum Terpasang:
1. Download Roblox dari situs resmi.
2. Pindahkan folder Roblox yang sudah terinstal ke struktur berikut:

Contoh pemindahan manual:
- Dari: `C:\Program Files (x86)\Roblox`  
  Ke: `Roblox-Portable\Roblox\ProgramFilesLink`

- Dari: `C:\Users\Administrator\AppData\Local\Roblox`  
  Ke: `Roblox-Portable\Roblox\LocalAppDataLink`

⚙️ Inisialisasi & Update Roblox:
1. Jalankan `z_RobloxInit.bat`
2. Lanjutkan dengan `z_RobloxServer.bat`  
▸ Akan meng-update Roblox ke versi terbaru  
▸ Membuat symbolic link secara otomatis  
▸ Membackup registry Roblox

🚀 Menjalankan Roblox (Client Mode):
- Jalankan `z_RobloxClient.bat`  
- Atau langsung buka `RobloxLoader.exe`

🔄 Update Roblox (jika ada versi baru):
Cukup jalankan ulang `z_RobloxServer.bat`

-----------------------------------------
⚠️ CATATAN PENTING:
-----------------------------------------

🖥️ Mode Peluncuran (Launcher atau Browser):
RobloxLoader dapat dijalankan melalui launcher atau browser tergantung pengaturan.

🔧 **Konfigurasi Peluncuran via `browser_path.txt`:**

1. Buat file bernama `browser_path.txt` di direktori utama RobloxLoader.
2. Isi file tersebut berdasarkan preferensi:

- **Gunakan launcher Roblox bawaan:**
Isi dengan false atau biarkan file kosong

- **Gunakan browser default di sistem:**
Isi dengan true

- **Gunakan browser tertentu:**
Isi dengan path lengkap ke browser pilihan:
Contoh C:\Program Files\Google\Chrome\Application\chrome.exe

-----------------------------------------
📌 Update & Info Lebih Lanjut:
-----------------------------------------

🔗 Selalu cek update terbaru di:
https://github.com/juliannizah26/RobloxLoader-Realease

