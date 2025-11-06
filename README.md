<a name="top"></a>
<div align="center">


# 🎓 ScholarSync  
### *Smarter Research, Simplified.*

---

## 📘 Overview

**ScholarSync** is a lightweight web platform that helps students, researchers, and professionals **organize, summarize, and explore research papers** — powered by **Google Generative AI**.

Built using **HTML, CSS, and JavaScript**, it lets users upload PDFs, generate concise summaries, extract keywords, and categorize papers into domains such as **AI**, **ML**, **Web Development**, or **Data Science** — all in a minimal single-page interface.

> ✨ *No heavy frameworks. No complex setup. Just a smart, minimal, AI-powered research manager.*

---

## 🚀 Features

- 📄 Upload and manage research papers (PDFs)  
- 🧠 AI-powered summarization (via **Google Gemini API**)  
- 🏷️ Automatic keyword extraction  
- 🔍 Smart categorization and instant search  
- 💾 Secure storage and hosting using **Firebase**  
- 📱 Clean, responsive single-page design  

---

## 🎯 Problem Statement

Researchers and students often deal with scattered PDFs and lengthy papers.  
Finding relevant insights and managing academic material is time-consuming.  
There’s a need for a simple, centralized, and intelligent platform to organize and digest research content efficiently.

---

## 💡 Solution

**ScholarSync** provides a clean, AI-driven interface to:
- Upload research papers  
- Auto-summarize with **Google Gemini API**  
- Extract keywords and topics  
- Categorize by research field  
- Save and access summaries anytime  

This allows users to focus on learning and innovation instead of manual data handling.

---


## 🧩 Architecture

```text
📄 PDF Upload
   ↓
   📘 Google Document AI / pdf.js → Extract Text
   ↓
   🤖 Google Gemini API → Generate Summary + Keywords
   ↓
   💾 Firebase → Store & Display Results

----

**🛠️ Tech Stack**
 - HTML 
 - CSS
 - JavaScript 
 - Python
 - Google Gemini Tools

----
## 📂 Project Structure


```
📦 Research-Paper-Organizer
├── 📂 .github/  <br>               # GitHub workflows, issue & PR templates <br> 
├── 📂 .vscode/   <br>                # VS Code workspace settings <br> 
├── 📂 backend/   <br>                # Backend code <br> 
│   ├── 📂 src/   <br>                
│   │   ├── 📂 config/   <br>         # Configuration files <br> 
│   │   ├── 📂 controllers/ <br>      # Business logic <br> 
│   │   ├── 📂 middleware/  <br>      # Middleware functions <br> 
│   │   ├── 📂 models/      <br>      # Database models <br> 
│   │   ├── 📂 routes/      <br>      # API routes <br> 
│   │   ├── 📂 utils/      <br>       # Helper utilities <br> 
│   │   └── 📜 app.js     <br>        # App entry point <br> 
│   │
│   ├── 📜 .env.example          # Example environment variables <br> 
│   ├── 📜 .gitignore            # Git ignore rules <br> 
│   ├── 📜 package-lock.json     # Dependency lockfile <br> 
│   ├── 📜 package.json          # Backend dependencies & scripts <br> 
│   └── 📜 test-env.js           # Environment test script <br> 
│
├── 📂 css/          <br>             # Stylesheets <br> 
│   ├── 📜 Tag-Based-filtering.css<br> 
│   ├── 📜 about.css<br> 
│   ├── 📜 add-organize-papers.css<br> 
│   ├── 📜 ats-checker.css<br> 
│   ├── 📜 auth.css<br> 
│   ├── 📜 blog.css<br> 
│   ├── 📜 contact.css<br> 
│   ├── 📜 faq.css<br> 
│   ├── 📜 forgot-password.css<br> 
│   ├── 📜 glossary.css<br> 
│   ├── 📜 hemingway.css<br> 
│   ├── 📜 research ethics.css<br> 
│   ├── 📜 pdf-annotator.css<br> 
│   ├── 📜 pdf-viewer.css<br> 
│   ├── 📜 profile-settings.css<br> 
│   ├── 📜 style.css<br> 
│   ├── 📜 summarize.css<br> 
│   └── 📜 tool.css<br> 
│
├── 📂 docs/         <br>             # Documentation files
├── 📂 favicon/       <br>            # Favicon & PWA assets
├── 📂 images/        <br>            # Image assets
├── 📂 js/            <br>            # JavaScript files
│
├── 📜 .gitignore
├── 📜 Faq.html
├── 📜 License
├── 📜 Masthead.html
├── 📜 Pdfconverter.html
├── 📜 Research_Paper_Summary.py
├── 📜 TODO.md
├── 📜 Tag-Based-filtering.html
├── 📜 about.html
├── 📜 about_new.html
├── 📜 add-organize-papers.html
├── 📜 app.js
├── 📜 ats-checker.html
├── 📜 auth-callback.html
├── 📜 blog.html
├── 📜 contact.html
├── 📜 forgot-password.html
├── 📜 glossary.html
├── 📜 hemingway.html
├── 📜 home.html
├── 📜 index.html
├── 📜 landing.css
├── 📜 landing.js
├── 📜 login.html
├── 📜 manage.py
├── 📜 offline.html
├── 📜 research ethics.html
├── 📜 package.json
├── 📜 pdf-annotator.html
├── 📜 pdf-viewer.html
├── 📜 privacy.html
├── 📜 profile-settings.html
├── 📜 profile.html
├── 📜 roadmap.html
├── 📜 signup.html
├── 📜 site.webmanifest
├── 📜 slider.css
├── 📜 summarize.html
├── 📜 terms-of-service.html
├── 🖼️ test1.jpg
├── 🖼️ testimonialw.png
└── 📜 tools.html

```


**💡 How to Use**

1. Clone this repo:

```
git clone https://github.com/Renucode-123/Scholarsync.git
```

2. Open `index.html` in your browser (right click and open with live server).
3. Start adding your research papers directly.

----

## 🚀 Getting Started

Before running the project, make sure you have the following installed:

### ✅ Prerequisites

- **Git** – to clone the repository  

- **Python 3.8+** – required for backend scripts (`manage.py`, `Research_Paper_Summary.py`)  
  
- **Node.js & npm** – required for frontend dependencies (`package.json`)  
  
- **Code Editor (VS Code recommended)** – for editing and running the project  

- **Web Browser (Chrome/Firefox)** – to view the HTML pages

----
 # Team: GenAI team

      -Renu Kumari Prajapati
      -Arushi Thakur

---

**🔮 Future Overview**

This project aims to become a **fully functional research management system** with features like:
- **Cloud Syncing** for research papers.
- **AI-based categorization** for auto-tagging papers.
- **PDF annotation** and in-browser reading.
- **Collaborator mode** for group research.
- **Integration with Google Scholar / Zotero**.

---

**🛠️ Roadmap (Planned Features)**

- * Add localStorage support to save entries*
- * Add dynamic paper upload & preview*
- * Add PDF embedding and reading inside cards*
- * Responsive design for mobile view*
- * Dark mode toggle*
- * Convert to a fully dynamic app (React/Vanilla JS)*
- * Login/signup feature for cloud syncing*

---



