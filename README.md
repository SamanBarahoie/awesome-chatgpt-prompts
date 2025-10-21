# 🌟 Awesome ChatGPT Prompts

> A curated collection of effective ChatGPT prompts for coding, creativity, learning, and productivity.
>
> 📘 مجموعه‌ای از پرامپت‌های کاربردی و تست‌شده برای استفاده در ChatGPT — از کدنویسی تا تولید محتوا و آموزش.

---

## 📂 Project Overview

**Awesome ChatGPT Prompts** is a structured and community-driven collection of prompts that help you get better results from conversational models like ChatGPT. Each prompt follows a standard format with metadata, examples, and clear instructions.

---

## 🏗 Repository Structure

```
awesome-chatgpt-prompts/
├─ README.md
├─ LICENSE
├─ CONTRIBUTING.md
├─ prompts/
│  ├─ creative-writing/
│  │   ├─ story-idea.md
│  │   └─ character-designer.md
│  ├─ coding/
│  │   ├─ debug-helper.md
│  │   └─ code-explainer.md
│  └─ utilities/
│      ├─ summarizer.md
│      └─ translator.md
├─ examples/
│  └─ creative-writing-example.md
└─ .github/workflows/check-prompts.yml
```

---

## 🧾 Prompt Template (Markdown)

```markdown
---
title: "Summarize Long Texts"
description: "Summarize long Persian texts into 3–4 sentences while keeping main ideas."
tags: [summarization, persian, utility]
model: gpt-4o-mini
temperature: 0.2
examples: true
---

## Purpose
Summarize Persian texts in a concise and readable way.

## Prompt Instruction
`You are a helpful assistant. Summarize the following Persian text in 3–4 sentences, preserving main ideas and avoiding redundancy.`

**Input:**
> (Long Persian text)

**Expected Output:**
- 3–4 clear, concise Persian sentences
- Main ideas preserved
```

---

## 💡 Example Prompts

### ✍️ Creative Writing — Story Idea Generator

```markdown
---
title: "Story Idea Generator"
description: "Generate 5 unique story ideas with a one-line hook."
tags: [creative, storytelling]
model: gpt-4o-mini
temperature: 0.8
---

You are a creative writing assistant. Generate 5 original short story ideas. Each should include a one-line hook and a short summary.
```

### 🐍 Coding — Python Debug Helper

```markdown
---
title: "Python Debug Helper"
description: "Identify the cause of a Python error and suggest a fix."
tags: [coding, python, debugging]
model: gpt-4o-mini
---

You are an expert Python debugger. Given a stacktrace and code snippet, explain the root cause and provide a corrected example.
```

### 🌐 Utilities — Smart Translator

```markdown
---
title: "Smart Translator"
description: "Translate English text to Persian while preserving tone and meaning."
tags: [translation, persian]
model: gpt-4o-mini
temperature: 0.3
---

You are a professional translator. Translate the following English text into fluent Persian, preserving the tone and intent.
```

---

## 🤝 Contributing

1. Fork the repo and create a new branch.
2. Add your prompt in the appropriate folder under `prompts/`.
3. Follow the metadata format (YAML front matter).
4. Submit a Pull Request (PR) describing your changes.

Please make sure each prompt includes:

* Title, Description, Tags
* Model & Temperature (if relevant)
* Example input/output (recommended)

---

## 🧾 License

This project is licensed under the **MIT License** — free for personal and commercial use with attribution.

---

## 🚀 Getting Started

```bash
git clone https://github.com/<your-username>/awesome-chatgpt-prompts.git
cd awesome-chatgpt-prompts
git add .
git commit -m "Initial commit with structure and sample prompts"
git push origin main
```

---

## 🌍 Future Enhancements

* JSON index of all prompts for easy search
* Automated format validator (CI)
* GitHub Pages website to browse prompts visually

---

⭐ If you like this project, consider starring it on GitHub!

> “Better prompts lead to smarter AI — share yours!”
