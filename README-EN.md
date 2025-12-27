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

# Media:
<img width="700" height="767" src="https://github.com/user-attachments/assets/c2638310-f830-4ce0-8bea-6de8c7180fe4" alt="Imagem ilustrativa de um print da tela inicial da aplicação. Nesse anexo, mostra-se a tela inicial, com as configurações CRUD de gerenciamento de currículo na esquerda do paínel, e centralizado seções a preencher, com sindronização á pré-visualização do currículo no lado direito. Possibilitando feedback e acompanhamento em tempo real."/>
<img width="700" height="767" alt="A three-column web application interface for a Cover Letter Builder with a dark theme sidebar on the left showing language and layout settings, a central section with form fields for recipient and opening details, and a document preview on the right displaying a resume header and a code block with raw HTML tags at the bottom." src="https://github.com/user-attachments/assets/eeb95ea2-530b-4a4a-8f4c-1f37f90867d0" />
<img width="700" height="767" alt="A web application interface for a Proposal Builder following PMI and ABNT standards featuring a dark sidebar on the left with language and layout settings and a main form section with input fields for author, institution, project title, subtitle, city, year, and work theme." src="https://github.com/user-attachments/assets/f4f0b285-79a8-454d-b53e-222ceab33191" />
<img width="700" height="767" alt="A web application interface for a Report Builder following ABNT standards featuring a dark sidebar on the left with language and layout settings and a main form section with input fields for author, institution, report title, subtitle, city, year, and work theme." src="https://github.com/user-attachments/assets/c88a5e25-4a4e-4c03-8e89-a14699c27ac2" />

---
<div align="center">
  <p><i>Developed with a focus on high performance and employability by Éverson Filipe.</i></p>
  <p>(https://www.linkedin.com/in/eversonfilipe-agile-products-ai/)</p>
</div>
