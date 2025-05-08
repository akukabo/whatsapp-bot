# WhatsApp Bot Otomatis – PR Reminder + AI + Aritmatika + Trigonometri
Bot WhatsApp multifungsi berbasis Node.js dan Baileys, dirancang untuk membantu pelajar, komunitas, dan UMKM dengan berbagai fitur otomatisasi, dari pencatat PR, kalkulasi matematika, hingga chatbot AI.

# Fitur Utama
- ✅ Tambah, lihat, dan hapus PR
- 🔢 Operasi Matematika: tambah, kurang, kali, bagi
- 📐 Fungsi Trigonometri: sin, cos, tan
- 🤖 Chatbot AI 
- 🗓️ Penjadwalan pesan menggunakan node-schedule
- 📂 Database ringan dengan lowdb

# Teknologi yang Digunakan
- Baileys – WhatsApp Web API
- Node.js
- LowDB – penyimpanan lokal berbasis file JSON
- Google Generative AI SDK (Gemini)
- QRCode-terminal – tampilkan QR login di terminal

# Cara Menjalankan
1. Clone Repository
2. Install Dependency
   # npm install
3. Ganti API Key Gemini
   Edit baris ini di kode:
   # const ai = new GoogleGenAI({ apiKey: "YOUR_API_KEY_HERE" });
4. Jalankan Bot
   # node index.js
Scan QR code yang muncul di terminal.

# Perintah WhatsApp Bot
# PR & Reminder
- !addpr <isi PR> → Tambah PR
- !listpr → Lihat daftar PR
- !deletepr <nomor> → Hapus PR berdasarkan nomor
- !resetpr → Hapus semua PR

# Kalkulasi Matematika
- !tambah <a> <b> → Penjumlahan
- !kurang <a> <b> → Pengurangan
- !kali <a> <b> → Perkalian
- !bagi <a> <b> → Pembagian

# Trigonometri
- !sin <derajat>
- !cos <derajat>
- !tan <derajat>

# AI Chat
- ai <pertanyaan> → Jawaban dari Gemini AI

# Kontak & Bantuan
Discord : @akukabo
