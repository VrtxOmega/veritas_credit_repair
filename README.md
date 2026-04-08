<div align="center">
  <img src="https://raw.githubusercontent.com/VrtxOmega/Gravity-Omega/master/omega_icon.png" width="100" alt="VERITAS" />
  <h1>VERITAS CREDIT REPAIR AI</h1>
  <p><strong>AI-Powered Credit Analysis & Dispute Generation Platform</strong></p>
  <p><em>Powered by Gemini 2.5 Pro</em></p>
</div>

![Status](https://img.shields.io/badge/Status-ACTIVE-success?style=for-the-badge&labelColor=000000&color=d4af37)
![AI](https://img.shields.io/badge/AI-Gemini%202.5%20Pro-blue?style=for-the-badge&labelColor=000000)
![Type](https://img.shields.io/badge/Type-Static%20Web%20App-informational?style=for-the-badge&labelColor=000000)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge&labelColor=000000)

---

A browser-based credit repair assistant that uses Google's Gemini 2.5 Pro to analyze credit reports, identify disputable items, and generate professional dispute letters. Runs entirely in the browser — no server, no backend, no data storage.

> **Your credit data never leaves your browser. Zero server-side processing.**

## Features

- **AI Credit Analysis** - Upload or paste your credit report for automated item-by-item analysis
- **Dispute Letter Generator** - Professional, legally-formatted dispute letters with consumer protection citations
- **Multi-Bureau Support** - Templates for Equifax, Experian, and TransUnion disputes
- **Score Simulator** - Estimate potential score impact from successful disputes
- **FCRA/FDCPA Citations** - Automatic inclusion of relevant consumer protection statutes
- **Export to PDF** - Download dispute letters ready for certified mail
- **Dark Mode** - VERITAS gold-and-obsidian interface

## Architecture

| Component | Technology | Purpose |
|-----------|-----------|---------|
| **Frontend** | HTML/CSS/JS | Single-page application, no build step |
| **AI Engine** | Gemini 2.5 Pro API | Credit analysis, dispute generation, legal citations |
| **Storage** | Browser localStorage | Session persistence (optional, clearable) |

## Quick Start

1. Open `index.html` in any modern browser (Chrome recommended)
2. Click the API key button to enter your Gemini API key
3. Paste or upload your credit report
4. Review AI-generated analysis and dispute recommendations
5. Generate and export dispute letters

### API Key

This app requires a [Google AI Studio](https://aistudio.google.com/) API key for Gemini 2.5 Pro. The key is stored only in your browser's localStorage and is never transmitted to any server other than Google's API endpoint.

## Tabs

| Tab | Function |
|-----|----------|
| **Dashboard** | Credit score overview and quick analysis |
| **Reports** | Detailed item-by-item credit report analysis |
| **Disputes** | Generate and manage dispute letters |
| **Education** | Credit repair guides and FCRA/FDCPA reference |

## Privacy

- **Client-Side Only** - No backend server, no database, no cookies
- **API Direct** - Gemini calls go directly from your browser to Google's API
- **No Persistence** - Clear localStorage to remove all data instantly
- **Open Source** - Full source code visible and auditable

## License

MIT

---

<div align="center">
  <sub>Built by <a href="https://github.com/VrtxOmega">RJ Lopez</a> | VERITAS Framework</sub>
</div>