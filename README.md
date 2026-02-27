# Alvaro-project Plymouth Theme
![Boot ChacyOS](Boot_for_chacyos.gif)

ini tampilan asli

## ❌ kekurangan
- kadang cepat sebagian
- pas munculin powered by chacyos langsung di cepetin

##
Tema Plymouth kustom dengan animasi PNG frame-by-frame.



## ✨ Deskripsi
Alvaro-project adalah tema Plymouth kustom untuk sistem Linux yang menginginkan tampilan boot yang bersih, modern, dan stabil. Tema ini menggunakan animasi berbasis PNG (frame-by-frame) yang diputar saat proses boot awal, lalu **berhenti (freeze) di frame terakhir** untuk menghindari tampilan terpotong pada sistem dengan proses boot yang cepat.

Tema ini dibuat dengan prinsip **mengutamakan kestabilan sistem**, bukan memaksa animasi berjalan penuh, sesuai dengan batasan dan praktik terbaik Plymouth.

## 🎯 Fitur Utama
- Animasi PNG frame-by-frame
- Aman untuk sistem dengan fast-boot (tidak menyebabkan bootloop)
- Posisi gambar otomatis di tengah (mendukung ukuran gambar yang tidak diketahui)
- Berhenti dengan halus di frame terakhir
- Script ringan dan sederhana
- Cocok untuk kustomisasi Linux pribadi atau proyek OS remix

## 📂 Struktur Tema
```
Alvaro-project/
├── Alvaro-project.plymouth
├── Alvaro-project.script
├── ezgif-frame-001.png
├── ezgif-frame-002.png
├── ...
└── ezgif-frame-XXX.png
```
## ⚙️ Cara Instalasi

1. Klik [Latest Release](https://github.com/alvaronaladhipa-dot/Boot-splash-Plymouth-for-Arch-Linux/releases/tag/v0.1) jika Anda ingin melihat update terbaru.

2. Jika Anda mau langsung menggunakan command tanpa melihat update:
   ```bash
   git clone https://github.com/alvaronaladhipa-dot/Boot-splash-Plymouth-for-Arch-Linux.git



## ⚙️ Cara menyalakan
1. Lihat folder yang bernama
```
Boot-splash-Plymouth-for-Arch-Linux
```
2 pilih folder yang mana yang cocok buat linux 
```
Boot-splash-Plymouth-for-Arch-Linux/
├── Alvaro-project.tar.gz
└──Alvaro-project.zip
```
3. Extract folder      
4. folder yang bernama Alvaro-projact taroh di home
5. ketik ini di command
```bash
cd ~
```
```bash
ls
```
```bash         
sudo mv Alvaro-project /usr/share/plymouth/themes/
```
```bash
sudo plymouth-set-default-theme Alvaro-project -R
```

Setelah itu, reboot sistem untuk menerapkan tema.



## ⚠️ Catatan Penting
- Plymouth tidak dapat menjamin animasi berjalan penuh pada sistem yang boot-nya sangat cepat.
- Tema ini sengaja berhenti di frame tertentu untuk menghindari pemotongan visual yang kasar.
- Dirancang dengan fokus pada **konsistensi visual dan keamanan sistem**.

## 📜 Lisensi
Bebas digunakan untuk keperluan pribadi dan edukasi.

## 👤 Pembuat
**Alvaro**  
