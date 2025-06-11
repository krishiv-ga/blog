# Krishiv Agarwal – Quant Portfolio Website

This is the personal website of **Krishiv Agarwal**, an Economics and Finance graduate with experience in venture capital, equity research, and wealth management — now diving deep into quantitative finance.

The site features:
- 🏠 A sleek homepage
- ✍️ A markdown-powered blog
- 💼 A project showcase grid
- 📄 A live HTML resume
- 🔍 Searchable, filterable content
- ⚡ Fast, responsive, and hosted via GitHub Pages

---

## 🚀 Features

### 🧠 Blog
- Markdown-based posts (`.md` in `/Blogs`)
- `posts.json` metadata controls title, date, tags, image
- Automatically sorted by most recent
- Filterable via search bar
- Tag-based category system with custom color themes

### 🛠️ Projects
- Displayed as uniform cards with title, image, subtitle, tags
- Data pulled from `projects.json`
- `starred: true` projects show on the homepage
- Searchable by title, subtitle, or tag
- Responsive layout with fixed card height

### 📋 Resume
- Fully styled, section-based resume
- Snapshot version appears on homepage
- LinkedIn + GitHub icons, styled links

---

## 📁 Folder Structure

```bash
/
├── index.html         # Homepage
├── blog.html          # Blog listing
├── projects.html      # Projects showcase
├── resume.html        # Resume page
├── Blogs/             # Markdown blog posts
├── Projects/          # projects.json lives here
├── Assets/            # Images, logos, icons
├── style.css          # Unified design system
└── README.md
````

---

## ✍️ How to Add New Content

### Add a Blog Post

1. Create a `.md` file in `/Blogs`
2. Add metadata to `posts.json`:

   ```json
   {
     "title": "Risk Parity Basics",
     "filename": "risk-parity.md",
     "image": "Assets/risk.png",
     "date": "2025-06-10",
     "tags": ["quant", "portfolio"]
   }
   ```

### Add a Project

1. Add your image to `/Assets/`
2. Add entry to `projects.json`:

   ```json
   {
     "title": "Smart Portfolio Optimizer",
     "subtitle": "Built in Python, includes entropy constraints",
     "image": "Assets/optimizer.png",
     "link": "https://github.com/krishiv/optimizer",
     "date": "2025-06-01",
     "starred": true,
     "tags": ["python", "risk", "optimization"]
   }
   ```

### Define New Tags

Add to `style.css`:

```css
.tag-yourtag { background-color: #hexcode; color: #fff; }
```

---

## 🧪 Tech Stack

* 💻 HTML5 + CSS3 + JavaScript
* 🎨 Custom dark theme
* 📄 Markdown + JSON
* 🔍 Search via vanilla JS
* 🌐 Hosted on GitHub Pages

---

## 🧠 Author

**Krishiv Agarwal**
Economics + Finance | Quantitative Strategy | Python | Valuation
[LinkedIn](https://www.linkedin.com/in/krishiv-agarwal-7026ab142/)
[GitHub](https://github.com/YOUR_USERNAME)

---

## 📜 License

This project is for personal and educational use. Contact Krishiv directly for reuse or collaboration inquiries.

```

---

Let me know if you'd like a version with:
- A screenshot preview banner
- Shields (e.g. GitHub Pages / license / last updated)
- Setup instructions for local development (if ever needed)
```
