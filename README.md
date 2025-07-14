
# Gemini Flash API 🔥🤖

Ini adalah proyek backend sederhana yang mengimplementasikan integrasi dengan **Gemini AI API** menggunakan Node.js.

## 📁 Struktur Direktori

```
gemini-flash-api/
├── node_modules/
├── uploads/
├── .env
├── index.js
├── package.json
└── package-lock.json
```

## 🚀 Fitur Utama

- 🔗 Endpoint API untuk berkomunikasi dengan Gemini AI.
- 📦 Upload file (melalui folder `uploads`).
- 🔐 Konfigurasi environment (`.env`).
- 💬 Respons dari Gemini API bisa diproses sesuai kebutuhan (text generation, dsb).

## ⚙️ Instalasi

1. Clone repositori ini:
   ```bash
   git clone https://github.com/username/gemini-flash-api.git
   cd gemini-flash-api
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Buat file `.env` dan isi dengan variabel yang diperlukan, contoh:
   ```env
   GEMINI_API_KEY=your_api_key_here
   ```

4. Jalankan server:
   ```bash
   node index.js
   ```

## 📬 Endpoint Contoh

```http
POST /gemini
Body:
{
  "prompt": "Tulis puisi tentang bulan"
}
```

## 🛠 Teknologi

- Node.js
- Express.js
- Gemini AI API
- dotenv
- Multer (jika upload file digunakan)

## 📌 Catatan

- Pastikan Anda memiliki API key dari Gemini sebelum menjalankan aplikasi ini.
- Endpoint dapat dikembangkan sesuai use case: chat, image, summarization, dll.

## 📄 Lisensi

Proyek ini dibuat untuk pembelajaran pribadi. Feel free to fork or contribute!

---

Happy coding! ✨
