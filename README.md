# 🤖 YusufAI - Universal AI Platform

![YusufAI Banner](frontend/assets/banner.png)

[![GitHub Stars](https://img.shields.io/github/stars/yusuf18081998-blip/YusufAI?style=social)](https://github.com/yusuf18081998-blip/YusufAI)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Made in Uzbekistan](https://img.shields.io/badge/Made%20in-Uzbekistan%20🇺🇿-blue)](https://uz.wikipedia.org/wiki/O%CA%BBzbekiston)

> **4 ta eng kuchli AI bir platformada | 100% Bepul | 500+ Til**

YusufAI - Muhammad Yusuf (13 yosh) tomonidan yaratilgan universal sun'iy intellekt platformasi. ChatGPT-4, Claude 3.5, Gemini Pro va Groq AI'larini bitta interfeys orqali foydalanish imkonini beradi.

🌐 **Live Demo:** [yusuf18081998-blip.github.io/YusufAI](https://yusuf18081998-blip.github.io/YusufAI)

---

## ✨ Xususiyatlar

### 🤖 4 ta AI Model
- **ChatGPT-4** (OpenAI) - Umumiy savol-javob, tahlil
- **Claude 3.5** (Anthropic) - Kreativ yozish, chuqur tahlil
- **Gemini Pro** (Google) - Tezkor javoblar, multi-modal
- **Groq** (Llama 3.3) - Texnik masalalar, dasturlash

### 🎯 Asosiy Imkoniyatlar
- 🎤 **Voice Input** - Ovozli kirish (speech recognition)
- 📄 **PDF Export** - Chatlarni PDF ga eksport
- 🌙 **Dark/Light Mode** - Ko'z uchun qulay rejimlar
- 💾 **Chat History** - Barcha suhbatlar saqlanadi
- 📊 **Statistics** - Foydalanish statistikasi
- 🌍 **500+ Til** - Multilingual support
- 💬 **Real-time** - Jonli javoblar

---

## 🚀 Quick Start

### Prerequisites
- Python 3.8+
- pip
- Modern browser

### Backend Setup

```bash
# Clone repository
git clone https://github.com/yusuf18081998-blip/YusufAI.git
cd YusufAI/backend

# Install dependencies
pip install -r requirements.txt

# Setup environment variables
cp .env.example .env
# Edit .env and add your API keys

# Run server
python app.py
```

Server runs at: `http://localhost:5000`

### Frontend Setup

```bash
# Open demo.html in browser
cd ../frontend
# Use Live Server (VS Code) or simply open demo.html
```

---

## 📖 Documentation

- 📘 [Setup Guide](docs/SETUP.md) - O'rnatish yo'riqnomasi
- 📗 [API Documentation](docs/API.md) - API hujjatlari
- 📙 [Deployment Guide](docs/DEPLOYMENT.md) - Deploy qilish
- 📕 [Contributing](docs/CONTRIBUTING.md) - Hissa qo'shish

---

## 🏗️ Arxitektura

```
┌─────────────────────────────────────┐
│         Frontend (HTML/JS/CSS)      │
│  • Voice Recognition                │
│  • PDF Generation                   │
│  • Theme Management                 │
│  • LocalStorage                     │
└──────────┬──────────────────────────┘
           │ REST API (JSON)
           ▼
┌─────────────────────────────────────┐
│        Backend (Python Flask)       │
│  • API Routes                       │
│  • AI Integration                   │
│  • SQLite Database                  │
│  • Statistics                       │
└──────────┬──────────────────────────┘
           │
    ┌──────┴──────┬──────┬──────┐
    ▼             ▼      ▼      ▼
  GPT-4        Claude  Gemini  Groq
```

---

## 🛠️ Texnologiyalar

### Backend
- **Python 3.8+** - Programming language
- **Flask** - Web framework
- **SQLite** - Database
- **OpenAI API** - ChatGPT-4
- **Anthropic API** - Claude 3.5
- **Google AI API** - Gemini Pro
- **Groq API** - Llama 3.3

### Frontend
- **HTML5** - Markup
- **CSS3** - Styling (Gradients, Animations)
- **JavaScript (ES6+)** - Logic
- **Web Speech API** - Voice input
- **jsPDF** - PDF generation
- **LocalStorage** - Data persistence

### Deployment
- **Railway.app** - Backend hosting
- **GitHub Pages** - Frontend hosting
- **Git** - Version control

---

## 📸 Screenshots

### Landing Page
![Landing](frontend/assets/screenshots/landing.png)

### Chat Interface
![Chat Interface](frontend/assets/screenshots/chat.png)

### Dark Mode
![Dark Mode](frontend/assets/screenshots/dark-mode.png)

### Voice Input
![Voice Input](frontend/assets/screenshots/voice.png)

---

## 🌟 Afzalliklar

| Xususiyat | YusufAI | ChatGPT Plus | Claude Pro |
|-----------|---------|--------------|------------|
| AI modellari | 4 | 1 | 1 |
| Narx | **Bepul** | $20/oy | $20/oy |
| O'zbek tili | ✅ | ⚠️ | ⚠️ |
| Voice Input | ✅ | ❌ | ❌ |
| PDF Export | ✅ | ❌ | ❌ |
| Dark Mode | ✅ | ✅ | ✅ |
| Open Source | ✅ | ❌ | ❌ |

---

## 🗺️ Roadmap

### ✅ Completed
- [x] 4 AI integration
- [x] Voice input
- [x] PDF export
- [x] Dark mode
- [x] Chat history
- [x] Statistics

### 🚧 In Progress
- [ ] User authentication
- [ ] PostgreSQL database
- [ ] Advanced analytics
- [ ] Mobile app

### 📅 Planned
- [ ] Custom AI training
- [ ] Image generation (DALL-E)
- [ ] File upload support
- [ ] Multi-user support
- [ ] API marketplace
- [ ] Enterprise version

---

## 👥 Hissa Qo'shish

Contributions are welcome! 🎉

1. Fork qiling
2. Feature branch yarating (`git checkout -b feature/AmazingFeature`)
3. Commit qiling (`git commit -m 'Add some AmazingFeature'`)
4. Push qiling (`git push origin feature/AmazingFeature`)
5. Pull Request oching

[Contributing Guide](docs/CONTRIBUTING.md) ni o'qing.

---

## 📄 License

MIT License - [LICENSE](LICENSE) faylini ko'ring.

---

## 👨‍💻 Yaratuvchi

**Muhammad Yusuf**
- 📧 Email: yusufaluz1@gmail.com
- 💻 GitHub: [@yusuf18081998-blip](https://github.com/yusuf18081998-blip)
- 📸 Instagram: [@khujayev._](https://instagram.com/khujayev._)
- 📍 Farg'ona, O'zbekiston 🇺🇿

**Yosh:** 13 yosh  
**Maktab:** 45-maktab  
**Tajriba:** 2 yil dasturlash

---

## 🙏 Minnatdorchilik

- OpenAI - ChatGPT API
- Anthropic - Claude API
- Google - Gemini API
- Groq - Llama API
- Railway.app - Hosting
- GitHub - Version control & Pages

---

## 📊 Statistika

![GitHub Stats](https://img.shields.io/github/stars/yusuf18081998-blip/YusufAI?style=social)
![GitHub Forks](https://img.shields.io/github/forks/yusuf18081998-blip/YusufAI?style=social)
![GitHub Issues](https://img.shields.io/github/issues/yusuf18081998-blip/YusufAI)
![GitHub Pull Requests](https://img.shields.io/github/issues-pr/yusuf18081998-blip/YusufAI)

---

## ⭐ Star History

[![Star History Chart](https://api.star-history.com/svg?repos=yusuf18081998-blip/YusufAI&type=Date)](https://star-history.com/#yusuf18081998-blip/YusufAI&Date)

---

## 💬 Muloqot

Savollar, takliflar yoki muammolar bo'lsa:
- 🐛 [Issue oching](https://github.com/yusuf18081998-blip/YusufAI/issues)
- 💬 [Discussions](https://github.com/yusuf18081998-blip/YusufAI/discussions)
- 📧 Email: yusufaluz1@gmail.com

---

<div align="center">

### 🇺🇿 Made with ❤️ in Uzbekistan

**YusufAI** - AI for Everyone

[Website](https://yusuf18081998-blip.github.io/YusufAI) • [Documentation](docs/) • [Report Bug](https://github.com/yusuf18081998-blip/YusufAI/issues) • [Request Feature](https://github.com/yusuf18081998-blip/YusufAI/issues)

⭐ **Loyihani yoqtirdingizmi? Star qo'ying!** ⭐

</div>
