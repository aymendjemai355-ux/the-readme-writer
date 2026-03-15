---
name: the-readme-writer
description: >
  THE README WRITER — A complete skill for writing exceptional GitHub README files.
  Use this skill whenever the user asks to write, create, generate, improve, or fix
  a README, README.md, or any GitHub project documentation. Also trigger when the user
  says "make my repo look good", "describe my project", "write docs for my project",
  "create a profile README", or "make a GitHub page for X". This skill covers ALL
  types of READMEs: repo READMEs, GitHub profile READMEs, course READMEs, tool READMEs,
  ML project READMEs, data analytics READMEs, and portfolio READMEs. MUST activate
  for any request involving GitHub documentation or project description.
---

# THE README WRITER

A master skill for writing professional, visually rich, and compelling GitHub README files.
Covers every type of README — from simple project docs to full profile showcases.

---

## 1. README Types — Detect Which One First

Before writing, identify the type from context:

| Type | Trigger signals | Key goal |
|---|---|---|
| **Profile README** | "my GitHub profile", "github.com/username", no specific project | Showcase identity + work |
| **Project README** | specific tool/app/script mentioned | Explain what it does + how to use |
| **Course/Tutorial README** | "course", "learn", "tutorial", "30 days", "curriculum" | Guide learners step by step |
| **Data/ML README** | dataset, notebook, model, analysis mentioned | Explain data, methods, results |
| **Tool/Library README** | installable package, CLI, API | Quick start + API reference |
| **Case Study README** | "case study", "analysis of", "research" | Tell the story + show findings |

If unclear, ask one question: **"Is this for your GitHub profile page or for a specific project?"**

---

## 2. Core Principles — Apply to ALL READMEs

### 2.1 The 10-Second Rule
A visitor decides in 10 seconds whether to stay. The **first 3 lines** must answer:
- What is this?
- Why should I care?
- What can I do with it?

Never start with installation instructions. Start with **impact**.

### 2.2 Visual Hierarchy
Use badges, dividers, emojis, and tables to break walls of text. GitHub renders Markdown beautifully — use it.

### 2.3 Tone Matching
| Audience | Tone |
|---|---|
| Developers | Technical, direct, show code fast |
| Learners/students | Friendly, encouraging, explain terms |
| Recruiters/clients | Results-focused, show outcomes |
| Data scientists | Methodology first, then results |

### 2.4 Always include these — no exceptions
- Clear title with one-line description
- Badges (relevant ones only — not badge spam)
- Demo or screenshot if possible
- Installation/usage section
- License

---

## 3. Structure Templates by Type

### 3.1 Project README Template

```markdown
<div align="center">

# 🔥 Project Name

**One punchy sentence about what this does and why it matters.**

[![Python](https://img.shields.io/badge/Python-3.10+-blue?style=flat-square&logo=python)](https://python.org)
[![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/username/repo?style=flat-square)](.)

[Demo](#demo) · [Installation](#installation) · [Usage](#usage) · [Contributing](#contributing)

</div>

---

## 🎯 What This Does

[2–3 sentences. What problem does it solve? Who is it for?]

## ✨ Features

- **Feature 1** — short explanation
- **Feature 2** — short explanation
- **Feature 3** — short explanation

## 🚀 Quick Start

\`\`\`bash
git clone https://github.com/username/repo
cd repo
pip install -r requirements.txt
python main.py
\`\`\`

## 📸 Demo / Screenshot

[Image or GIF here]

## 📂 Project Structure

\`\`\`
repo/
├── data/          # datasets
├── notebooks/     # Jupyter notebooks
├── src/           # source code
└── README.md
\`\`\`

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Python | Core language |
| Pandas | Data manipulation |
| ... | ... |

## 📊 Results

[Key findings, metrics, or outcomes]

## 📄 License

MIT © [Your Name]
```

---

### 3.2 Profile README Template

```markdown
<div align="center">

<img src="banner.png" alt="banner" width="100%"/>

# Hi, I'm [Name] 👋

**[Your tagline — e.g., "Data Analyst · Frontend Developer · AI Builder"]**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat-square&logo=linkedin)](your-link)
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-red?style=flat-square)](your-link)
[![Email](https://img.shields.io/badge/Email-Contact-orange?style=flat-square&logo=gmail)](mailto:you@email.com)

</div>

---

## 🧠 About Me

\`\`\`python
profile = {
    "name": "Your Name",
    "role": ["Data Analyst", "Frontend Dev", "AI Builder"],
    "currently": "Building X",
    "learning": "Y",
    "based_in": "Algeria 🇩🇿",
}
\`\`\`

## 🔧 Tech Stack

**Data & ML**
![Python](https://img.shields.io/badge/-Python-333?style=flat-square&logo=python)
![Pandas](https://img.shields.io/badge/-Pandas-333?style=flat-square&logo=pandas)
...

**Frontend**
![React](https://img.shields.io/badge/-React-333?style=flat-square&logo=react)
...

## 🚀 Featured Projects

| Project | Description | Stack | Link |
|---------|-------------|-------|------|
| 🔥 Project 1 | What it does | Python, ML | [→](#) |
| 📊 Project 2 | What it does | React | [→](#) |

## 📈 GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=YOUR_USERNAME&show_icons=true&theme=radical" height="165"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_USERNAME&layout=compact&theme=radical" height="165"/>
</div>

---

<div align="center">
  <i>Let's build something great together.</i>
</div>
```

---

### 3.3 Course/Tutorial README Template

