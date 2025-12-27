# 📄 Gerador de Currículos & Documentos Técnicos (ATS-Friendly)

![Python](https://img.shields.io/badge/python-3.8+-blue.svg)
![Streamlit](https://img.shields.io/badge/streamlit-1.x-FF4B4B.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Status](https://img.shields.io/badge/status-active-brightgreen.svg)

Desenvolvido por **Éverson Filipe**, este software é um micro-sistema robusto construído com Python e Streamlit. Ele foi projetado para ir além de um simples formulário, atuando como uma ferramenta de conformidade para algoritmos de busca de emprego (ATS) e padrões acadêmicos rigorosos.

## 🎯 Proposta de Valor

O sistema gera documentos totalmente compatíveis e otimizados para leitura por algoritmos de **SEO**, **LLMO** (Large Language Model Optimization) e, principalmente, sistemas **ATS** (Applicant Tracking Systems). Além da carreira, a ferramenta permite a criação de protótipos de artigos e relatórios técnicos otimizados para as normas **ABNT**.

## 🚀 Principais Funcionalidades

### 1. Construção de Currículos e Cover Letters
* **Otimização Algorítmica:** Estruturas limpas em fontes padrão (Times New Roman/Helvetica) para garantir máxima legibilidade por robôs de recrutamento.
* **Exportação Multiformato:** Suporte nativo para geração de arquivos **PDF** (via ReportLab) e **DOCX** (via python-docx).
* **Ajuste de Densidade:** Controle fino do layout (Confortável, Normal, Compacto e Super Compacto) para otimizar o espaço sem comprometer o design.

### 2. Simulador de Leitura ATS
* **Algoritmo de Auditoria:** Módulo que simula a visão de um robô ATS, extraindo texto bruto e identificando seções automaticamente via padrões heurísticos.
* **Scoring de Legibilidade:** Gera uma pontuação de compatibilidade baseada na presença de seções essenciais e integridade da formatação.

### 3. Gerador de Documentos ABNT/PMI
* **Propostas Comerciais:** Estrutura baseada em padrões PMI/ABNT, incluindo Cronograma (Timeline) e Orçamento (Budget).
* **Relatórios Técnicos:** Geração de documentos com Capa, Folha de Rosto, Sumário automático e seção de Anexos para imagens.

### 4. Internacionalização (I18n)
* Interface e documentos totalmente traduzíveis, com suporte nativo para **Português (PT)** e **Inglês (EN)**.

## 🛠️ Arquitetura e Tech Stack

O projeto utiliza uma arquitetura baseada em processamento de buffers em memória para garantir performance e segurança dos dados:

* **Linguagem:** Python 3.x
* **Interface:** Streamlit
* **Motor de PDF:** ReportLab (Geração de documentos via coordenadas e Flowables)
* **Motor Word:** Python-Docx
* **Análise de Dados:** PyPDF / PyPDF2 (Extração e análise de texto)

## 💻 Como Executar

Para rodar o projeto localmente, siga os passos abaixo:

1. **Clone o repositório:**
   ```bash
   git clone [https://github.com/seu-usuario/gerador-curriculos-ats.git](https://github.com/seu-usuario/gerador-curriculos-ats.git)
   cd gerador-curriculos-ats

2. **Crie e ative um ambiente virtual:**
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # No Windows: .venv\Scripts\activate

3. **Instale as dependências:**
   ```bash
   pip install -r requirements/requirements.txt

4. **Inicie a aplicação:**
   ```bash
   streamlit run app.py

# Mídia:
<img width="700" height="767" src="https://github.com/user-attachments/assets/c2638310-f830-4ce0-8bea-6de8c7180fe4" alt="Imagem ilustrativa de um print da tela inicial da aplicação. Nesse anexo, mostra-se a tela inicial, com as configurações CRUD de gerenciamento de currículo na esquerda do paínel, e centralizado seções a preencher, com sindronização á pré-visualização do currículo no lado direito. Possibilitando feedback e acompanhamento em tempo real."/>
<img width="700" height="767" alt="A three-column web application interface for a Cover Letter Builder with a dark theme sidebar on the left showing language and layout settings, a central section with form fields for recipient and opening details, and a document preview on the right displaying a resume header and a code block with raw HTML tags at the bottom." src="https://github.com/user-attachments/assets/eeb95ea2-530b-4a4a-8f4c-1f37f90867d0" />
<img width="700" height="767" alt="A web application interface for a Proposal Builder following PMI and ABNT standards featuring a dark sidebar on the left with language and layout settings and a main form section with input fields for author, institution, project title, subtitle, city, year, and work theme." src="https://github.com/user-attachments/assets/f4f0b285-79a8-454d-b53e-222ceab33191" />
<img width="700" height="767" alt="A web application interface for a Report Builder following ABNT standards featuring a dark sidebar on the left with language and layout settings and a main form section with input fields for author, institution, report title, subtitle, city, year, and work theme." src="https://github.com/user-attachments/assets/c88a5e25-4a4e-4c03-8e89-a14699c27ac2" />

---
<div align="center">
  <p><i>Desenvolvido com foco em alta performance e empregabilidade por Éverson Filipe.</i></p>
  <p>(https://www.linkedin.com/in/eversonfilipe-agile-products-ai/)</p>
</div>
