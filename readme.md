# Clip-Vault

> **Copy once. Access forever.**  
> Your clipboard's new memory — simple, secure, and always within reach.

---

## What is Clip-Vault?

Clip-Vault is a **floating clipboard manager** that automatically saves everything you copy—text, links, images, and code—making your clipboard history instantly accessible without breaking your workflow.

**The Problem:** Every day, you copy important information and lose it when you copy something else. Research shows 75% of users lose clipboard content daily, wasting time scrolling back or recopying lost items.

**The Solution:** Clip-Vault quietly captures every copy action and stores it locally on your device. A small floating bubble stays visible across all apps, giving you instant access to your clipboard history with a single tap.

![Clip-Vault Demo](assets/demo.gif)

---

## The Problem We're Solving

**Copy-paste is broken for knowledge workers.**

Here's what happens every day:
1. You copy an important quote, link, or code snippet
2. You switch apps and copy something else
3. **The first item is gone forever**
4. You waste 5+ minutes finding it again or give up entirely

**Real user pain points:**
- 75% of users lose copied content daily (based on our 12-person survey)
- 58% don't know clipboard history exists on their device
- Existing clipboard managers are buried in system menus or require keyboard shortcuts
- No seamless cross-app access — you have to stop what you're doing

This isn't just frustrating — **it's a productivity tax everyone pays daily.**

---

## How Clip-Vault Solves This

Clip-Vault works on three core principles:

### 1. **Always Visible, Never Intrusive**
A floating bubble stays on your screen across all apps. No keyboard shortcuts to memorize, no app switching required.

### 2. **Automatic Capture**
Every time you copy something, Clip-Vault saves it automatically. Your clipboard history grows without you thinking about it.

### 3. **Instant Access**
Tap the bubble → see your last 5 clips → tap to paste. **Total time: 2 seconds.**

**Result:** Never lose copied content again. Stay focused. Work faster.

---

## Who It's For

**Knowledge Workers & Analysts**  
Copying data between spreadsheets and documents all day. Clip-Vault eliminates the endless "wait, where did I copy that from?" moments.

**Developers & Engineers**  
Stop scrolling terminal history to find that API response or error message. Clip-Vault remembers your code fragments and configurations.

**Students & Researchers**  
Managing quotes from multiple papers for citations? Clip-Vault organizes them automatically so you can focus on writing.

**Content Creators & Marketers**  
Reusing captions, hashtags, and templates constantly. Pin frequently-used content and access it instantly.

---

## Key Features

### Bubble Interface
- Always-on-top button visible across all apps
- Draggable to any screen position
- Subtle pulse animation when new content is captured

### Unlimited Clipboard History
- Auto-saves every copy action instantly
- Supports text, links, images, code snippets
- Everything stored locally on your device

### Quick Access Panel
- Tap bubble to see your 5 most recent clips
- One-tap to copy any item back to clipboard
- Access in under 2 seconds

### Smart Search
- Real-time search across all saved clips
- Intelligent keyword matching
- Results highlight matched terms

### Pin Important Clips
- Mark frequently-used content (templates, addresses, snippets)
- Pinned clips never auto-delete
- Always accessible at the top

### Smart Collections
- Auto-categorizes clips into Work, Research, Design, Personal
- Keeps your history organized without manual effort

### Lock Sensitive Clips
- Protect passwords and private info with a 4-digit PIN
- AES-256 encryption
- Locked clips require PIN to view

### Easy Management
- Delete individual clips or clear all history
- Auto-delete old clips after 30 days (configurable)
- Export your data anytime

---

## Technology

**Built with modern, proven technologies:**

**Desktop:** Electron (cross-platform: Windows, macOS, Linux)  
**Mobile:** React Native (iOS, Android)  
**Database:** SQLite (local, fast, zero-config)  
**Frontend:** React + TailwindCSS  
**Security:** Node.js Crypto (AES-256 encryption)

**Future:** Supabase for optional encrypted cloud sync

For detailed technical architecture, see [systemArchitecture.md](systemArchitecture.md)

---

## Roadmap

### **Phase 1: MVP (Current Focus)**
- Floating bubble interface
- Automatic clipboard capture
- Local storage with search
- Smart collections
- PIN-protected clips

**Target:** Public launch for Windows, macOS, Linux

### **Phase 2: Growth (Months 4-6)**
- Cloud sync (encrypted, optional)
- Multi-device synchronization
- Browser extension
- Advanced search features
- Premium tier ($4.99/month)

### **Phase 3: Team Features (Months 7-12)**
- Team workspaces
- Shared collections
- Enterprise features

### **Phase 4: AI Intelligence (Future)**
- Auto-summarization
- Smart suggestions
- Natural language search

---

## Privacy & Security

### **Our Privacy Promise**

**1. Local-First**  
All clips stay on your device by default. No data leaves your computer unless you opt-in to cloud sync.

**2. You Control Your Data**  
Enable/disable capturing anytime. Delete or export your data whenever you want.

**3. Strong Encryption**  
Locked clips use AES-256 encryption. Your sensitive data is cryptographically secure.

**4. Transparent Sync (Future)**  
Cloud sync is optional and uses end-to-end encryption — the server never sees your plaintext data.

---

## Contributing

Clip-Vault is currently in active development. We welcome:
- **Bug reports** — Found an issue? [Open an issue](#)
- **Feature requests** — Have an idea? Share it
- **Beta testing** — Want early access? Contact us

### Development Setup
```bash
# Clone the repository
git clone https://github.com/breebiira-pm/clipvault.git
cd clipvault

# Install dependencies
npm install

# Run development
npm run dev
```

## Evidence of Functionality

### 1. Live Prototype
- [Clip-Vault Prototype](https://clip-vault-ease.lovable.app/)
- Screenshots:
  - [Welcome Screen](prototype_screenshots/welcome_screen.png)
  - [Dashboard](prototype_screenshots/dashboard_screen.png)
  - [Floating Bubble](prototype_screenshots/floating_bubble.png)
  - [Quick Access Panel](prototype_screenshots/quick_access_panel.png)
  - [Collections Screen](prototype_screenshots/collections_screen.png)
  - [Settings Screen](prototype_screenshots/settings_screen.png)

### 2. System Architecture
- [Architecture Diagram (View on Miro)](https://miro.com/app/board/uXjVJ48aP6g=/?share_link_id=143480897031)
- [Architecture Diagram (Image)](systemarchitecture_screenhot/clipvault_systemArchitecturee.png)

### 3. Database
- Database Tables:
  - [SQL Query](database_screenshots/sql_query.png)
  - [Actions Table](database_screenshots/table_actions.png)
  - [Clips Table](database_screenshots/table_clips.png)
  - [Clip User Table](database_screenshots/table_clipuser.png)
  - [Collections Table](database_screenshots/table_collections.png)

---

## License

Clip-Vault is released under the [MIT License](LICENSE).

---

## Acknowledgments

Built with love by [Bree PM](https://github.com/breebiira-pm)

**Inspired by:**

- The frustration of losing important copied content
- User research showing 75% of people lose clipboard data daily
- The vision of making productivity tools invisible and effortless

**Special thanks to:**

- The 12 participants in our initial user research
- Beta testers providing invaluable feedback
- The open-source community

---

## Contact

- **GitHub:** [github.com/breebiira-pm/clipvault](https://github.com/breebiira-pm/clipvault)
- **Email:** [biirabridgetb@gmail.com](mailto:biirabridgetb@gmail.com)

---

<div align="center">

**Never lose what you copy again.**

Made with love by productivity nerds, for productivity nerds.

</div>