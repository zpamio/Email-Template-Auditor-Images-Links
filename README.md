# 📧 Email Template Auditor: Images & Links

![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)
![No Dependencies](https://img.shields.io/badge/dependencies-none-brightgreen)
![Single File](https://img.shields.io/badge/size-single%20file-orange)
![Browser Ready](https://img.shields.io/badge/browser-ready-blueviolet)

> Paste your HTML email template and instantly audit every image and link before you hit send. No install. No server. Just open and go.

---

## ✨ Features

| Feature | Details |
|---|---|
| 🖼️ **Image Preview** | Live thumbnail of every image found in the template |
| 📐 **Dimension Check** | Intrinsic (file) size vs. actual rendered size |
| 🗑️ **Waste Detection** | Pixel waste % — how oversized the image is |
| 💾 **Size Savings** | Estimated KB you could save by resizing |
| 🔗 **Link Audit** | Every `href` listed with anchor text, URL, and target |
| ⚡ **Zero Setup** | Single `.html` file, works in any modern browser |

---

## 🚀 Quick Start

```bash
# No install needed — just open the file
```

1. Open HTML(https://zpamio.github.io/Email-Template-Auditor-Images-Links/) in any modern browser
2. Paste your full HTML email template into the text area
3. Click **Analyze**
4. Review the results in the two audit tables below

---

## 📊 What You Get

### Image Optimization Table
- Live preview thumbnail
- Intrinsic dimensions (actual file size)
- Rendered dimensions (how it appears in the email)
- Waste percentage + estimated KB savings

### HREF Link Audit Table
- Anchor text or `[Image Link]` label
- Full destination URL (clickable)
- Target attribute (`_blank`, `_self`, etc.)

---

## ⚠️ Known Limitations

- **CORS restricted** — images served with strict CORS headers will show "CORS restricted" instead of file size. This is a browser security constraint, not a bug.
- **Rendered size** — dimensions are measured in a hidden 1200px iframe, which may differ slightly from some email clients.

---

## 📄 License

MIT — free to use, modify, and share.

---

<div align="center">

*Vibe coded with ❤️ and [Claude](https://claude.ai)*

</div>
