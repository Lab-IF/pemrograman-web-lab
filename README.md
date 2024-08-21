
# Modul Praktikum Pemrograman Web

## Deskripsi

Modul ini dirancang untuk membimbing Anda dalam membangun dan mengoptimalkan aplikasi web menggunakan **Next.js**. Modul ini mencakup berbagai topik penting dalam pengembangan web seperti pembuatan rute, layout, pengoptimalan font dan gambar, pengambilan data dari database PostgreSQL, serta implementasi strategi rendering dinamis seperti **Streaming** dan **Partial Prerendering**.

Setiap bab berfokus pada topik tertentu yang akan membantu Anda mengembangkan keterampilan dalam pengembangan aplikasi web modern.

## Daftar Bab

### [Bab 1: Memulai Proyek](./Chapter-1.md)
- **Tujuan:** Memahami cara memulai proyek Next.js menggunakan `pnpm`.
- **Topik Utama:** Setup proyek, struktur folder, dan integrasi TypeScript.

### [Bab 2: Gaya CSS](./Chapter-2.md)
- **Tujuan:** Mempelajari cara mengatur gaya pada aplikasi menggunakan Tailwind CSS dan CSS Modules.
- **Topik Utama:** Penggunaan CSS global, utilitas Tailwind, dan modul CSS.

### [Bab 3: Mengoptimalkan Font dan Gambar](./Chapter-3.md)
- **Tujuan:** Menambahkan font kustom dan gambar responsif pada aplikasi.
- **Topik Utama:** Optimalisasi font dan gambar dengan `next/font` dan `next/image`.

### [Bab 4: Membuat Layout dan Halaman](./Chapter-4.md)
- **Tujuan:** Membuat rute dan layout yang terstruktur pada aplikasi.
- **Topik Utama:** File-system routing, nested routes, dan pembuatan layout yang dapat digunakan kembali.

### [Bab 5: Navigasi Antar Halaman](./Chapter-5.md)
- **Tujuan:** Menyediakan navigasi mulus antar halaman pada aplikasi.
- **Topik Utama:** Menggunakan `next/link` untuk navigasi sisi klien dan gaya tautan aktif.

### [Bab 6: Mengatur Database](./Chapter-6.md)
- **Tujuan:** Menghubungkan aplikasi ke database PostgreSQL dan melakukan seed data awal.
- **Topik Utama:** Membuat database PostgreSQL dengan Vercel dan menyambungkannya ke Next.js.

### [Bab 7: Mengambil Data](./Chapter-7.md)
- **Tujuan:** Mengambil data dari database dan menampilkannya di dashboard.
- **Topik Utama:** Berbagai metode pengambilan data dan penggunaan `Promise.all()`.

### [Bab 8: Rendering Statis dan Dinamis](./Chapter-8.md)
- **Tujuan:** Meningkatkan performa aplikasi dengan teknik rendering statis dan dinamis.
- **Topik Utama:** Perbedaan antara rendering statis dan dinamis.

### [Bab 9: Streaming](./Chapter-9.md)
- **Tujuan:** Meningkatkan performa dengan menggunakan teknik **Streaming** pada aplikasi.
- **Topik Utama:** Penggunaan `loading.tsx`, `Suspense`, dan skeleton loading.

### [Bab 10: Partial Prerendering (PPR)](./Chapter-10.md)
- **Tujuan:** Menggabungkan rendering statis dan dinamis dalam satu rute dengan fitur **Partial Prerendering**.

### [Bab 11: Menambahkan Pencarian dan Paginasi](./Chapter-11.md)
- **Tujuan:** Menambahkan fitur pencarian dan paginasi pada halaman faktur.
- **Topik Utama:** Penggunaan `useSearchParams`, `useRouter`, dan `usePathname`.

### [Bab 12: Menggunakan Websockets](./Chapter-12.md)
- **Tujuan:** Mengimplementasikan pembaruan secara real-time menggunakan websockets.
- **Topik Utama:** Mengatur koneksi websocket dan menangani data real-time.

### [Bab 13: Menangani Kesalahan](./Chapter-13.md)
- **Tujuan:** Menangani kesalahan dalam aplikasi menggunakan `error.tsx` dan `notFound`.
- **Topik Utama:** Penanganan kesalahan dengan `try/catch` dan pembuatan halaman kesalahan kustom.

### [Bab 14: Meningkatkan Aksesibilitas](./Chapter-14.md)
- **Tujuan:** Memastikan aplikasi dapat diakses oleh semua pengguna, termasuk yang memiliki disabilitas.
- **Topik Utama:** Menggunakan plugin ESLint untuk aksesibilitas, HTML semantik, dan umpan balik kesalahan yang ramah pengguna.

### [Bab 15: Menambahkan Autentikasi](./Chapter-15.md)
- **Tujuan:** Menambahkan autentikasi ke dalam aplikasi menggunakan NextAuth.js.
- **Topik Utama:** Menyediakan proteksi rute dengan Middleware dan menambahkan alur login/logout.

### [Bab 16: Menambahkan Metadata](./Chapter-16.md)
- **Tujuan:** Meningkatkan SEO dan shareability dengan menambahkan metadata ke aplikasi.
- **Topik Utama:** Menambahkan metadata SEO, gambar Open Graph, favicon, dan judul halaman.

## Cara Menjalankan Proyek

1. Clone repositori:
   ```bash
   git clone <your-repo-url>
   ```
2. Install dependencies:
   ```bash
   pnpm install
   ```
3. Setel environment variables dengan menamai ulang `.env.example` menjadi `.env` dan tambahkan rahasia yang diperlukan.
4. Jalankan server pengembangan:
   ```bash
   pnpm dev
   ```
5. Buka `http://localhost:3000` untuk melihat aplikasi di browser.

---

Rangkuman ini memberikan gambaran tentang topik yang dibahas dalam modul praktikum ini dan menyertakan tautan langsung ke setiap bab untuk memudahkan Anda dalam mempelajari lebih lanjut.
