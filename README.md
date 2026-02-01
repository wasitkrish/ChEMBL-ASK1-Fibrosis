<!-- Banner Header -->

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:11998e,100:38ef7d&height=220&section=header&text=ChEMBL%20ASK1%20Fibrosis%20Dataset&fontSize=36&fontColor=ffffff&animation=fadeIn" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Data-ChEMBL-orange.svg?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Domain-Cheminformatics-green.svg?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Task-Drug%20Discovery-blue.svg?style=for-the-badge" />
  <img src="https://img.shields.io/badge/License-CC%20BY%204.0-purple.svg?style=for-the-badge" />
</p>

<p align="center">
  <b>Reproducible ChEMBL-based ASK1 (MAP3K5) bioactivity dataset for fibrosis-focused drug discovery and machine learning</b>
</p>

---

# 🧪 ChEMBL ASK1 Fibrosis Dataset

This repository provides a **fully reproducible pipeline** for extracting, cleaning, and curating bioactivity data from **ChEMBL** targeting **ASK1 (MAP3K5)** — a kinase strongly associated with **fibrotic diseases**.

The final dataset is **ML-ready** and suitable for **QSAR modeling, cheminformatics, and AI-driven drug discovery**.

🤗 **Hugging Face Dataset:**  
👉 https://huggingface.co/datasets/<your-username>/chembl-ask1-fibrosis

---

## 🧬 Background

**ASK1 (Apoptosis Signal-Regulating Kinase 1 / MAP3K5)** is a stress-activated kinase involved in:
- Liver fibrosis
- Pulmonary fibrosis
- Renal fibrosis
- Inflammatory and oxidative stress signaling pathways

Because of its central role in fibrosis progression, ASK1 has emerged as an important **therapeutic target**, making curated bioactivity datasets valuable for computational drug discovery.

---

## 🛠️ What This Repository Contains

- 📓 Reproducible Jupyter notebook for ChEMBL data extraction
- 🧹 Data filtering, normalization, and cleaning steps
- 🧪 Curated ASK1 inhibitor bioactivity dataset
- 🤖 Machine-learning–ready structured data
- 🔗 Seamless integration with Hugging Face Datasets

---

## 📌 Tech Stack

- **Language:** Python  
- **Data Source:** ChEMBL  
- **Libraries:** pandas, numpy, chembl-webresource-client  
- **Data Format:** CSV / Parquet  
- **ML Integration:** Hugging Face Datasets  

---

## 📁 Project Structure

```
chembl-ask1-fibrosis/
│
├── notebooks/
│   └── ASK1_dataset.ipynb     # ChEMBL extraction & processing pipeline
│
├── data/
│   └── ASK1_dataset.csv       # Final curated dataset
│
├── requirements.txt           # Python dependencies
├── LICENSE
└── README.md                  # Project documentation
```

---

## 🚀 Getting Started

### Prerequisites
- Python 3.9+
- pip or conda
- Jupyter Notebook

### Installation

1. Clone the repository:
```bash
git clone https://github.com/<your-username>/chembl-ask1-fibrosis.git
cd chembl-ask1-fibrosis
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run the notebook:
```bash
jupyter notebook notebooks/ASK1_dataset.ipynb
```

---

## 🤗 Using the Dataset via Hugging Face

```python
from datasets import load_dataset

dataset = load_dataset("<your-username>/chembl-ask1-fibrosis")
print(dataset)
```

---

## 🔍 Potential Machine Learning Tasks

- 📈 Bioactivity regression (IC50 / Ki prediction)
- 🧪 Active vs inactive compound classification
- 🧬 SMILES-based deep learning models
- 🧠 Classical QSAR modeling
- 🔗 Graph Neural Networks (future extension)

---

## 📊 Suggested Dataset Extensions

- Molecular descriptor calculation (RDKit)
- Scaffold-based splitting
- External validation datasets
- Multi-task learning across related kinases

---

## 📄 License

- **ChEMBL Data License:** Creative Commons Attribution 4.0 (CC BY 4.0)
- **This Repository:** CC BY 4.0

You are free to use, modify, and redistribute this work **with proper attribution**.

---

## 🤝 Contributing

Contributions are welcome!  
Feel free to open an issue or submit a pull request.

---

## 📫 Contact

**Krish Singh**  
GitHub: https://github.com/wasitkrish

---

## ⚠️ Disclaimer

This dataset is intended **for research and educational purposes only**.  
It does **not** constitute medical, pharmaceutical, or clinical advice.
