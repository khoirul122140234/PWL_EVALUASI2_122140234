Portal Berita - Aplikasi Web Berita Terkini
 Deskripsi Aplikasi
 Portal Berita adalah aplikasi web yang dibangun menggunakan Next.js dan 
mengintegrasikan OAuth2 untuk autentikasi pengguna. Aplikasi ini menyajikan 
berita dari tiga portal berita berbeda yang mencakup berbagai kategori seperti 
Teknologi, Perjalanan, dan Bisnis.
 Fitur Utama
  Autentikasi dengan GitHub OAuth2
 Login menggunakan akun GitHub
 Manajemen sesi pengguna
 Proteksi rute untuk pengguna yang belum login
  Halaman Utama Berita
 Menampilkan daftar berita dari berbagai sumber
 Filter berita berdasarkan kategori
 Tampilan responsif untuk berbagai ukuran layar
 Kartu berita dengan gambar, judul, dan deskripsi
  Halaman Detail Berita
 Tampilan lengkap artikel berita
 Gambar berita beresolusi tinggi
 Informasi sumber dan waktu publikasi
 Navigasi kembali ke halaman utama
  Sumber Berita
 Untitled
 Tech News Indonesia Berita Teknologi)
 Travel Indonesia Berita Pariwisata)
 1
Business Daily Berita Bisnis)
  Standardisasi Data
 Format waktu yang seragam
 Ukuran gambar yang konsisten
 Panjang judul yang terstandarisasi
 Kategorisasi berita yang jelas
 Teknologi yang Digunakan
  Frontend Framework
 Next.js 15.3.2
 React 19.0.0
 TypeScript
  Styling
 Tailwind CSS
 Responsive Design
  Autentikasi
 NextAuth.js
 GitHub OAuth2
  Optimasi
 Next.js Image Optimization
 Client-side Navigation
 Dynamic Routing
 Cara Instalasi
  Clone repository:
 Untitled
 2
git clone URL_REPOSITORY
 cd newsportal
  Install dependencies:
 npm install
  Konfigurasi environment variables:
 Buat file 
.env.local
 Tambahkan konfigurasi GitHub OAuth:
 GITHUB_ID=your_github_client_id
 GITHUB_SECRET=your_github_client_secret
 NEXTAUTH_URL=http://localhost:3000
 NEXTAUTH_SECRET=your_nextauth_secret
  Jalankan aplikasi:
 npm run dev
  Buka browser dan akses:
 <http://localhost:3000
 Struktur Proyek
 newsportal/
 ├── src/
 │   ├── app/
 │   │   ├── components/
 │   │   │   └── NewsCard.tsx
 │   │   ├── news/
 │   │   │   └── [id]/
 Untitled
 3
│   │   │       └── page.tsx
 │   │   ├── login/
 │   │   │   └── page.tsx
 │   │   ├── page.tsx
 │   │   └── layout.tsx
 │   └── data/
 │       └── newsData.ts
 ├── public/
 ├── package.json
 └── next.config.js
 Keunggulan Aplikasi
  User Experience
 Interface yang intuitif dan mudah digunakan
 Navigasi yang lancar antar halaman
 Loading state yang informatif
 Responsif di berbagai perangkat
  Keamanan
 Autentikasi yang aman dengan OAuth2
 Proteksi rute untuk pengguna yang belum login
 Manajemen sesi yang terjamin
  Performa
 Optimasi gambar otomatis
 Client-side navigation untuk transisi halaman yang cepat
 Kode yang terstruktur dan mudah dimaintain
  Konten
 Untitled
 Berita dari berbagai sumber terpercaya
 Kategorisasi yang jelas
 4
Format yang konsisten
 Pengembangan Selanjutnya
  Implementasi fitur pencarian berita
  Penambahan fitur bookmark berita
  Integrasi dengan lebih banyak sumber berita
  Penambahan fitur komentar
  Implementasi sistem notifikasi
