# VersaMind - Smart Document Summarizer & Email Drafter

VersaMind is a lightweight, intelligent AI tool designed to streamline business communication by efficiently summarizing lengthy documents and drafting professional emails. Built on the Microsoft Phi-3 Mini 4K Instruct model and leveraging key NLP techniques, VersaMind simplifies document analysis and accelerates workflows.

---

### 🚀 Features

*   **Multi-Format Support**: Handles documents in `.pdf`, `.docx`, and `.txt` formats.
*   **Intelligent Summarization**: Extracts, cleans, and chunks document content to provide accurate, context-aware summaries using the Phi-3 Mini LLM.
*   **Configurable Tone**: The email drafting feature can be customized for different tones (Formal, Friendly, Professional, Casual).
*   **Lightweight & Efficient**: Optimized for local execution with 4-bit quantization.

---

### 🛠️ Tech Stack

| Category | Tools & Libraries |
| :--- | :--- |
| **Language** | Python 3.10+ |
| **LLM** | Microsoft Phi-3 Mini 4K Instruct |
| **ML Framework** | PyTorch, Transformers, BitsAndBytes |
| **Interface** | Gradio |
| **File Parsing** | PyMuPDF, python-docx |

---

### 📂 Project Structure

```
Versamind-main/
├── notebooks/
│   └── VersaMind.ipynb      # Original Jupyter Notebook for experimentation
├── versamind.py             # Main executable Python script
├── requirements.txt         # Python dependencies
└── README.md                # Project documentation
```

---

### 💻 Installation & Usage

#### 1. Prerequisites
*   Python 3.10 or higher installed.
*   **GPU Recommended**: This project uses 4-bit quantization which requires a CUDA-capable GPU for optimal performance. It may not run correctly on CPU-only machines.

#### 2. Install Dependencies
```bash
pip install -r requirements.txt
```
*Note: You may need to install PyTorch manually ensuring it matches your CUDA version if the default install fails to detect your GPU.*

#### 3. Run the Application
```bash
python versamind.py
```
This will launch a local Gradio interface (usually at `http://127.0.0.1:7860`).

---

### 🧾 How It Works

1.  **Document Input**: Upload a .pdf, .docx, or .txt file via the UI.
2.  **Parsing & Cleaning**: Content is extracted and cleaned (typo correction, formatting).
3.  **Summarization**: The content is chunked and processed by Phi-3 to generate a concise summary.
4.  **Email Drafting**: Enter a topic and select a tone to generate a professional email draft.

---


## 🤝 Contributions
Contributions are welcome!
1. Fork the repository.
2. Create a feature branch.
3. Commit your changes.
4. Submit a pull request.

## Author

**Yeshwanth Goud**

*Data Scientist | Full Stack & ML Enthusiast*

