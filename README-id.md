[English](README.md) · [日本語](README-ja.md) · [繁體中文](README-zh-TW.md) · [简体中文](README-zh.md) · [Deutsch](README-de.md) · [Français](README-fr.md) · [Español](README-es.md) · Bahasa Indonesia

# VoiceFlow - Aplikasi Text-to-Speech Canggih

[![Live Demo](https://img.shields.io/badge/Live_Demo-blue?style=for-the-badge)](https://text-speech.pages.dev)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)
[![GitHub issues](https://img.shields.io/github/issues/didvc/text-to-speech?style=for-the-badge)](https://github.com/didvc/text-to-speech/issues)
[![GitHub stars](https://img.shields.io/github/stars/didvc/text-to-speech?style=for-the-badge)](https://github.com/didvc/text-to-speech/stargazers)

Aplikasi web text-to-speech yang modern dan kaya fitur, dibangun dengan React dan TypeScript. VoiceFlow menyediakan antarmuka intuitif untuk mengubah teks menjadi suara yang terdengar alami, dengan penyorotan kata secara real-time, pengaturan suara yang bisa disesuaikan, dan fitur pengelolaan konten.

## Tangkapan layar

![Antarmuka aplikasi VoiceFlow](https://res.cloudinary.com/dxowqxqtj/image/upload/v1753415581/text-to-speech/voiceflow-main-screenshot.png)

*Antarmuka VoiceFlow yang intuitif, dengan penyorotan kata secara real-time, kontrol suara yang bisa disesuaikan, dan pengelolaan konten.*

## Fitur

### Fungsi inti
- Konversi teks ke suara: sintesis suara berkualitas tinggi dengan Web Speech API
- Penyorotan kata real-time: kata yang dibacakan disorot dengan animasi saat diputar
- Kontrol pemutaran: putar, jeda, dan hentikan dengan kontrol yang responsif
- Banyak pilihan suara: pilih dari suara yang tersedia di sistem, dengan deteksi bahasa

### Kustomisasi
- Kecepatan bicara: atur kecepatan pemutaran dari 0,5x hingga 2x
- Kontrol nada: atur tinggi rendah suara untuk pengalaman mendengar terbaik
- Kontrol volume: atur tingkat keluaran audio
- Pilihan suara: pilih dari suara yang tersedia di sistem

### Pengelolaan konten
- Perpustakaan teks: atur beberapa dokumen teks dengan judul
- Tambah, edit, hapus: pengelolaan konten teks secara lengkap
- Berpindah konten: berpindah antarteks dengan mulus
- Penyimpanan tetap: konten disimpan secara lokal di browser

### Antarmuka
- Tema gelap modern: antarmuka gelap yang elegan dan nyaman di mata
- Desain responsif: berjalan baik di desktop, tablet, dan ponsel
- Nuansa gradien: teks dan elemen visual bergradien yang indah
- Kontrol intuitif: antarmuka yang mudah digunakan dengan umpan balik visual yang jelas

## Memulai

### Prasyarat
- Node.js (versi 16 atau lebih baru)
- npm atau yarn
- Browser modern yang mendukung Web Speech API

### Instalasi

1. Clone repositori
   ```bash
   git clone https://github.com/didvc/text-to-speech.git
   cd text-to-speech
   ```

2. Instal dependensi
   ```bash
   npm install
   # or
   yarn install
   ```

3. Jalankan server pengembangan
   ```bash
   npm run dev
   # or
   yarn dev
   ```

4. Buka browser
   Buka `http://localhost:5173` untuk melihat aplikasinya

### Build untuk produksi

```bash
npm run build
# or
yarn build
```

File hasil build akan tersedia di direktori `dist/`.

## Cara pakai

### Penggunaan dasar
1. Pilih atau tambah teks: pilih dari contoh yang tersedia atau tambahkan teks Anda sendiri
2. Atur pengaturan: sesuaikan suara, kecepatan, nada, dan volume sesuai selera
3. Putar: klik tombol putar untuk memulai konversi teks ke suara
4. Ikuti bacaan: lihat penyorotan kata secara real-time saat teks dibacakan

### Fitur lanjutan
- Pengelolaan konten: gunakan perpustakaan teks untuk mengatur banyak dokumen
- Ganti suara: coba berbagai suara dan bahasa
- Kontrol kecepatan: atur kecepatan membaca untuk pemahaman atau kebutuhan aksesibilitas
- Dukungan ponsel: semua fitur tersedia di perangkat seluler

## Teknologi

- Framework frontend: React 18
- Bahasa: TypeScript
- Build tool: Vite
- Styling: Tailwind CSS
- Ikon: Lucide React
- API suara: Web Speech API (SpeechSynthesis)

## Kompatibilitas browser

VoiceFlow berjalan di browser modern yang mendukung Web Speech API:

- Chrome/Chromium (disarankan)
- Edge
- Safari
- Firefox (pilihan suara terbatas)
- Browser seluler (iOS Safari, Chrome Mobile)

## Desain responsif

VoiceFlow dirancang agar berjalan mulus di semua jenis perangkat:
- Desktop: fitur lengkap dengan tata letak yang dioptimalkan
- Tablet: antarmuka ramah sentuhan dengan kontrol adaptif
- Ponsel: desain ringkas dengan fitur penting yang mudah dijangkau

## Berkontribusi

Kontribusi dari komunitas sangat diterima! Lihat [panduan kontribusi](CONTRIBUTING.md) untuk cara memulai.

### Mulai cepat untuk kontributor
1. Fork repositori
2. Buat branch fitur (`git checkout -b feature/amazing-feature`)
3. Lakukan perubahan
4. Commit perubahan Anda (`git commit -m 'Add amazing feature'`)
5. Push branch (`git push origin feature/amazing-feature`)
6. Buka pull request

## Lisensi

Proyek ini berlisensi MIT; lihat file [LICENSE](LICENSE) untuk detailnya.

## Masalah dan dukungan

- Laporan bug: [buat issue](https://github.com/didvc/text-to-speech/issues/new?template=bug_report.yml)
- Permintaan fitur: [ajukan fitur](https://github.com/didvc/text-to-speech/issues/new?template=feature_request.yml)
- Diskusi: [ikut diskusi](https://github.com/didvc/text-to-speech/discussions)

## Ucapan terima kasih

- Web Speech API yang menyediakan fungsi text-to-speech
- Komunitas React dan TypeScript atas perkakas yang luar biasa
- Tailwind CSS atas sistem styling yang indah
- Lucide React atas ikon yang bersih dan modern

## Keunggulan proyek

- Ukuran build: dioptimalkan untuk pemuatan cepat
- Dependensi: minimal dan dipilih dengan cermat
- Performa: animasi 60 fps yang mulus dan interaksi yang responsif
- Aksesibilitas: sesuai WCAG dengan dukungan navigasi keyboard

---

<div align="center">

[Coba VoiceFlow langsung](https://text-speech.pages.dev) | [Dokumentasi](https://github.com/didvc/text-to-speech/wiki) | [Diskusi](https://github.com/didvc/text-to-speech/discussions)

Dibuat oleh [didvc](https://github.com/didvc)

</div>