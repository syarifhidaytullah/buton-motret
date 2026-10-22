# 📸 Buton Motret (`@buton_motret`) — Modern Landing Page with Direct WhatsApp Booking

Landing page modern untuk jasa fotografi olahraga & event **[Buton Motret (@buton_motret)](https://www.instagram.com/buton_motret/)** dengan tema warna **Biru Langit (*Sky Blue*) & Putih Bersih (*Pure White*)** serta sistem pemesanan jadwal yang langsung terhubung ke **WhatsApp**.

---

## ✨ Fitur Utama

1. **Tema Modern Sky Blue & White**:
   - Perpaduan warna biru langit (`#0EA5E9`, `#38BDF8`, `#E0F2FE`) dan latar putih bersih (`#FFFFFF`) dengan efek *glassmorphism* pada navigasi serta kartu interaktif.
2. **Integrasi Identitas Instagram `@buton_motret`**:
   - Kartu *Live Showcase* profil Instagram `@buton_motret` di bagian Hero dengan tombol langsung menuju profil Instagram resmi.
3. **Katalog Paket & Pricelist Fotografi**:
   - Paket *Match Mini Soccer / Futsal*, *Fun Football / Trofeo*, hingga *Turnamen & Event*.
   - Klik tombol **"Pilih & Booking WA"** pada paket mana pun akan langsung memilih paket tersebut di formulir pemesanan.
4. **Filter Galeri Portofolio**:
   - Galeri interaktif dengan filter kategori (*Fun Football & Mini Soccer*, *Running & Basket*, *Event & Portrait*).
5. **Direct WhatsApp Booking Generator**:
   - Formulir pemesanan lengkap (Nama Pemesan, Nama Tim/Komunitas, Pilihan Paket, Tanggal Main, Jam Kick-off, Nama Lapangan/Venue, Add-ons Video Reels/Express Delivery, dan Catatan Jersey).
   - Otomatis menyusun format chat WhatsApp yang rapi dan langsung membuka aplikasi WhatsApp (`wa.me`).
6. **Direct WhatsApp Booking Generator**:
   - Formulir pemesanan lengkap (Nama Pemesan, Nama Tim/Komunitas, Pilihan Paket, Tanggal Main, Jam Kick-off, Nama Lapangan/Venue, Add-ons Video Reels/Express Delivery, dan Catatan Jersey).
   - Otomatis menyusun format chat WhatsApp yang rapi dan langsung membuka aplikasi WhatsApp (`wa.me`) menuju nomor resmi Buton Motret (+62 831-3837-2534).

---

## 🚀 Cara Membuka & Mengatur Nomor WhatsApp

### 1. Buka di Browser
File [index.html](file:///home/rifs/buton-motret/index.html) bersifat *standalone* (HTML, CSS, dan JavaScript sudah menyatu dalam 1 file):
```bash
xdg-open /home/rifs/buton-motret/index.html
```

### 2. Nomor WhatsApp Admin
- **Nomor Default Resmi**: `+62 831-3837-2534` (sesuai bio resmi Instagram @buton_motret).
- **Jika ingin mengganti nomor**: Buka [index.html](file:///home/rifs/buton-motret/index.html) dan sesuaikan konstanta `adminWhatsApp` pada baris skrip:
  ```javascript
  const adminWhatsApp = '6283138372534';
  ```
