# WebToolBox

> **Fast, privacy-focused web utilities for developers.**

WebToolBox is a modern collection of practical browser-based tools designed to make everyday development tasks faster and easier. Format data, encode URLs, convert colors, generate UUIDs and passwords, work with timestamps, analyze text, and more — all from one clean interface.

**No backend. No unnecessary data collection. Just useful developer tools in your browser.**

## ✨ Features

- **JSON Formatter & Validator** — Format and validate JSON with a clean, readable output.
- **Base64 Encoder / Decoder** — Quickly encode or decode Base64 text.
- **URL Encoder / Decoder** — Safely encode and decode URL components.
- **Color Converter** — Convert HEX colors into RGB values.
- **UUID Generator** — Generate unique UUIDs instantly.
- **Unix Timestamp** — Convert timestamps and work with current time values.
- **Text Counter** — Count words, characters, and lines.
- **Password Generator** — Generate strong random passwords locally.
- **Search & Quick Access** — Find tools quickly from the sidebar.
- **Dark / Light Theme** — Switch between themes for a comfortable workflow.
- **Responsive UI** — Designed to work across desktop and mobile screens.
- **Clipboard Support** — Copy generated or converted results with one click.

## 🔒 Privacy First

WebToolBox is designed around a simple principle: **your data should stay yours.**

The tools process input directly in your browser whenever possible. WebToolBox does not require a backend for its core utilities, making it suitable for working with development data without unnecessarily sending it to a server.

> **Tip:** Always avoid entering real passwords, private API keys, access tokens, or other sensitive credentials into any third-party web tool.

## 🛠️ Tech Stack

- **React 19**
- **Vite**
- **JavaScript**
- **Lucide Icons**
- **Modern CSS**
- **Web Crypto API** for secure random generation where applicable

## 🚀 Getting Started

### Prerequisites

Make sure you have **Node.js 20+** and npm installed.

### Installation

```bash
git clone https://github.com/hasnaintanoli/web-toolbox.git
cd web-toolbox
npm install
```

### Start Development Server

```bash
npm run dev
```

Then open the local URL shown by Vite in your browser.

### Production Build

```bash
npm run build
```

### Run Tests

```bash
npm test
```

The current test gate runs the production build to make sure the application compiles successfully before deployment.

## 🔄 CI/CD

WebToolBox uses **GitHub Actions** for its deployment workflow.

The pipeline follows this flow:

```text
Push / Pull Request
        ↓
Install dependencies
        ↓
Run tests
        ↓
Tests pass?
   ↙          ↘
 YES           NO
  ↓             ↓
Deploy       Stop
to Vercel
```

Production deployment is gated behind a successful test job, helping prevent broken builds from being deployed.

## 📁 Project Structure

```text
web-toolbox/
├── .github/
│   └── workflows/
│       └── test-and-deploy.yml
├── public/
│   └── favicon.svg
├── src/
│   ├── main.jsx
│   └── styles.css
├── index.html
├── package.json
└── README.md
```

## 🎯 Why WebToolBox?

WebToolBox brings commonly used developer utilities into a single, focused workspace so you don't have to keep opening different websites for small development tasks.

It is built to be:

- **Fast** — lightweight and responsive.
- **Private** — browser-first processing for core utilities.
- **Simple** — focused interfaces without unnecessary complexity.
- **Practical** — useful for real-world development workflows.
- **Accessible** — responsive across different screen sizes.

## 🗺️ Roadmap

Potential future improvements include:

- More developer utilities
- Additional color formats
- Hash and checksum tools
- JWT utilities
- Regex tester
- Markdown utilities
- Developer-friendly keyboard shortcuts
- Expanded automated test coverage
- PWA / offline support

## 🤝 Contributing

Contributions, ideas, and improvements are welcome.

1. Fork the repository.
2. Create a feature branch.
3. Make your changes.
4. Run `npm test`.
5. Open a pull request with a clear description of your changes.

## 📄 License

This project is open source. See the repository for the applicable license and project terms.

---

**WebToolBox** — practical tools for everyday developers.