```markdown
# 📚 Course Name

> **Tagline: What students will be able to do after this.**

[![Lessons](https://img.shields.io/badge/Lessons-30-blue?style=flat-square)]()
[![Level](https://img.shields.io/badge/Level-Beginner-green?style=flat-square)]()
[![Language](https://img.shields.io/badge/Language-Python-yellow?style=flat-square)]()

## 🎯 What You'll Learn

By the end of this course, you will:
- [ ] Skill 1
- [ ] Skill 2
- [ ] Skill 3

## 📋 Prerequisites

- Basic knowledge of X
- Python installed
- Nothing else — we start from scratch

## 🗓️ Course Outline

| Week | Topic | Notebook |
|------|-------|---------|
| 1 | Introduction to X | [Open →](link) |
| 2 | Topic 2 | [Open →](link) |
| ... | ... | ... |

## 🚀 How to Use This Course

1. Clone the repo
2. Open notebooks in order
3. Complete exercises at the end of each lesson

## 🤝 Contributing

Found an error? Open an issue or PR — all contributions welcome.
```

---

### 3.4 Data/ML Project README Template

```markdown
# 📊 Project Name

**One line: what data, what question, what method.**

## 🎯 Problem Statement

[What business or research question does this answer?]

## 📁 Dataset

| Field | Value |
|-------|-------|
| Source | Kaggle / Custom / etc. |
| Rows | X,XXX |
| Columns | XX |
| Target | column_name |

## 🔬 Methodology

1. Data cleaning & EDA
2. Feature engineering
3. Model selection
4. Evaluation

## 📈 Key Results

| Metric | Value |
|--------|-------|
| Accuracy | 94.2% |
| F1 Score | 0.91 |

## 🏃 Run It

\`\`\`bash
pip install -r requirements.txt
jupyter notebook analysis.ipynb
\`\`\`

## 💡 Key Findings

- Finding 1
- Finding 2
- Finding 3
```

---

## 4. Badge Reference — Use the Right Ones

### Always relevant
```markdown
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python)](https://python.org)
[![Stars](https://img.shields.io/github/stars/username/repo?style=social)]()
```

### For data/ML repos
```markdown
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)]()
[![Pandas](https://img.shields.io/badge/Pandas-✓-blue)]()
[![scikit-learn](https://img.shields.io/badge/scikit--learn-✓-f89939)]()
```

### For courses
```markdown
[![Lessons](https://img.shields.io/badge/Lessons-30-brightgreen)]()
[![Level](https://img.shields.io/badge/Level-Beginner-blue)]()
[![Arabic](https://img.shields.io/badge/Language-Arabic-red)]()
```

### For profile READMEs
```markdown
![Profile views](https://komarev.com/ghpvc/?username=YOUR_USERNAME&color=red)
[![GitHub followers](https://img.shields.io/github/followers/username?style=social)]()
```

### GitHub Stats cards (profile READMEs only)
```markdown
![Stats](https://github-readme-stats.vercel.app/api?username=USERNAME&show_icons=true&theme=radical)
![Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=USERNAME&layout=compact&theme=radical)
![Streak](https://streak-stats.demolab.com/?user=USERNAME&theme=radical)
```

---

## 5. Quality Checklist — Run Before Delivering

Before outputting any README, silently check:

- [ ] First 3 lines answer: What is this? Why care? What can I do?
- [ ] Title is clear and has an emoji (for personality)
- [ ] At least 2 relevant badges (not badge spam)
- [ ] Code blocks use correct language tags (```python, ```bash, ```sql)
- [ ] Tables are properly formatted
- [ ] No walls of text — broken up with headers, bullets, tables
- [ ] Installation/usage section exists (even if simple)
- [ ] License mentioned
- [ ] Consistent tone throughout
- [ ] Links use descriptive text, not raw URLs
- [ ] `align="center"` used for header section when appropriate

---

## 6. Power Moves — Make It Unforgettable

### Collapsible sections (for long READMEs)
```markdown
<details>
<summary>📦 Full dependency list</summary>

- pandas==2.0.0
- numpy==1.24.0

</details>
```

### Code-style about section (profile READMEs)
```markdown
\`\`\`python
me = {
    "name": "Djemai Mohamed Aymen",
    "role": "Data Analyst + AI Builder",
    "location": "Earth 🌍",
    "building": "AB Informatique",
}
\`\`\`
```

### Horizontal divider with style
```markdown
<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png"/>
```

### Centered banner text
```markdown
<div align="center">
  <h3>🚀 Built with passion in Algeria</h3>
  <p><i>"Code is the new language of the world."</i></p>
</div>
```

---

## 7. Personal Brand Guidelines (for Djemai Mohamed Aymen's repos)

When writing READMEs for any project created by Djemai Mohamed Aymen:
- ALWAYS include `**Built by [Djemai Mohamed Aymen](link)**` to prove ownership of the work
- Ensure it is explicitly stated that Djemai Mohamed Aymen is the author and creator
- Use dark-theme friendly screenshots when possible
- Mention both Arabic and English support where applicable
- Footer signature MUST be exactly:
```markdown
---
<div align="center">
  Made with ❤️ by <a href="https://github.com/username">Djemai Mohamed Aymen</a> · Algeria 🇩🇿
</div>
```

---

## 8. Common Mistakes — Never Do These

| ❌ Bad | ✅ Good |
|--------|---------|
| Starting with "This is a project that..." | Start with what it DOES |
| No badges at all | 2–4 relevant badges |
| Raw GitHub link as text | [Descriptive text](link) |
| All text, no structure | Headers + tables + bullets |
| Missing license | Always mention license |
| Vague description | Specific: "Cleans and analyzes marketing CSVs with pandas" |
| No demo/screenshot | At minimum describe what output looks like |
| Badge spam (20+ badges) | 3–6 maximum |
| Generic "Hello World" title | Specific, punchy, with emoji |
| No contributor/contact info | Always say how to reach you |

---

*THE README WRITER — Every repo deserves a front door worth opening.*
