# 🤝 Contributing to NeuroMap Dataset

First off — thank you for wanting to contribute. Every annotation, correction, and addition makes this dataset more valuable for the entire AI + neuroscience community.

---

## 📋 Table of Contents

- [What You Can Contribute](#what-you-can-contribute)
- [Before You Start](#before-you-start)
- [How to Contribute](#how-to-contribute)
- [Contribution Rules](#contribution-rules)
- [Data Quality Standards](#data-quality-standards)
- [Code of Conduct](#code-of-conduct)

---

## 🧠 What You Can Contribute

| Type | Examples |
|---|---|
| 📸 **Images** | Brain scan references (PNG/JPG), fMRI screenshots with clear source attribution |
| 🏷️ **Annotations** | Emotion labels, intent labels, brain region tags for existing images |
| 📝 **Text Data** | Brain region descriptions, psychology notes, research summaries |
| 🔗 **External Datasets** | Links to CC0 or CC BY licensed fMRI/neuroscience datasets |
| 🐛 **Corrections** | Fixing wrong labels, typos, or inaccurate annotations |
| 📖 **Documentation** | Improving the README, guides, or this file |

---

## ⚠️ Before You Start

Please make sure:

1. **You have rights to the data** — only contribute content you own or that is under a CC0, CC BY, or equivalent open license
2. **No private or identifiable patient data** — never contribute any data that could identify a real person
3. **No copyrighted images scraped from Google** — screenshots from research papers are okay only if the paper is open access and you cite it
4. **Check existing issues first** — someone might already be working on the same thing

---

## 🚀 How to Contribute

### Step 1 — Fork the repo
Click the **Fork** button on GitHub to create your own copy.

### Step 2 — Clone your fork
```bash
git clone https://github.com/YOUR_USERNAME/neuromap-dataset.git
cd neuromap-dataset
```

### Step 3 — Create a branch
Name it clearly based on what you're doing:
```bash
git checkout -b add/emotion-annotations
git checkout -b fix/amygdala-label
git checkout -b docs/update-readme
```

### Step 4 — Make your changes
Follow the data quality standards below before adding anything.

### Step 5 — Commit with a clear message
```bash
git add .
git commit -m "add: 10 new emotion annotations for prefrontal cortex images"
```

### Step 6 — Push and open a Pull Request
```bash
git push origin your-branch-name
```
Then go to GitHub and open a **Pull Request** against the `main` branch. Include:
- What you added or changed
- Source/license of any new data
- Any notes the reviewer should know

---

## 📏 Contribution Rules

- ✅ All contributed data must be openly licensed (CC0, CC BY, or original work)
- ✅ Always include the `source` and `license` fields in annotation entries
- ✅ Images should be clear and relevant to neuroscience / brain psychology
- ✅ Text annotations should be factually grounded — cite sources where possible
- ❌ No AI-generated fake brain scan images
- ❌ No personal or patient-identifiable data of any kind
- ❌ No data scraped from paywalled journals without open access confirmation

---

## 🔬 Data Quality Standards

### For images
- Format: PNG or JPG
- Must show a brain region, scan, or diagram relevant to the dataset's scope
- File name format: `img_XXX.png` (e.g. `img_051.png`)
- Must have a matching annotation row in the relevant CSV

### For annotations
Follow this format exactly when adding rows to the CSV files:

```
image_id, brain_region, emotion_primary, emotion_secondary, intent_state, arousal, valence, psychology_tag, source, license
img_051.png, hippocampus, sadness, grief, withdrawal, low, negative, memory_recall, original, CC BY 4.0
```

- Use lowercase for all label values
- `arousal` must be: `low`, `medium`, or `high`
- `valence` must be: `positive`, `negative`, or `neutral`
- Leave a field blank rather than guessing

### For text data
- Write in clear English
- Cite the source if referencing a research paper
- Keep descriptions factual — no speculation

---

## 🤜 Code of Conduct

This project follows a simple standard:

- Be respectful to all contributors
- Give credit where it's due
- No spam, self-promotion, or irrelevant PRs
- Science should be open and accessible to everyone

Violations will result in your contribution being declined and potentially being blocked from the repo.

---

## 📬 Questions?

Open a GitHub Issue or reach out directly:

- X: [@debdoesbiz](https://x.com/debdoesbiz)
- GitHub: [debdoesbiz](https://github.com/debdoesbiz)

---

<p align="center">
  <i>Every contribution, big or small, moves neuroscience AI forward.</i>
</p>
