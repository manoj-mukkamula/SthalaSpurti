# 📍 Sthalaspurti – A Heritage Map of India 🇮🇳

*Sthalaspurti* (స్థలస్పూర్తి) is an open-source, AI-powered Streamlit application that lets users document local cultural and historical landmarks by uploading photos and descriptions in regional Indian languages like Telugu.

Our goal is to crowdsource and preserve the diverse heritage of India—one story, one place at a time—while collecting high-quality, multilingual corpus data to support the development of Indian language models.

---

## 🚀 Live Demo

👉 [Try it on Hugging Face Spaces](https://huggingface.co/spaces/your-team/sthalaspurti)

---

## 🎯 Project Objectives

- Build a corpus collection engine disguised as a simple, engaging app.
- Enable multilingual, low-bandwidth, *offline-first* contributions.
- Collect culturally rich *image-text pairs* from real users.
- Showcase India’s diverse local heritage through crowdsourced storytelling.

---

## 🏗 Features

- 📸 Upload photo of a local place (temple, monument, tree, lake, etc.)
- 📝 Add a short description in Telugu or any regional language.
- 🗺 View contributions on an interactive map.
- 🧠 AI-enhanced components:
  - *Image captioning* (optional)
  - *Language detection*
  - *IndicTrans2* for translation
- 📶 Offline-first support: Queue submissions when offline and sync later.
- 🌐 Multilingual UI (Telugu + English)

---

## 🧠 AI Integration

- *Whisper (Offline)*: Converts audio to text (future enhancement).
- *IndicTrans2 (Open-Source)*: For multilingual translation and corpus alignment.
- *Pillow/OpenCV*: Image preprocessing and resizing for low bandwidth upload.

All models used are open-source and run locally when possible.

---

## 🔧 Tech Stack

| Layer | Tech |
|-------|------|
| Frontend | Streamlit |
| Backend | Python |
| ML/AI | HuggingFace Transformers, IndicTrans2 |
| Data Storage | JSON/CSV for MVP; SQLite (optional) |
| Hosting | Hugging Face Spaces |
| Offline Support | Streamlit + Caching + Local queuing |

---

## 👥 Team

- [Your Name] - Full Stack Developer  
- [Teammate 1] - Data Engineer  
- [Teammate 2] - AI/ML Integration  
- [Teammate 3] - UI/UX & Testing  
- [Teammate 4] - Outreach & User Campaigns

---

## 📈 Project Timeline

| Week | Focus |
|------|-------|
| Week 1 | MVP development, Hugging Face deployment |
| Week 2 | User testing in low-bandwidth settings |
| Week 3 | Social media + WhatsApp outreach |
| Week 4 | User feedback, campaign expansion, corpus analysis |

---

## 📣 User Acquisition Strategy

We targeted:
- College students, cultural clubs, and village communities.
- Telugu-speaking users via WhatsApp groups, posters, and Instagram reels.

Incentives included:
- Public recognition on the map.
- Contribution badges and social media shoutouts.
- Certificate of Contribution after 5 uploads.

For details, see our [REPORT.md](./REPORT.md).