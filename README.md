🍗 Iyashi No Kage - Official VTuber Website

Selamat datang di repositori website resmi untuk VTuber Iyashi No Kage! Website ini dirancang sebagai halaman perkenalan (debut) yang interaktif, modern, dan responsif. Tema desain menggabungkan elemen awan yang menenangkan dan kecintaan Iyashi pada ayam goreng.

✨ Fitur Utama

Video Hero Background: Latar belakang halaman utama menggunakan video yang diputar secara otomatis (auto-play & loop) untuk memberikan kesan dinamis.

Live Subscriber Counter: Menampilkan jumlah subscriber YouTube secara real-time.

Interactive Lore Video: Tombol "Tonton Lore Iyashi" akan membuka video layar penuh tanpa tombol kontrol yang akan tertutup otomatis saat cerita selesai.

VTuber ID Card (KTP): Menampilkan gambar profil/identitas VTuber dengan desain ala Kartu Tanda Penduduk.

YouTube Integration: Menampilkan video perkenalan utama dan galeri YouTube Shorts.

Galeri Fan Art: Etalase karya seni dari komunitas beserta credit ke ilustrator masing-masing.

Dark/Light Mode: Pengunjung dapat mengubah tema tampilan (terang/gelap) sesuai kenyamanan dengan satu klik.

Mobile-Friendly: Desain yang responsif, dilengkapi dengan navigasi bawah (bottom nav) khusus untuk pengguna smartphone.

🛠️ Teknologi yang Digunakan

Proyek ini dibangun murni menggunakan teknologi front-end tanpa perlu proses kompilasi (build process):

HTML5 - Struktur utama website.

Tailwind CSS (via CDN) - Framework CSS untuk mendesain antarmuka secara cepat dan responsif.

Vanilla JavaScript - Logika untuk Dark Mode, Scroll Navigasi, dan pengontrolan Modal Video.

Google Fonts - Menggunakan font Fredoka untuk judul dan Quicksand untuk teks utama.

Font Awesome - Ikon interaktif (Discord, YouTube, ayam goreng, dll).

🚀 Cara Menjalankan

Karena website ini hanya terdiri dari file HTML statis, kamu tidak perlu menginstal dependency apa pun (seperti Node.js atau npm).

Clone repositori ini atau download file .zip.

Buka folder proyek.

Klik dua kali pada file index.html untuk membukanya di browser (Chrome, Firefox, Edge, dll).

🎨 Panduan Kustomisasi

Untuk mengubah beberapa konten agar sesuai dengan pembaruan, cari dan ubah bagian berikut di dalam index.html:

Video Lore: Cari tag <video id="lore-video-player" src="..."> dan ganti URL src dengan link video MP4 lore terbaru.

Video Background (Hero): Cari tag <video autoplay loop muted playsinline...> di bagian <section id="home"> dan ganti URL src-nya.

Live Subscriber: Cari link livecounts.io/embed/youtube-live-subscriber-counter/UC... dan ganti ID Channel (UCguA4kxlPY0us979Jx1h7Sg) dengan ID YouTube kamu.

Tautan Sosial Media: Cari https://discord.gg/yourlink atau lambang href="#" pada bagian Footer & Navbar, lalu ganti dengan link asli sosial mediamu.

Gambar KTP / Fan Art: Ganti URL di dalam atribut src pada tag <img> yang sesuai.

💖 Special Thanks / Credits

Proyek ini tidak akan terwujud tanpa bantuan orang-orang hebat berikut:

@Mama_Art - Character Design & Visual.

@Papa_Rig - Live2D Rigger.

Katamamahbisacoding - Web Developer.

Dibuat dengan cinta dan sepotong ayam goreng 🍗
