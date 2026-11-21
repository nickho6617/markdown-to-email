# Markdown to Email & HTML Converter

A fast, lightweight, zero-dependency static web app that converts Markdown into email-ready rich text and HTML with automatic inlined CSS. Optimized for 100% free hosting on **GitHub Pages**.

## Features

- **Email-Safe Inlined CSS**: Injects styles directly into HTML tags (`p`, `h1-h6`, `table`, `code`, `blockquote`, `ul/ol/li`) so email clients like **Microsoft Outlook**, **Gmail**, and **Apple Mail** render typography, tables, and code blocks cleanly without stripping styles.
- **Auto-Cleaner for Messy Text**: One-click cleaner that strips terminal borders (e.g. `│`, `|`), bullet symbols (`•`), and repairs hard-wrapped split lines from console outputs or quoted emails.
- **One-Click Clipboard Actions**:
  - **Copy for Email (Rich Text)**: Direct paste into Outlook, Gmail, Apple Mail, or Word with full formatting.
  - **Copy Clean Markdown**: Grab the sanitized markdown text.
  - **Copy Raw HTML**: Get the inline-styled HTML markup for newsletters or email templates.
- **Customizable Typography**: Choose between standard email-safe fonts (Arial, Segoe UI, Calibri, Georgia, System Default) and font sizes.
- **Zero Build Tools**: Single static HTML page powered by CDN-hosted [marked.js](https://marked.js.org/).

---

## Free Hosting on GitHub Pages (Step-by-Step)

You can host this for free on GitHub Pages in under 2 minutes:

### 1. Initialize Git and Commit
```bash
git init -b main
git add .
git commit -m "Initial commit: Markdown to Email converter"
```

### 2. Create a GitHub Repository & Push
Create a new public or private repository on GitHub (e.g., `markdown-to-email` or `markdown-to-html`), then run:
```bash
git remote add origin https://github.com/<YOUR-USERNAME>/<YOUR-REPO-NAME>.git
git push -u origin main
```

### 3. Turn on GitHub Pages
1. Go to your repository on GitHub.
2. Click **Settings** > **Pages** (in the left sidebar).
3. Under **Build and deployment**:
   - **Source**: Select `Deploy from a branch`.
   - **Branch**: Select `main` and `/ (root)`.
4. Click **Save**.
5. Within 1 minute, your site will be live at:
   `https://<YOUR-USERNAME>.github.io/<YOUR-REPO-NAME>/`
