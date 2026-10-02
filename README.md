# 🌌 Quorix AI — The Intelligent Learning OS

[![Version](https://img.shields.io/badge/version-1.0.0-blue.svg?style=for-the-badge)]()
[![License](https://img.shields.io/badge/license-ISC-green.svg?style=for-the-badge)]()
[![Platform](https://img.shields.io/badge/Platform-Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)]()
[![PWA](https://img.shields.io/badge/PWA-Ready-f6120d?style=for-the-badge&logo=pwa&logoColor=white)]()
[![Docker](https://img.shields.io/badge/Docker-Ready-2496ed?style=for-the-badge&logo=docker&logoColor=white)]()

**Quorix AI** is a state-of-the-art, multi-subject learning platform powered by high-performance Large Language Models (LLMs). It transforms static education into a dynamic, adaptive experience with personalized AI tutoring, spaced-repetition flashcards, and deep mastery analytics.

---

## ✨ Core Pillars

### 📖 Adaptive Curriculum
Bespoke lessons generated in real-time. Whether it's **Quantum Physics** or **Macroeconomics**, Quorix adjusts content depth based on your selected level (School/University) and prior performance.

### 🧠 Cognitive Retention (SM-2)
Never forget what you learn. Our integrated **Spaced Repetition System** uses the SM-2 algorithm to schedule flashcard reviews at the mathematically optimal time for your memory.

### 💬 Neural AI Tutor
A dedicated tutor available 24/7. Ask questions, clear doubts, and get explanations in different personas (Professor, Comrade, or Emoji-friendly).

### 📊 Mastery Analytics
Track your "Learning Velocity" with high-end visualizations. Monitor your XP, level progression, and leaderboard rank in a real-time competitive environment.

---

## 🛠️ Production-Grade Tech Stack

| Layer | Technologies |
| :--- | :--- |
| **Frontend** | Vanilla JS, CSS3 (Glassmorphism), PWA (Service Workers), Chart.js |
| **Backend** | Node.js (Express), JWT Auth, Morgan Logging |
| **Security** | Helmet.js, Express Rate Limit, BcryptJS |
| **Database** | SQLite (Better-SQLite3) with specialized indexing |
| **AI/ML** | Groq LPU™ Inference Engine (Gemma 4 26B) |
| **DevOps** | Docker, GitHub Actions, PWA Manifest |

---

## 🚀 Rapid Deployment

### Standard Installation
```bash
# Clone and enter
git clone https://github.com/padmanabhansb08/Bio-Quorix.git
cd Quorix-AI

# Install dependencies
npm install

# Setup environment
cp .env.example .env
# Edit .env with your GROQ_API_KEY and JWT_SECRET

# Launch
npm start
```

### Docker Deployment (Recommended)
```bash
docker build -t quorix-ai .
docker run -p 8000:8000 --env-file .env quorix-ai
```

---

## 📱 Progressive Web App (PWA)
Quorix AI is fully PWA-compatible. You can "Install" it on your:
- **iOS/Android**: Add to Home Screen for a native app feel.
- **Desktop**: Install via Chrome/Edge for offline access to cached resources.

---

## 🛡️ Security Architecture
- **JWT Authentication**: Secure, stateless user sessions.
- **Rate Limiting**: Protection against DDoS and brute-force attacks.
- **Helmet Headers**: Industry-standard security headers for browser protection.
- **Input Sanitization**: Multi-layer validation for all AI prompts and user data.

---

## 🗺️ Learning Roadmap
- [x] Multi-subject support
- [x] PWA Integration
- [x] Spaced Repetition (SM-2)
- [x] Dockerization
- [ ] Collaborative Study Groups
- [ ] Voice-to-Voice AI Tutoring
- [ ] Advanced Subject-Specific Simulations

---

## 📄 License
This project is licensed under the **ISC License**.

Created with ❤️ by the Quorix Engineering Team.

---

<div align="center">

<a href="https://github.com/santheesh73">
  <img src="https://img.shields.io/badge/Author-Santheesh%20S-181717?style=for-the-badge&logo=github&logoColor=white" alt="Author" />
</a>
<a href="https://github.com/santheesh73?tab=repositories">
  <img src="https://img.shields.io/badge/Projects-santheesh73-DC2626?style=for-the-badge&logo=git&logoColor=white" alt="Projects" />
</a>

<br>

<sub>Developed for the Education purpose • Continuous Learning</sub><br>
<sub>Crafted with care by <a href="https://github.com/santheesh73"><b>Santheesh S</b></a></sub>

</div>

