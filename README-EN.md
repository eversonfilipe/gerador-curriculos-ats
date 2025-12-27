# 📄 Resume & Technical Document Generator (ATS-Friendly)

![Python](https://img.shields.io/badge/python-3.8+-blue.svg)
![Streamlit](https://img.shields.io/badge/streamlit-1.x-FF4B4B.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Status](https://img.shields.io/badge/status-active-brightgreen.svg)

Developed by **Éverson Filipe**, this software is a robust micro-system built with Python and Streamlit. It was designed to go beyond a simple form, acting as a compliance tool for Applicant Tracking System (ATS) algorithms and rigorous academic standards.

## 🎯 Value Proposition

The system generates documents fully compliant and optimized for reading by **SEO** algorithms, **LLMO** (Large Language Model Optimization), and principally, **ATS** (Applicant Tracking Systems). Beyond career tools, it allows the creation of prototypes for articles and technical reports optimized for **ABNT** standards.

## 🚀 Key Features

### 1. Resume & Cover Letter Builder
* **Algorithmic Optimization:** Clean structures in standard fonts (Times New Roman/Helvetica) to ensure maximum readability by recruitment bots.
* **Multi-format Export:** Native support for generating **PDF** (via ReportLab) and **DOCX** (via python-docx) files.
* **Density Adjustment:** Fine control of the layout (Comfortable, Normal, Compact, and Super Compact) to optimize space without compromising design.

### 2. ATS Reading Simulator
* **Audit Algorithm:** Module that simulates an ATS robot's vision, extracting raw text and automatically identifying sections via heuristic patterns.
* **Readability Scoring:** Generates a compatibility score based on the presence of essential sections and formatting integrity.

### 3. ABNT/PMI Document Generator
* **Commercial Proposals:** Structure based on PMI/ABNT standards, including Timeline and Budget.
* **Technical Reports:** Generation of documents with Cover, Title Page, automatic Table of Contents, and Annex section for images.

### 4. Internationalization (I18n)
* Interface and documents fully translatable, with native support for **Portuguese (PT)** and **English (EN)**.

## 🛠️ Architecture and Tech Stack

The project uses an architecture based on in-memory buffer processing to ensure performance and data security:

* **Language:** Python 3.x
* **Interface:** Streamlit
* **PDF Engine:** ReportLab (Document generation via coordinates and Flowables)
* **Word Engine:** Python-Docx
* **Data Analysis:** PyPDF / PyPDF2 (Text extraction and analysis)

## 💻 How to Run

To run the project locally, follow the steps below:

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/seu-usuario/gerador-curriculos-ats.git](https://github.com/seu-usuario/gerador-curriculos-ats.git)
   cd gerador-curriculos-ats
   ```

2. **Create and activate a virtual environment:**
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # On Windows: .venv\Scripts\activate
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements/requirements.txt
   ```

4. **Start the application:**
   ```bash
   streamlit run app.py
   ```

---
<div align="center">
  <p><i>Developed with a focus on high performance and employability by Éverson Filipe.</i></p>
  <p>(https://www.linkedin.com/in/eversonfilipe-agile-products-ai/)</p>
</div>
