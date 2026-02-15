
# Alvaro-project Plymouth Theme

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

## ⚙️ Instalasi
```bash
sudo mv Alvaro-project /usr/share/plymouth/themes/
sudo plymouth-set-default-theme Alvaro-project -R
```

Setelah itu, reboot sistem untuk menerapkan tema.

## 🧪 Testing (tanpa reboot)
```bash
sudo plymouthd
sudo plymouth --show-splash
sudo plymouth quit
```

## ⚠️ Catatan Penting
- Plymouth tidak dapat menjamin animasi berjalan penuh pada sistem yang boot-nya sangat cepat.
- Tema ini sengaja berhenti di frame tertentu untuk menghindari pemotongan visual yang kasar.
- Dirancang dengan fokus pada **konsistensi visual dan keamanan sistem**.

## 📜 Lisensi
Bebas digunakan untuk keperluan pribadi dan edukasi.

## 👤 Pembuat
**Alvaro**  
Proyek kustomisasi dan eksperimen Linux
---



