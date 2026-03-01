# ⚡ CampusCreate AI

> **AI-powered content generation suite for every college student.**  
> Generate event posters, Instagram captions, email drafts & AI poster images in under 10 seconds.

<div align="center">



[![AMD Slingshot Hackathon](https://img.shields.io/badge/AMD%20Slingshot-Hackathon%202025-ED1C24?style=for-the-badge&logo=amd)](https://)
[![Powered by gemini](https://aistudio.google.com/api-keys?project=gen-lang-client-0736831853)
[![Image Gen](https://img.shields.io/badge/Images-Pollinations%20AI-c8f135?style=for-the-badge)](https://pollinations.ai)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

</div>

---

## 🎯 What is CampusCreate AI?

College life is full of events — fests, hackathons, cultural nights, workshops, sports meets — but students spend **hours** writing poster copy, captions, emails, and finding designers. CampusCreate AI eliminates all of that.

**Type your event name. Get a full content kit in 10 seconds.**

---

## ✨ Features

| Feature | Description |
|--------|-------------|
| 📢 **Poster Copy** | Bold headlines, taglines & key highlights for notice boards and stories |
| 📱 **Instagram Captions** | 3 uniquely styled captions with emojis and hashtags |
| 📧 **Email Draft** | Complete announcement email with subject line, ready to send |
| 🎨 **AI Image Prompt** | Detailed prompt for DALL-E / Midjourney |
| 🖼️ **Poster Image Generator** | Actual AI-generated poster image via Pollinations AI — free, instant |
| 🛡️ **Responsible AI Bias Check** | Audits all content for bias, exclusionary language & stereotypes |
| 🔐 **Auth System** | Sign up / login with local storage — no backend needed |
| 📊 **Dashboard** | Overview stats, generation history, quick-start templates |
| 📋 **6 Templates** | Pre-filled templates for Fest, Hackathon, Cultural Night, Workshop, Sports, Clubs |

---
## 🚀 Getting Started

### Option 1 — Just open locally (fastest)
```bash
# 1. Clone the repo
git clone https://github.com/YOUR_USERNAME/campuscreate-ai.git

# 2. Open the file
open campuscreate.html   # Mac
# OR double-click campuscreate.html on Windows
```

### Option 2 — Deploy on Replit
1. Go to [replit.com](https://replit.com) → New Repl → HTML/CSS/JS
2. Delete default code
3. Paste contents of `campuscreate.html`
4. Hit **Run** → get a live public URL instantly

---

## 🔑 API Setup

### gemini API (Text Generation)
1. Go to https://aistudio.google.com/apps
2. Sign up → **GET API Keys** → **Create Key**
3. Open `campuscreate.html` in a text editor
4. Find `YOUR_API_KEY_HERE` and replace with your key
5. Save and open in browser

### Pollinations AI (Image Generation)
**No setup needed!** Pollinations AI is completely free with no API key required. Images generate automatically.

---

## 🛠️ Tech Stack

```
Frontend      →  HTML5, CSS3, Vanilla JavaScript (zero frameworks)
AI Text       →  Gemini-APi
AI Images     →  Pollinations AI (free, no key)
Auth          →  localStorage (no backend)
Fonts         →  Cabinet Grotesk + Instrument Serif + JetBrains Mono
Hosting       →  Any static host (Replit, Netlify, GitHub Pages)
```

---

## 📁 Project Structure

```
campuscreate-ai/
│
├── campuscreate.html     # Entire app — single file, zero dependencies
└── README.md             # This file
```

> The entire app is **one single HTML file** — no npm, no build step, no dependencies. Just open and run.

---

## 🧠 How It Works

```
User enters event details
        ↓
Claude API generates 4 content pieces simultaneously
        ↓
Pollinations AI generates a poster image from the AI prompt
        ↓
Responsible AI bias checker audits all content
        ↓
User copies outputs with one click
        ↓
Content saved to local history
```

---

## 🛡️ Responsible AI

CampusCreate AI has a built-in **Responsible AI Bias Checker** that:
- Scans all generated content for gender bias
- Checks for cultural insensitivity
- Flags exclusionary or stereotyping language
- Provides a clear ✅ SAFE / ⚠️ SUGGESTIONS / ❌ NEEDS REVISION report

This aligns with the **Generative AI for Everyone** theme — making AI not just accessible, but **ethical and responsible** for campus use.

---

## 🏆 Built For

**AMD Slingshot Hackathon 2026** — *Generative AI for Everyone* track

> "Open up creation — text, image, audio, video, code — to any student, club, or campus team."

CampusCreate AI directly addresses:
- ✅ Multimodal creativity (text + image generation)
- ✅ Low/no-code app for non-CS students
- ✅ Responsible GenAI with bias checks built into the flow
- ✅ Efficient on-device options (runs entirely in browser)
- ✅ Collaboration-ready outputs (copy & share anywhere)

---

## 👥 Team

Built with ❤️ for AMD Slingshot Hackathon 2026.

---

## 📄 License

MIT License — free to use, modify and distribute.

---

<div align="center">
  <strong>CampusCreate AI</strong> · Powered by Anthropic Claude · AMD Slingshot Hackathon 2025
</div>
