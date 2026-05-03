# 🧠 NeuroMap Dataset

> An open-source curated dataset for training AI models in brain-based psychology — emotion detection, intent detection, neural pathway mapping, and cognitive state classification.

![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)
![Status: Active](https://img.shields.io/badge/Status-Active-brightgreen)
![Domain: Neuroscience + AI](https://img.shields.io/badge/Domain-Neuroscience%20%2B%20AI-blueviolet)
![Contributions Welcome](https://img.shields.io/badge/Contributions-Welcome-orange)

---

## 📌 About

**NeuroMap Dataset** is a free, open-source dataset combining brain imaging references, psychological annotations, and structured text data — designed to help researchers and developers build AI systems that understand the human brain.

This dataset focuses on four core areas:

| Area | Description |
|---|---|
| 🧬 **Emotion Detection** | Mapping brain activation patterns to emotional states |
| 🎯 **Intent Detection** | Neural correlates of decision-making and goal-directed behavior |
| 🛤️ **Neural Pathways** | Functional connections between brain regions |
| 🧠 **Psychology Classification** | Psychological states, disorders, and cognitive functions |

---

## 🔬 Data Sources

### Original Data
Collected and curated by the NeuroMap Dataset team. Includes annotated brain scan reference images and psychological text data.

### External Sources
| Dataset | Source | License | Usage |
|---|---|---|---|
| Language Network / TBI Study | [OpenNeuro ds002675](https://openneuro.org/datasets/ds002675) | CC0 | Metadata, annotation schema reference |

> Coffey BJ, Threlkeld ZD, Bodien YB, Edlow BL. *The language network reemerges during recovery from severe traumatic brain injury.* medRxiv 2020. doi: 10.1101/2020.01.10.20017004

---

## 🚀 Getting Started

### Clone the repo
```bash
git clone https://github.com/debdoesbiz/neuromap-dataset.git
cd neuromap-dataset
```

### Load annotations in Python
```python
import pandas as pd

emotions = pd.read_csv('annotations/emotion_labels.csv')
print(emotions.head())
```

### Load text data
```python
import json

with open('text_data/region_descriptions.json') as f:
    regions = json.load(f)

print(regions['amygdala'])
```

---

## 📊 Dataset Stats

| Category | Count |
|---|---|
| Total Entries | 50+ (growing) |
| Brain Regions Covered | 12+ |
| Emotion Classes | 8 primary |
| Psychology Tags | 20+ |
| External Datasets Referenced | 1 (OpenNeuro CC0) |
| Languages | English |

> ⚠️ This dataset is actively growing. Star the repo to get notified of updates.

---

## 🤝 Contributing

Contributions are welcome and encouraged. You can help by:

- Adding new annotated entries to the CSV files
- Improving or correcting existing annotations
- Adding text descriptions for brain regions
- Linking to additional CC0-licensed fMRI datasets
- Translating documentation

**To contribute:**
1. Fork the repo
2. Create a branch (`git checkout -b add/new-annotations`)
3. Make your changes
4. Submit a Pull Request with a clear description

Please read [CONTRIBUTING.md](CONTRIBUTING.md) before submitting.

---

## 📜 License

This dataset is released under the **Creative Commons Attribution 4.0 International (CC BY 4.0)** license.

You are free to:
- ✅ Share — copy and redistribute in any format
- ✅ Adapt — remix, transform, and build upon the data
- ✅ Use commercially

As long as you:
- 📌 Give appropriate credit to **NeuroMap Dataset**
- 📌 Indicate if changes were made

External data from OpenNeuro is licensed under **CC0** (public domain).

---

## 📎 Citation

If you use this dataset in your research or project, please cite:

```bibtex
@dataset{neuromap2025,
  title     = {NeuroMap Dataset: Open Brain-Psychology AI Training Data},
  author    = {Debojeet Mukherjee},
  year      = {2025},
  publisher = {GitHub},
  url       = {https://github.com/debdoesbiz/neuromap-dataset}
}
```

---

## 📬 Contact

Made by **Debojeet Mukherjee** — designer, developer, and AI builder.

- X (Twitter): [@debdoesbiz](https://x.com/debdoesbiz)
- GitHub: [debdoesbiz](https://github.com/debdoesbiz)

---

<p align="center">
  <i>Built for the open science community. Free forever.</i><br/>
  <b>⭐ Star this repo if you find it useful</b>
</p>
