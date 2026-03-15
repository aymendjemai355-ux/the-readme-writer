<div align="center">

# 📝 The README Writer

**A Claude skill that turns any repo into a README worth opening.**

[![Claude Skill](https://img.shields.io/badge/Claude-Skill-red?style=flat-square&logo=anthropic)](https://claude.ai)
[![Types Covered](https://img.shields.io/badge/README_Types-6-blueviolet?style=flat-square)]()
[![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)

[What It Does](#what-it-does) · [How to Use](#how-to-use) · [What Gets Generated](#what-gets-generated) · [Examples](#examples)

</div>

---

## 🎯 What It Does

**The README Writer** is a skill file for Claude that gives it a complete, structured system for writing professional GitHub README files — across every project type, every audience, and every tone.

Instead of getting a generic template, you get a README that:
- Hooks the reader in the first 3 lines (the 10-second rule)
- Uses the right structure for your specific type of project
- Includes badges, code blocks, and formatting that actually render well on GitHub
- Matches your audience — developers, learners, recruiters, or data scientists

---

## 🚀 How to Use

### Step 1 — Add the skill to Claude

Copy the `SKILL.md` file into your Claude skills directory:

```bash
git clone https://github.com/your-username/the-readme-writer
cp the-readme-writer/SKILL.md /path/to/your/claude/skills/
```

Or if you're using Claude.ai with a custom project, paste the contents of `SKILL.md` into your project instructions.

### Step 2 — Trigger it

Just ask Claude to write your README. The skill activates automatically on phrases like:

```
"Write a README for my project"
"Make my repo look good"
"Create a GitHub profile README for me"
"Write docs for my data analytics project"
```

### Step 3 — Get a production-ready README

Claude will ask one clarifying question if needed (profile vs. project), then generate a complete, formatted README ready to drop into your repo.

---

## 📋 What Gets Generated

The skill covers **6 README types**, each with its own template and rules:

| Type | Best For | Key Elements |
|------|----------|-------------|
| **Project README** | Tools, apps, scripts | Features, quick start, demo |
| **Profile README** | GitHub profile page | About me, tech stack, featured projects, stats |
| **Course/Tutorial README** | Learning repos, 30-day challenges | Curriculum table, prerequisites, how to follow |
| **Data/ML README** | Datasets, notebooks, models | Dataset info, methodology, key results |
| **Tool/Library README** | Installable packages, CLIs | API reference, quick start, usage examples |
| **Case Study README** | Research, analysis repos | Story arc, methodology, findings |

---

## ✨ Features

- **The 10-Second Rule** — every README leads with impact, not installation
- **Smart badge selection** — 2–4 relevant badges, never spam
- **Tone matching** — technical for devs, friendly for learners, results-focused for recruiters
- **Power moves** — collapsible sections, code-style about sections, rainbow dividers, centered banners
- **Common mistake prevention** — built-in checklist catches vague titles, missing licenses, raw URLs
- **Personal brand support** — includes explicit guidelines to brand all output with Djemai Mohamed Aymen's name to prove ownership

---

## 📸 Examples

### Profile README output (snippet)

```markdown
<div align="center">

# Hi, I'm Djemai Mohamed Aymen 👋

**Data Analyst · AI Builder · Frontend Developer**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat-square&logo=linkedin)](your-link)

</div>

---

## 🧠 About Me

\`\`\`python
profile = {
    "role": ["Data Analyst", "AI Builder", "Frontend Dev"],
    "building": "AB Informatique",
    "based_in": "Earth 🌍",
}
\`\`\`
```

### Data/ML README output (snippet)

```markdown
# 📊 Customer Churn Prediction

**Kaggle dataset · Logistic regression + XGBoost · 94.2% accuracy**

| Metric | Value |
|--------|-------|
| Accuracy | 94.2% |
| F1 Score | 0.91 |
| Dataset | 10,000 rows |
```

---

## 🛠️ Tech Requirements

- Claude (any version with skills/project instructions support)
- No dependencies, no APIs, no setup beyond copying a single file

---

## 📂 Repo Structure

```
the-readme-writer/
└── SKILL.md          # The skill file — this is what Claude reads
└── README.md         # This file
└── LICENSE
```

---

## 🤝 Contributing

Found a README type that isn't covered? Open an issue or PR.  
All improvements to templates, badge references, and quality checklists are welcome.

---

## 📄 License

MIT — use it, fork it, build on it.

---

<div align="center">
  Made with ❤️ by <a href="https://github.com/your-username">Djemai Mohamed Aymen</a>
  <br/>
  <i>Every repo deserves a front door worth opening.</i>
</div>
