# 🤖 ClaudeXI — Free AI Chat Interface

**The evolution of free Claude access.** A beautiful, open-source, multi-provider AI chat interface that runs entirely in your browser.

> 🌟 **Perfect. Excellent. Free.** — Bring your own API key, chat with multiple AI models, zero cost.

---

## ✨ Features

### 🆓 Free & Open Source
- **Zero server costs** — everything runs in your browser (client-side)
- **BYO API Key** — use your own keys from any provider
- **No lock-in** — switch between models anytime
- **Open source** — MIT license, fork and modify freely

### 🤖 Multi-Provider
| Provider | Models | Free Tier? |
|----------|--------|------------|
| **Anthropic** | Claude 3.5 Haiku, Sonnet, Opus 4 | API key required (pay-as-you-go) |
| **OpenAI** | GPT-4o, GPT-4o Mini | API key required |
| **Groq** | Llama 3.3 70B | ✅ **Free tier available** |
| **Gemini** | Gemini 2.0 Flash | ✅ **Free tier available** |
| **DeepSeek** | DeepSeek Chat | Very low cost |

### 🎨 Beautiful UI/UX
- Dark glassmorphism design
- Smooth animations and transitions
- Syntax-highlighted code blocks
- Responsive — desktop & mobile
- Keyboard shortcuts
- Live streaming responses

### 💾 Privacy & Data
- **No server** — all data stays in your browser (localStorage)
- **Direct API calls** — your requests go straight to the provider
- **No tracking** — zero analytics, zero cookies
- **Export chats** to Markdown or JSON

### 🛠️ Advanced Features
- Custom system prompts
- Temperature and max tokens control
- Chat history management
- Token count estimation
- Copy code with one click
- Regenerate responses

---

## 🚀 Quick Start

### Option 1: Use Online
Open [claudexi.vercel.app](https://claudexi.vercel.app) *(coming soon)* or use GitHub Pages directly.

### Option 2: Run Locally
```bash
# Clone
git clone https://github.com/XunowID/claudexi.git
cd claudexi

# Open in browser (no build step needed)
open index.html
```

**That's it.** No npm install. No build tools. No server.

### Get Your API Keys

| Provider | Get Key |
|----------|---------|
| **Anthropic (Claude)** | [console.anthropic.com](https://console.anthropic.com) |
| **OpenAI (GPT)** | [platform.openai.com](https://platform.openai.com) |
| **Groq (Free)** | [console.groq.com](https://console.groq.com) |
| **Gemini (Free)** | [aistudio.google.com](https://aistudio.google.com) |
| **DeepSeek** | [platform.deepseek.com](https://platform.deepseek.com) |

1. Open ClaudeXI in your browser
2. Click the settings icon (⚙️)
3. Paste your API key(s)
4. Start chatting!

---

## 📸 Screenshots

| Empty State | Chat | Settings |
|-------------|------|----------|
| Clean, minimal start | Streaming with code highlighting | API key & model config |

---

## 🧠 Architecture

```
┌─────────────┐     ┌──────────────┐     ┌─────────────┐
│  Browser     │────▶│  ClaudeXI    │────▶│  API        │
│  (You)       │     │  (index.html)│     │  Provider   │
└─────────────┘     └──────────────┘     └─────────────┘
                          │
                    ┌─────┴──────┐
                    │ localStorage│
                    │ (chats,     │
                    │  settings)  │
                    └────────────┘
```

- **Zero backend** — pure client-side JavaScript
- **Direct API calls** — your browser talks directly to the AI provider
- **Local persistence** — chats stored in browser localStorage
- **Portable** — single HTML file, deploy anywhere (GitHub Pages, Vercel, S3, etc.)

---

## ⚖️ Legal & Disclaimer

> **ClaudeXI is an independent, open-source project.**
>
> - **Not affiliated** with Anthropic, OpenAI, or any API provider.
> - **Not endorsed by or connected to** any of the companies whose APIs are supported.
> - **You provide your own API keys.** All API calls go directly from your browser to the respective provider.
> - **No data is stored on any server.** All conversation data persists only in your browser's localStorage.
> - **This tool is provided "as is"** without warranty of any kind. Use at your own risk.
> - **Respect the terms of service** of each API provider. Do not use this tool for any illegal or prohibited purpose.
> - **API keys are stored locally** in your browser's localStorage. They are never sent to any third party except the API provider you choose.

---

## 📦 File Size

| File | Size |
|------|------|
| `index.html` | ~38 KB |
| `README.md` | ~2 KB |
| **Total** | **< 45 KB** |

---

## 🛣️ Roadmap

- [ ] Streaming with abort support
- [ ] Image/file upload
- [ ] Markdown preview toggle
- [ ] Search through chat history
- [ ] Custom provider URL support
- [ ] Offline mode (service worker)
- [ ] PWA support

---

## 🤝 Contributing

PRs welcome! Ideas? Open an issue. Found a bug? Fix it.

---

## 📜 License

MIT — use it, modify it, share it. No strings attached.

---

*Built with ❤️ for developers who believe AI should be accessible to everyone.*
