#  AI Bank Statement Automation with LLM & RAG

![Python](https://img.shields.io/badge/Python-3776AB?logo=python\&logoColor=white)
![LLM](https://img.shields.io/badge/LLM-4B0082)
![LangChain](https://img.shields.io/badge/LangChain-2E8B57)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?logo=streamlit\&logoColor=white)
![YOLO](https://img.shields.io/badge/YOLO-00FFFF)
![OCR](https://img.shields.io/badge/OCR-Tesseract-4285F4)


##  Overview

This project automates **bank statement analysis** using **LLMs and Retrieval-Augmented Generation (RAG)**.
It converts unstructured bank statement PDFs into structured data and allows users to query income and expenses using **natural language**.


##  Use Case

* Extract income & expenses from PDF bank statements
* Analyze monthly and yearly financial trends
* Store records in databases
* Ask questions like *“How much did I spend last month?”*


##  How It Works

1. **Document Processing**

   * OCR + Computer Vision for complex PDF layouts
   * Custom YOLO model for document layout detection
   * Tables and text extraction

2. **RAG Pipeline**

   * Embedding models + Vector Database
   * Semantic retrieval using LangChain

3. **LLM Interface**

   * Open-source LLMs (LLaMA, Gemma)
   * Natural language financial queries

##  Tech Stack

* Python
* OCR (Tesseract)
* YOLO (Document Layout Detection)
* LangChain
* Open-source LLMs
* Vector Database
* SQL Database
* Streamlit

🔗 Related YOLO Project:
https://medium.com/@theeagleofwallstreet/ai-bank-statement-automation-with-llms-and-rag-6ecfb3bab4c4?postPublishedType=repub

##  Installation

```bash
git clone https://github.com/Theeagleofwallstreet/AI_bank_statements_automation_with_LLM-RAG.git
cd AI_bank_statements_automation_with_LLM-RAG
pip install -r requirements.txt
```

Create `.env` file:

```env
GOOGLE_API_KEY=your_api_key
```

For Linux OCR:

```bash
bash install-pytesseract-for-linux.sh
```

---

##  Run

**Development**
```bash
cd src/dev/

**App**

```bash
streamlit run apps.py


##  Links

* **GitHub Repo**
  [https://github.com/Theeagleofwallstreet/AI_bank_statements_automation_with_LLM-RAG.git](https://github.com/Theeagleofwallstreet/AI_bank_statements_automation_with_LLM-RAG.git)

* **AI Documents**
  [https://drive.google.com/drive/folders/1LSox2EQOCea4J5hXMEg8SnOp3ENej0Iu](https://drive.google.com/drive/folders/1LSox2EQOCea4J5hXMEg8SnOp3ENej0Iu)


##  Future Work

* Expense categorization
* Multi-bank support
* Dashboard analytics
* API integration
