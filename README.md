
---

# 💬 ChatGPT Professional UI

Antarmuka pengguna (UI) profesional untuk mengintegrasikan kemampuan ChatGPT dalam aplikasi web modern. Dirancang untuk memberikan pengalaman interaktif, bersih, dan responsif kepada pengguna akhir, cocok untuk chatbot, asisten virtual, atau sistem customer support otomatis.

## 🚀 Fitur Utama

* ✅ **Desain Modern & Minimalis** — Tampilan UI bersih dengan elemen yang mudah dibaca dan digunakan.
* 💡 **Percakapan Interaktif** — Mendukung chat berkelanjutan seperti ChatGPT asli.
* 🌙 **Mode Gelap & Terang** — Dukungan tema untuk kenyamanan pengguna.
* 📱 **Responsif** — Optimal di perangkat desktop maupun mobile.
* 🔧 **Integrasi API Mudah** — Siap terhubung dengan OpenAI API atau endpoint GPT lokal.
* 🧠 **Riwayat Percakapan** — Menyimpan dan mengelola histori percakapan.
* 🗂️ **Multi-Session** — Mendukung sesi percakapan terpisah untuk topik berbeda.

## 🛠️ Teknologi yang Digunakan

* React.js / Next.js
* Tailwind CSS / ShadCN UI
* Zustand / Redux (opsional untuk state management)
* Axios / Fetch API untuk komunikasi backend
* OpenAI API / Custom GPT endpoint

## 📷 Cuplikan Tampilan

![Preview Chat UI](preview.png)
*Tampilan mode gelap dari antarmuka percakapan*

## ⚙️ Instalasi

```bash
git clone https://github.com/username/chatgpt-professional-ui.git
cd chatgpt-professional-ui
npm install
npm run dev
```

## 🔌 Konfigurasi API

Edit file `.env.local`:

```env
OPENAI_API_KEY=your_openai_api_key
API_BASE_URL=https://api.openai.com/v1
```

## 🧪 Contoh Penggunaan

```javascript
const response = await fetch('/api/chat', {
  method: 'POST',
  body: JSON.stringify({ message: "Apa itu AI?" }),
});
const data = await response.json();
console.log(data.reply);
```

## 📁 Struktur Folder

```
├── components/         # Komponen UI
├── pages/              # Routing halaman (Next.js)
├── public/             # Aset publik (gambar, icon)
├── styles/             # File CSS global
├── utils/              # Fungsi utilitas (misal format tanggal, panggil API)
```

## ✅ Lisensi

Proyek ini dilisensikan di bawah MIT License. Silakan gunakan dan modifikasi sesuai kebutuhan Anda.

---

## 🙋‍♂️ Kontribusi

Kontribusi sangat terbuka! Silakan fork repo ini, buat perubahan, dan ajukan Pull Request.

---

**Dibuat dengan ❤️ oleh \[Dwi Bakti N Dev]**

---
