# 🌐 Text Language Translator App

A simple yet powerful **Text Translator App** built using **React**, **Tailwind CSS**, and **RapidAPI's Google Translate API**.

## 🚀 Live Demo
👉 [Link to Live Site](#) — *(Add your Vercel/Netlify link here once deployed)*

---

## 🛠️ Features

- 🌍 Translate text between multiple languages
- 🧠 Powered by Google Translate API (via RapidAPI)
- ⚡ Built with modern React (hooks, async/await)
- 🎨 Beautiful UI with Tailwind CSS
- ✅ Mobile responsive design

---

## 📦 Tech Stack

| Tech            | Used For                         |
|-----------------|----------------------------------|
| React           | Frontend Framework               |
| Tailwind CSS    | Styling & Layouts                |
| Axios           | API Requests                     |
| RapidAPI        | Google Translate API Integration |

---

## 🔑 API Integration

This app uses [Google Translate API](https://rapidapi.com/robust-api-robust-api-default/api/google-translate113/) from RapidAPI.

### Steps to Get API Key:
1. Go to [RapidAPI Marketplace](https://rapidapi.com/)
2. Search for **Google Translate API**
3. Subscribe and copy your `X-RapidAPI-Key`
4. Replace it in `App.js` file:
```js
headers: {
  'X-RapidAPI-Key': 'aad55de45bmshbbf4c364cb4e8a5p1d9c02jsn0bfe34ec578b',
  'X-RapidAPI-Host': 'google-translate113.p.rapidapi.com'
}


📁 Folder Structure
text_language_translator_app/
├── public/
├── src/
│   ├── App.js
│   ├── index.js
│   └── ...
├── tailwind.config.js
├── postcss.config.js
└── package.json


---

## 🧪 Getting Started (Run Locally)

### 📁 Clone the Repository

```bash
git clone https://github.com/Naitik2701/Text_Language_Translator.git
cd Text_Language_Translator
1.npm install
2.npm run start

You can now view text-translator-app in the browser.
Local:            http://localhost:3000
