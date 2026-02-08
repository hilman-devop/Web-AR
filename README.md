# AR Biologi SMA - Augmented Reality Edukasi Biologi Kelas XI 🧠✨

**Aplikasi Web Augmented Reality** untuk pembelajaran interaktif Biologi SMA Kelas XI, fokus pada **Sistem Organ Manusia** (Sistem Pernapasan & Sistem Koordinasi).

Proyek ini adalah landing page edukasi dengan desain modern dan animasi menarik yang mengarahkan pengguna ke dua modul AR berbasis web (menggunakan **AR.js** + **A-Frame**). Pengguna dapat mengakses pengalaman 3D interaktif langsung di browser tanpa instalasi aplikasi tambahan (hanya butuh kamera dan marker).

![Landing Page Preview](assets/landing-preview.jpg) <!-- Upload screenshot landing page -->
![AR Demo](assets/ar-demo.gif) <!-- Upload GIF demo AR di browser -->

### 🚀 Fitur Utama
- **Splash screen** dengan animasi gradient dan loading elegan
- **Background animasi particles** floating untuk efek futuristik
- **Responsive design** (mobile-first, tampil bagus di HP/tablet/desktop)
- **Menu grid** dengan card interaktif (hover effect, glassmorphism)
- Dua modul AR:
  - **AR-BREATH**: Eksplorasi 3D sistem pernapasan manusia (paru-paru, alveolus, dll.)
  - **AR-COORDINATION**: Visualisasi sistem saraf, hormon, dan indra
- Pure HTML/CSS/JS (vanilla) + AR.js di sub-modul → ringan dan cepat load
- Tidak butuh app eksternal → cukup scan marker dengan kamera HP/browser

### 🛠 Tech Stack
- HTML5
- CSS3 (Flexbox, Grid, Animations, Glassmorphism, Gradient)
- JavaScript Vanilla (particles, splash screen transition)
- AR.js + A-Frame (di folder `AR-Breath/` dan `AR-Coordination/`)
- Google Fonts (Poppins)
- Icon dari Flaticon

### 📦 Struktur Repository
ar-biologi-sma/
├── index.html                  # Landing page utama (kode yang kamu bagikan)
├── AR-Breath/
│   └── index.html              # Modul AR Sistem Pernapasan
├── AR-Coordination/
│   └── index.html              # Modul AR Sistem Koordinasi
├── assets/                     # Folder untuk screenshot/GIF demo
│   ├── landing-preview.jpg
│   └── ar-demo.gif
└── marker/                     # Folder marker HIF (jika ada, untuk AR.js)
text### ▶️ Cara Menjalankan Lokal
Karena ini pure static web, sangat mudah:

1. Clone repository:
   ```bash
   git clone https://github.com/hilman-devop/ar-biologi-sma.git
   cd ar-biologi-sma

Buka dengan Live Server (rekomendasi):
Install extension Live Server di VS Code
Klik kanan index.html → "Open with Live Server"
Atau cukup double-click index.html di file explorer (tapi AR.js butuh HTTPS/local server untuk akses kamera).
Untuk modul AR:
Klik card → masuk ke modul
Izinkan akses kamera
Print/cetak marker (biasanya hiro atau custom) → arahkan kamera ke marker


🌐 Demo Live (Rekomendasi)
Deploy gratis ke GitHub Pages atau Vercel/Netlify:

GitHub Pages: Settings → Pages → Branch main → Save → akses di https://hilman-devop.github.io/ar-biologi-sma
Link demo akan muncul otomatis.

📸 Screenshot & Demo

Landing page dengan splash screen dan particles
Tampilan card menu responsif
Demo AR di browser (GIF scan marker → model 3D muncul)

🔮 Future Improvements (Ide Pengembangan)

Tambah modul lain (Sistem Pencernaan, Sirkulasi, dll.)
Voice narration/guide audio
Quiz interaktif setelah eksplorasi AR
Multi-marker support
Integrasi PWA (installable di HP)

🏆 Konteks Proyek
Proyek ini dibuat sebagai media pembelajaran interaktif Biologi SMA, menggabungkan web development dengan teknologi Augmented Reality untuk meningkatkan engagement siswa.
