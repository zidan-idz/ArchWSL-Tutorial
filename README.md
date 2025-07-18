# Cara Memasang ArchWSL di PC/Laptop Windows

Panduan singkat dan jelas untuk menginstal Arch Linux menggunakan WSL (Windows Subsystem for Linux) di PC atau laptop dengan sistem operasi Windows.

## Persyaratan

- Windows 10/11
- Koneksi internet
- Akses administrator pada komputer

---

## 🛠️ Langkah-Langkah Instalasi

### TAHAP 1:
-	Buka Powershell sebagai Administrator
-	Jalankan Perintah Aktivasi
   ```
dism.exe /online /enable-feature /featurename:VirtualMachinePlatform /all
```
```
dism.exe /online /enable-feature /featurename:Microsoft-Windows-Subsystem-Linux /all
```

### TAHAP 2:
-	Buka File Explorer.
-	Pergi ke drive C:.
-	Buat folder baru bernama ArchWSL(misalnya, C:\ArchWSL).
-	Lalu, Buka browser dan kunjungi: https://github.com/yuk7/ArchWSL/releases
-	Di bagian "Latest release", cari dan unduh file ArchWSL.zip.
-	Setelah selesai mengunduh, ekstrak file ArchWSL.zip tersebut ke folder yang baru dibuat: C:\ArchWSL.

### TAHAP 3:
-	Setelah selesai, Anda akan melihat file Arch.exe bersama file lainnya di dalam folder ini.
-	Setelahnya, Buka PowerShell biasa (bukan Administrator).
-	Navigasikan ke folder instalasi Anda dengan perintah:
```
cd C:\ArchWSL
```
```
.\Arch.exe
```

[Lihat PDF](./ArchWSL-Tutorial.pdf)
[Download PDF](https://raw.githubusercontent.com/zidan-idz/ArchWSL-Tutorial/main/ArchWSL-Tutorial.pdf)


