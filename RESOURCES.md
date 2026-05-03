# 📚 Resources for Brain & Neuroscience AI Research

A curated list of datasets, tools, research papers, and communities to help you go deeper into brain-based AI — emotion detection, neural pathways, psychology classification, and beyond.

> Pull requests welcome — if you know a great resource not listed here, add it.

---

## 🗄️ Open Datasets

### fMRI & Brain Imaging

| Dataset | Description | License | Link |
|---|---|---|---|
| **OpenNeuro** | 600+ open brain imaging datasets (fMRI, EEG, MEG, PET) hosted by Stanford | CC0 | [openneuro.org](https://openneuro.org) |
| **Human Connectome Project (HCP)** | Unparalleled neural connectivity data from 1,200+ healthy adults | Custom open | [humanconnectome.org](https://www.humanconnectome.org) |
| **ABCD Study** | Adolescent Brain Cognitive Development — largest long-term brain study of child development in the US | Open access | [abcdstudy.org](https://abcdstudy.org) |
| **UK Biobank** | Massive medical database including neuroimaging from 500,000+ participants | Researcher access | [ukbiobank.ac.uk](https://www.ukbiobank.ac.uk) |
| **OASIS** | Longitudinal neuroimaging + clinical data for aging and Alzheimer's research | Open | [oasis-brains.org](https://www.oasis-brains.org) |
| **Natural Scenes Dataset (NSD)** | 7T fMRI data on perception and memory of natural scenes | Open | [naturalscenesdataset.org](http://naturalscenesdataset.org) |
| **Amsterdam Open MRI Collection (AOMIC)** | Multimodal MRI datasets for individual difference analyses | CC0 | [openneuro.org/datasets/ds002785](https://openneuro.org/datasets/ds002785) |
| **Cam-CAN** | Cambridge Centre for Ageing and Neuroscience large-scale lifespan dataset | Open | [cam-can.org](https://www.cam-can.org) |
| **NeuroEmo** | fMRI dataset for 5 emotion states in Indian population (calm, afraid, delighted, depressed, excited) | Open | [openneuro.org/datasets/ds005700](https://openneuro.org/datasets/ds005700) |
| **Spacetop** | 101 participants, 6 hours scanning each — cognitive, affective, social tasks | Open | [openneuro.org](https://openneuro.org) |

### Emotion & Psychology Specific

| Dataset | Description | License | Link |
|---|---|---|---|
| **Emo-FilM** | fMRI + emotion annotations from 30 people watching films. 50 emotion items annotated | Open | [biorxiv.org](https://www.biorxiv.org/content/10.1101/2024.02.26.582043) |
| **DECAF** | MEG-based multimodal database for decoding affective physiological responses | Open | [imec-int.com](https://imec-int.com) |
| **IAPS** | International Affective Picture System — standardized emotional images with ratings | Researcher license | [csea.phhp.ufl.edu](https://csea.phhp.ufl.edu/media.html) |
| **DEAP** | Dataset for emotion analysis using EEG, peripheral physiological signals and video | Open | [eecs.qmul.ac.uk](https://www.eecs.qmul.ac.uk/mmv/datasets/deap) |

---

## 🛠️ Tools & Software

### Data Processing

| Tool | What it does | Link |
|---|---|---|
| **FSL** | Industry standard fMRI analysis toolkit from Oxford | [fsl.fmrib.ox.ac.uk](https://fsl.fmrib.ox.ac.uk) |
| **FreeSurfer** | Brain surface reconstruction and cortical analysis | [freesurfer.net](https://surfer.nmr.mgh.harvard.edu) |
| **SPM12** | Statistical Parametric Mapping — MATLAB-based fMRI analysis | [fil.ion.ucl.ac.uk/spm](https://www.fil.ion.ucl.ac.uk/spm) |
| **Nilearn** | Python library for fast fMRI data manipulation and ML | [nilearn.github.io](https://nilearn.github.io) |
| **MNE-Python** | EEG/MEG analysis in Python | [mne.tools](https://mne.tools) |
| **dcm2niix** | Convert DICOM brain scans to NIfTI format | [github.com/rordenlab/dcm2niix](https://github.com/rordenlab/dcm2niix) |

### Visualization

| Tool | What it does | Link |
|---|---|---|
| **Nilearn Plotting** | Brain map visualization in Python | [nilearn.github.io](https://nilearn.github.io/stable/plotting/index.html) |
| **FSLeyes** | Interactive brain image viewer | [fsl.fmrib.ox.ac.uk/fsl/fslwiki/FSLeyes](https://fsl.fmrib.ox.ac.uk/fsl/fslwiki/FSLeyes) |
| **3D Slicer** | Open-source medical image visualization | [slicer.org](https://www.slicer.org) |
| **BrainPainter** | Generate publication-quality brain illustrations | [github.com/mrazvan22/brain-painter](https://github.com/mrazvan22/brain-painter) |

### AI / ML for Neuroscience

| Tool | What it does | Link |
|---|---|---|
| **Nilearn + scikit-learn** | Decode brain states using ML | [nilearn.github.io](https://nilearn.github.io) |
| **DeepMedic** | Deep learning for brain lesion segmentation | [github.com/deepmedic](https://github.com/deepmedic/deepmedic) |
| **BrainIAK** | Brain Imaging Analysis Kit — advanced ML for fMRI | [brainiak.org](https://brainiak.org) |

---

## 📖 Key Research Papers

| Paper | Why it matters | Link |
|---|---|---|
| Haxby et al. (2001) — *Distributed and Overlapping Representations of Faces and Objects* | Foundational — shows how brain regions encode different visual categories | [science.org](https://www.science.org/doi/10.1126/science.1063736) |
| LeDoux (2000) — *Emotion Circuits in the Brain* | Core reference for amygdala and fear processing | [annualreviews.org](https://www.annualreviews.org/doi/10.1146/annurev.neuro.23.1.155) |
| Damasio (1994) — *Descartes' Error* | Emotion and decision-making linked to neural pathways | Book |
| Coffey et al. (2020) — *Language network reemerges after TBI* | Source of OpenNeuro ds002675 used in this dataset | [medrxiv.org](https://doi.org/10.1101/2020.01.10.20017004) |
| Ekman (1992) — *An Argument for Basic Emotions* | Foundation of emotion classification used in psychology AI | [tandfonline.com](https://www.tandfonline.com/doi/abs/10.1080/02699939208411068) |
| Phan et al. (2002) — *Functional Neuroanatomy of Emotion* | Meta-analysis of emotion brain regions across 55 studies | [neuron.org](https://www.cell.com/neuron/fulltext/S0896-6273(02)00682-9) |

---

## 🌐 Communities & Learning

| Resource | Description | Link |
|---|---|---|
| **Neurostars** | Q&A forum for neuroimaging and brain data analysis | [neurostars.org](https://neurostars.org) |
| **OpenNeuro Slack** | Community of neuroscience data sharers | Via openneuro.org |
| **Brainhack** | Global community of open neuroscience hackers | [brainhack.org](https://brainhack.org) |
| **Coursera — Fundamental Neuroscience for Neuroimaging** | Johns Hopkins course on neuroimaging basics | [coursera.org](https://www.coursera.org/learn/neuroscience-neuroimaging) |
| **Andy's Brain Book** | Free online textbook for fMRI analysis | [andysbrainbook.readthedocs.io](https://andysbrainbook.readthedocs.io) |
| **HuggingFace — Medical/Neuro Datasets** | Growing collection of AI-ready brain datasets | [huggingface.co/datasets](https://huggingface.co/datasets?search=brain) |

---

## 📌 Standards & Formats

| Standard | What it is | Link |
|---|---|---|
| **BIDS** | Brain Imaging Data Structure — the universal format for organizing neuroimaging data | [bids.neuroimaging.io](https://bids.neuroimaging.io) |
| **NIfTI** | Standard file format for brain scan volumes (.nii / .nii.gz) | [nifti.nimh.nih.gov](https://nifti.nimh.nih.gov) |
| **DICOM** | Raw medical imaging format from MRI scanners | [dicomstandard.org](https://www.dicomstandard.org) |
| **CC0 License** | Public domain — no restrictions on reuse | [creativecommons.org/publicdomain/zero/1.0](https://creativecommons.org/publicdomain/zero/1.0) |
| **CC BY 4.0** | Open license — use freely, credit the source | [creativecommons.org/licenses/by/4.0](https://creativecommons.org/licenses/by/4.0) |

---

## 🔗 Related GitHub Repos

| Repo | Description |
|---|---|
| [nilearn/nilearn](https://github.com/nilearn/nilearn) | Machine learning for neuroimaging in Python |
| [bids-standard/bids-starter-kit](https://github.com/bids-standard/bids-starter-kit) | Get started with BIDS format |
| [mne-tools/mne-python](https://github.com/mne-tools/mne-python) | EEG/MEG processing |
| [OpenNeuro datasets on GitHub](https://github.com/OpenNeuroDatasets) | Browse OpenNeuro datasets via DataLad |

---

<p align="center">
  <i>Know a resource that should be here? Open a Pull Request.</i><br/>
  <b>⭐ Star the repo to support open neuroscience AI</b>
</p>
