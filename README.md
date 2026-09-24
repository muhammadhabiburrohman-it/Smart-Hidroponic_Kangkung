# 🌱 Smart-Hidroponic_Kangkung

Sistem hidroponik pintar berbasis IoT untuk budidaya kangkung, menggunakan ESP32 untuk *monitoring* dan kontrol otomatis (nutrisi, pH, ketinggian air, dan suhu air).

🔗 **Demo:** [muhammadhabiburrohman-it.github.io/Smart-Hidroponic_Kangkung](https://muhammadhabiburrohman-it.github.io/Smart-Hidroponic_Kangkung/)

## Fitur
- 📊 Monitoring real-time: pH, TDS, suhu air, ketinggian air, suhu & kelembapan udara
- 🕹️ Kontrol jarak jauh: pompa isi air & pompa nutrisi A/B
- 📈 Grafik tren (Live 5 detik & riwayat 7 hari)
- 🔔 Notifikasi otomatis saat air tandon rendah
- 🔐 Login untuk akses dashboard

## Parameter Ideal
| Parameter | Rentang |
|---|---|
| pH air | 5.5 – 6.5 |
| TDS | 700 – 1000 ppm |
| Suhu air | 18 – 26 °C |
| Level air | ≥ 50% |
| Suhu udara | 24 – 34 °C |
| Kelembapan udara | 45 – 85% RH |

## Teknologi
- **Firmware:** ESP32 (Arduino)
- **Backend:** Firebase Realtime Database, Firestore, Authentication
- **Frontend:** HTML, Tailwind CSS, JavaScript
- **Hosting:** GitHub Pages

## Struktur Proyek
```
├── index.html        # Halaman login
├── dashboard.html    # Dashboard monitoring & kontrol
└── README.md
```

## Cara Menjalankan
1. Buat proyek Firebase → aktifkan Realtime Database, Firestore, Authentication
2. Salin `firebaseConfig` ke `index.html` dan `dashboard.html`
3. Program ESP32 agar menulis data ke `/monitoring` dan membaca perintah dari `/kontrol`
4. Buka `index.html` atau publikasikan lewat GitHub Pages

## Kontributor
**Muhammad Habiburrohman**

---
<p align="center"><i>Dibuat dengan 🌱 untuk pertanian yang lebih cerdas.</i></p>
