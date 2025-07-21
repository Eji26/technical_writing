# technical_writing
# technical_writing

> A curated collection of templates, style guides, and tooling examples for modern technical writing workflows.

[![CI](https://github.com/Eji26/technical_writing/workflows/CI/badge.svg)](https://github.com/Eji26/technical_writing/actions)
[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)

---

## 📦 Contents

- `/templates` – reusable Markdown & AsciiDoc templates  
- `/style-guide` – in-house writing rules & examples  
- `/snippets` – VS Code / JetBrains snippets for docs-as-code  
- `/workflows` – GitHub Actions that lint, spell-check, and publish docs  

---

## 🚀 Quick Start

1. Clone the repo  
   ```bash
   git clone https://github.com/Eji26/technical_writing.git
   cd technical_writing



2. Install dependencies (optional tools)  
   ```bash
   npm install      # vale, markdownlint, etc.
   ```

3. Use a template  
   ```bash
   cp templates/api-reference.md ./my-new-doc.md
   ```

---

## 🛠️ Tooling

| Tool        | Purpose                            | Command            |
|-------------|------------------------------------|--------------------|
| Vale        | prose linting                      | `npm run lint:md`  |
| Markdownlint| Markdown style checks              | `npm run lint:md`  |
| MkDocs      | build static site (`/site`)        | `mkdocs serve`     |

---

## 🤝 Contributing

1. Fork the repository  
2. Create a feature branch (`git checkout -b add-new-template`)  
3. Commit with clear messages (`git commit -m "feat: add release-notes template"`)  
4. Open a Pull Request

Guidelines are detailed in [CONTRIBUTING.md](CONTRIBUTING.md).

---

## 📋 Changelog

See [CHANGELOG.md](CHANGELOG.md) or the [releases](https://github.com/Eji26/technical_writing/releases) page.

---

## 📄 License

MIT © 2024 Eji26
```
