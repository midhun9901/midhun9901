<h1 align="center">Hi, I'm Midhun 👋</h1>

<p align="center">
  M.Sc. student at FAU Erlangen-Nürnberg (Electromobility-ACES, major: AI and autonomous driving),<br/>
  focused on computer vision and deep learning. I like understanding things by building them from scratch, then using them on real problems.
</p>

---

- 🔬 Research project at FAU's Pattern Recognition Lab on **metric learning for image retrieval**
- 🏭 Project thesis on **automated DIC specimen preparation** at the Chair of Manufacturing Technology
- 🧱 Building **deep learning from scratch**, from an autograd engine up to language models
- 🔎 Looking for a **Master's thesis** in computer vision or machine learning, available immediately

## 🚀 Featured projects

### 🏺 [Metric Learning for Vase &amp; Urn Retrieval](https://github.com/midhun9901/vase-urn-project)
Content-based image retrieval for archaeological vases, a research project at FAU's Pattern Recognition Lab.
- Compared **ResNet-50 vs DINOv2** features and Triplet, ProxyAnchor and ArcFace losses across seven experiment families on one fixed split
- Best model: **frozen DINOv2 ViT-S/14 + MLP head + triplet loss: 78.3% mAP, 77.4% Acc@1, 100% Acc@10** on 53 held-out queries (raw DINOv2: 32.7% mAP)
- Audited my own results: found an evaluation bug and a train/test overlap, fixed both and documented them in the repo
- Reproducible pipeline with SLURM jobs for FAU's TinyGPU cluster

`PyTorch` · `DINOv2` · `FAISS` · `metric learning` · `SLURM`

### 🧠 [Deep Learning from Scratch](https://github.com/midhun9901/deep-learning-from-scratch)
The core ideas of modern deep learning, built from nothing, one stage at a time (following Karpathy's *Zero to Hero*).
- A scalar **autograd engine**, the same idea that powers PyTorch's backprop, with a computation graph rendered by the engine itself
- **makemore**: character-level language models (bigram → MLP → six-layer BatchNorm network), working toward a small GPT
- Every stage is a self-contained notebook with a written explanation of *why* it works

`Python` · `PyTorch` · `zero-dependency autograd`

### 🎙️ [JARVIS](https://github.com/midhun9901/jarvis)
A local, always-on voice assistant I use daily.
- FastAPI + WebSockets backend, React voice UI, multi-LLM routing with provider fallback
- Persistent memory with background agents, Gmail/Calendar tools behind a spoken confirmation gate

`Python` · `FastAPI` · `React` · `WebSockets`

## 🛠️ Tech I work with

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)

Computer vision · metric learning · FAISS · deep learning from scratch · HPC / SLURM

## 📫 Reach me

- 🌐 Portfolio: [midhun9901.github.io/portfolio](https://midhun9901.github.io/portfolio/)
- 📧 midhun.somanunnithan@fau.de
