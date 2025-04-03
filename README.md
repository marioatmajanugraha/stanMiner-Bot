# stanMiner-Bot ⛏️

Script ini digunakan untuk mengotomatiskan klik dan level up di game rwa-Miner pada platform GoldStation.

---

## 📌 Fitur
- ✅ Auto klik hingga batas harian (`dailyMax`) menggunakan token dari `tokens.txt`
- 📈 Auto level up ketika `dailyMax` tercapai atau power mencapai 800.746
- 🔌 Dukungan proxy (`proxy.txt`) untuk koneksi aman
- ⏳ Jeda 1 jam setelah `dailyMax` tercapai, dan 10 menit untuk siklus normal
- 📊 Menampilkan status real-time (Level, Power, Status) dalam tabel interaktif
- ⚡ Dukungan multiple token dalam satu tabel

---

## 🚀 Cara Penggunaan

### 1. Clone Repository
```sh
git clone https://github.com/marioatmajanugraha/stanMiner-Bot.git
cd stanMiner-Bot
```

### 2. Install Dependencies
```sh
npm install axios chalk@4 cfonts cli-table3 http-proxy-agent socks-proxy-agent
```

### 3. Siapkan File Tokens
Buat file `tokens.txt` dan isi dengan token akses, satu token per baris. Contoh:
```sh
eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9...
eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9...
```

### 4. (Opsional) Buat Proxy.txt
Jika ingin menggunakan proxy, buat `proxy.txt`. Contoh:
```sh
http://username:password@host:port
socks5://username:password@host:port
```

### 5. Jalankan Script
```sh
node index.obf.js
```

### 6. Ikuti Instruksi
- Pilih apakah ingin menggunakan proxy (y/n)
- Bot akan mulai berjalan otomatis, menampilkan banner, kredit, dan tabel status
- Tekan `Ctrl+C` untuk menghentikan bot

---

## ⚠️ Disclaimer
Gunakan script ini dengan bijak dan sesuai aturan game.

Developer tidak bertanggung jawab atas penyalahgunaan atau banned akun.

---

## 🤝 Kontribusi
Jika ingin berkontribusi, silakan fork repo ini dan ajukan pull request! Kami terbuka untuk ide baru dan perbaikan.

---

## 📞 Kontak
Jika ada pertanyaan, hubungi: [@balveerxyz](https://t.me/balveerxyz)

Join channel Telegram gratis: [Airdrop 888](https://t.me/airdroplocked)
