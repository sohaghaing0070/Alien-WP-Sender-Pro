# 🛸 Alien WP Sender Pro (Enterprise Desktop Edition)

**Developer**: Alien Software Development  
**WhatsApp Support**: [+8801710978997](https://wa.me/8801710978997)  
**Official Website**: [aliensoftwaredevelopment.com](https://aliensoftwaredevelopment.com)  
**Online Documentation Hub**: [aliensoftwaredevelopment.com/docs/alien-wp-sender-pro](https://aliensoftwaredevelopment.com/docs/alien-wp-sender-pro)

A high-performance C# .NET Desktop Application designed for dynamic WhatsApp messaging, bulk CSV/Excel marketing campaigns, AI copywriting & tone rewriting, multi-attachment dispatching, and anti-ban automation powered by an embedded SQLite database (`alien_wp_sender.db`) and a silent Node.js Baileys REST API Gateway with live in-app QR code pairing.

---

## 🌟 Pro Features & Architecture

### 1. 🤖 AI Copywriter, Tone Rewriter & Anti-Spam Safety Analyzer
- **Multi-Engine AI Integration**:
  - **Built-in Smart Engine**: 100% Offline, free, instant generation with automatic Spintax across 10+ industries.
  - **Google Gemini API**: Full integration with `gemini-1.5-flash` and `gemini-pro`.
  - **OpenAI / DeepSeek / ChatGPT API**: Full integration with `gpt-4o-mini`, `gpt-4o`, and custom endpoints.
- **Web / Doc URL Knowledge Extractor**: Provide any product or landing page URL (e.g. `https://aliensoftwaredevelopment.com`), and the AI reads the website to craft targeted marketing copy!
- **Tone Polisher**: Rewrite any message into Professional, Urgent / FOMO, Friendly, Short SMS-style, or Emojified.
- **Anti-Spam Risk Score & Safety Meter**: Analyzes trigger words, excessive capitalization, and formatting risk with 1-click **Auto-Fix Spintax** injection.

### 2. 📖 Professional Documentation & Knowledge Base
- Built-in multi-topic documentation viewer with instant search filter.
- Step-by-step guides for QR code pairing, anti-ban best practices, CSV variable mapping, multi-attachment dispatch, AI copywriting, and REST API/Webhooks.
- 1-Click buttons to open official web documentation (`https://aliensoftwaredevelopment.com/docs/alien-wp-sender-pro`) or initiate WhatsApp live chat with support.

### 3. 📤 Direct Send (Single Message & Multi-Attachments)
- Send direct messages with international dial codes.
- **Multiple File Attachments**: Attach and send multiple files (PNG, JPG, WebP, PDF, DOCX, XLSX, MP4, MP3, ZIP) sequentially.
- **1-Click AI Polish**: Instant AI enhancement and Spintax injection directly from the direct send panel.

### 4. 🚀 Bulk Campaign Sender (CSV / Excel Import & Dynamic Mapping)
- Import contacts from `.csv`, `.txt`, `.tsv` files with auto-detected headers.
- **Dynamic Variable Injection**: Map headers to placeholders (e.g. `{{Name}}`, `{{Company}}`, `{{InvoiceNo}}`, `{{Amount}}`, `{{DueDate}}`, `{{City}}`).
- **Anti-Ban Turbo-Shield**:
  - Configurable randomized human delays (e.g., 4s to 10s).
  - Batch cooling pause (e.g., pause 60s after every 20 messages).
  - Live execution controls: `▶️ Start`, `⏸️ Pause / Resume`, `⏹️ Stop`.
  - Automatic skipping of blacklisted numbers.
  - Real-time progress bar, live stats counters, and delivery status grid.

### 5. 🛠️ Number Tools & Spintax Tester
- **Phone Sanitizer**: Cleans raw unformatted numbers into international WhatsApp standards (`+880...`).
- **Spintax Tester**: Test and preview dynamic variations of `{Option1|Option2|Option3}` before launching campaigns.

### 6. 📝 Message Templates Manager
- Create, edit, and delete reusable dynamic templates.
- 1-click export to Direct Send or Bulk Campaign.

### 7. 👥 Contact Book & Blacklist / Opt-Out Filter
- Full CRUD contact management with real-time search and CSV import/export.
- Dedicated **Blacklist** manager to prevent sending to unsubscribed or opted-out numbers.

### 8. 📜 History & Analytics Export
- Search logs by phone and custom date ranges.
- One-click **Export to CSV Report** for campaign analytics.

### 9. ⚙️ Settings & QR Connect (Silent Daemon)
- **Silent Auto-Backend**: Node.js Baileys server automatically launches silently in the background with zero window popups.
- **Live QR Code Scanner**: Renders sharp WhatsApp pairing QR code with automatic live status detection.
- **Session Controls**: Refresh QR, Reconnect, or Disconnect/Logout session.

---

## 🚀 Quick Start Guide

### Launch the Application
Double-click [`Run_App.bat`](file:///D:/MY_C%23%20APP/Whatapp_sender/Run_App.bat) or run:
```bash
dotnet run
```
The Node.js gateway starts silently in the background automatically!
