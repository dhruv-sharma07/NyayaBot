<p align="center">
  <span style="font-size: 60px;">⚖️</span>
</p>

<h1 align="center">NyayaBot</h1>
<h3 align="center">India's AI Legal Advisor — IPC · CrPC · BNS 2024 · 200+ Acts</h3>

<p align="center">
  <a href="#-features"><img src="https://img.shields.io/badge/Indian_Acts-200+-C9A84C?style=for-the-badge&logoColor=white" alt="200+ Acts"/></a>
  <a href="#-quick-start"><img src="https://img.shields.io/badge/Setup-Zero_Config-34D399?style=for-the-badge" alt="Zero Config"/></a>
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-MIT-blue?style=for-the-badge" alt="MIT License"/></a>
  <a href="#"><img src="https://img.shields.io/badge/Cost-100%25_Free-gold?style=for-the-badge" alt="Free"/></a>
</p>

<p align="center">
  <strong>NyayaBot</strong> is a fully self-contained AI legal advisor built exclusively for Indian citizens.<br/>
  Describe your legal problem in plain English or Hindi — NyayaBot identifies the applicable Indian laws, cites specific sections, and provides a concrete step-by-step action plan.
</p>

---

## ✨ Why NyayaBot?

Navigating India's legal system is intimidating, expensive, and slow. NyayaBot bridges the **justice gap** by translating complex legal language into plain, practical advice that every citizen can understand and act upon — **instantly and for free**.

| Pain Point | NyayaBot's Solution |
|---|---|
| Can't afford a lawyer for initial consultation | Free 24/7 AI advisor, no registration |
| Don't know which law applies | Auto-identifies domain + cites exact sections |
| Generic AI gives US/UK legal hallucinations | Trained exclusively on Indian jurisprudence |
| Don't know which portal/court to approach | Names specific portals (e-Daakhil, NCH 1915, cybercrime.gov.in) |
| New BNS/BNSS 2024 laws are confusing | Cross-references old IPC/CrPC → new BNS/BNSS sections |

---

## 🚀 Quick Start

**No server, no API key, no installation needed.** Just open the file:

```bash
# Clone the repo
git clone https://github.com/dhruv-sharma07/NyayaBot.git
cd NyayaBot

# Option 1: Open directly in your browser
# Just double-click index.html — it works immediately!

# Option 2: Local HTTP server (optional, for full experience)
python run.py
# Opens http://localhost:8000 automatically
```

> **That's it.** The built-in legal intelligence engine works 100% offline with zero configuration.

---

## 🏛️ Features

### ⚡ Dual AI Architecture

| Engine | Setup | Cost | Internet |
|---|---|---|---|
| **Built-in Indian Law Engine** (default) | Zero config | Free forever | Not required |
| **Google Gemini API** (optional) | Paste API key | Google's free tier available | Required |
| **OpenAI GPT-4o** (optional) | Paste API key | OpenAI pricing | Required |

### 📚 Comprehensive Indian Legal Corpus

<table>
<tr>
<td width="50%">

**Criminal Law**
- Indian Penal Code (IPC) — All major sections
- Bharatiya Nyaya Sanhita (BNS 2023) — New law mapping
- CrPC & BNSS — Procedural safeguards
- Arrest Rights (D.K. Basu Guidelines)
- FIR Registration (Lalita Kumari mandate)

**Consumer & Commercial**
- Consumer Protection Act, 2019
- E-Commerce Rules, 2020
- Negotiable Instruments Act (Sec 138 Cheque Bounce)
- Indian Contract Act, 1872

</td>
<td width="50%">

**Civil & Property**
- Transfer of Property Act, 1882
- State Rent Control Acts
- Motor Vehicles Act, 2019 (MACT claims)

**Digital & Transparency**
- IT Act, 2000 (Cyber crimes, Sec 66E/67/67A)
- Right to Information Act, 2005

**Family & Employment**
- Hindu Marriage Act, 1955
- PWDVA (Domestic Violence Act), 2005
- Payment of Wages Act, 1936
- POSH Act (Workplace Harassment)

</td>
</tr>
</table>

### 🛠️ Interactive Tools

- **📄 Legal Notice Drafter** — Generate advocate-grade notices for consumer claims, security deposit recovery, unpaid salary, and cheque bounce
- **🎙️ Voice Input** — Speak your problem in English or Hindi using speech recognition
- **🔊 Read Aloud** — Listen to legal advice via text-to-speech
- **📋 Copy & Export** — One-click copy any response, or download full consultation logs as `.txt`
- **🔗 Interactive Previews** — Click any law category or demo card to auto-run the query in the live chatbot

---

## 📂 Project Structure

```
NyayaBot/
├── index.html                           # Complete self-contained web application (HTML + CSS + JS)
├── NyayaBot_Hackathon_Solution_Deck.pdf # 11-Slide Executive Solution Deck (PDF)
├── presentation_deck.html               # Interactive presentation slides (Fullscreen + Print)
├── generate_solution_deck.py            # Python generator script for PDF deck
├── run.py                               # Optional: Local HTTP server with auto-browser launch
├── LICENSE                              # MIT License
├── .gitignore
└── README.md                            # Documentation
```

### 📊 Hackathon Submission Resources
- **PDF Solution Deck:** [NyayaBot_Hackathon_Solution_Deck.pdf](NyayaBot_Hackathon_Solution_Deck.pdf)
- **Interactive Presentation Deck:** [https://dhruv-sharma07.github.io/NyayaBot/presentation_deck.html](https://dhruv-sharma07.github.io/NyayaBot/presentation_deck.html) (Navigate with `◀` `▶` Arrow keys / `Spacebar` / `F11` Fullscreen)

> The entire application is a **single `index.html` file** — no build step, no bundler, no dependencies. Open it and it works.

---

## 🔧 Optional: Connect a Live LLM

While the built-in engine handles 50+ common legal scenarios with detailed statutory guidance, you can optionally connect a live LLM for open-ended conversations:

1. Click **⚙️ Engine** in the chatbot toolbar
2. Select **Google Gemini** or **OpenAI**
3. Paste your API key (stored only in your browser's `localStorage`, never sent anywhere except the provider)
4. Save — the chatbot now uses your chosen LLM with the Indian law system prompt

**Get a free Gemini API key:** [Google AI Studio](https://aistudio.google.com/apikey)

---

## 🤝 Contributing

Contributions are welcome! Some ideas:

- **Add more legal scenarios** to the built-in knowledge base
- **Add Hindi/regional language** UI translations
- **Improve the legal notice templates** with more formats
- **Add dark/light theme toggle**
- **Add landmark Supreme Court case citations**

```bash
# Fork, clone, make changes, then:
git checkout -b feature/your-feature
git commit -m "Add: your feature description"
git push origin feature/your-feature
# Open a Pull Request
```

---

## ⚠️ Disclaimer

> **NyayaBot provides legal information and procedural guidance grounded in Indian statutes for educational and advisory purposes.** It is not a substitute for professional legal representation by a qualified advocate. For serious or complex legal matters, always consult a licensed lawyer enrolled with the Bar Council of India.

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

<p align="center">
  Built with ❤️ for India's 1.4 billion citizens
</p>
