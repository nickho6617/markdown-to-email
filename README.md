# Markdown to Email & HTML Converter

[![Live App](https://img.shields.io/badge/🚀_LAUNCH_APP-Click_Here-2563eb?style=for-the-badge&logo=rocket)](https://nickho6617.github.io/markdown-to-email/)
[![GitHub Pages](https://img.shields.io/badge/Hosted_on-GitHub_Pages-16a34a?style=for-the-badge&logo=github&logoColor=white)](https://nickho6617.github.io/markdown-to-email/)

> ### 🌐 Live Web App: **[https://nickho6617.github.io/markdown-to-email/](https://nickho6617.github.io/markdown-to-email/)**
> *Click the button above or link to open the converter directly in your browser.*

---

A fast, lightweight, zero-dependency static web app that converts Markdown into email-ready rich text and HTML with automatic inlined CSS.

## Features

- **Email-Safe Inlined CSS**: Injects styles directly into HTML tags (`p`, `h1-h6`, `table`, `code`, `blockquote`, `ul/ol/li`) so email clients like **Microsoft Outlook**, **Gmail**, and **Apple Mail** render typography, tables, and code blocks cleanly without stripping styles.
- **Auto-Cleaner for Messy Text**: One-click cleaner that strips terminal borders (e.g. `│`, `|`), bullet symbols (`•`), and repairs hard-wrapped split lines from console outputs or quoted emails.
- **One-Click Clipboard Actions**:
  - **Copy for Email (Rich Text)**: Direct paste into Outlook, Gmail, Apple Mail, or Word with full formatting.
  - **Copy Clean Markdown**: Grab the sanitized markdown text.
  - **Copy Raw HTML**: Get the inline-styled HTML markup for newsletters or email templates.
- **Customizable Typography**: Choose between standard email-safe fonts (Arial, Segoe UI, Calibri, Georgia, System Default) and font sizes.
- **Zero Build Tools**: Single static HTML page powered by CDN-hosted [marked.js](https://marked.js.org/).
