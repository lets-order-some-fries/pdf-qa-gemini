# 📖 PDF Q&A System using Google Gemini API

## 🚀 Overview
This project allows users to upload a PDF and ask questions based on its content. The system:
- Extracts text from the PDF 📄
- Splits text into meaningful chunks 🔍
- Stores embeddings using FAISS + Google Gemini 🔢
- Supports conversational memory for better answers 🧠
- Can summarize the document upon request ✨

## 📂 Project Structure
📁 pdf-qa-gemini │── 📄 main.ipynb # Jupyter Notebook with all code │── 📄 requirements.txt # Dependencies file │── 📄 README.md # Project documentation │── 📁 faiss_index/ # FAISS index storage │── 📁 examples/ # Sample PDFs


## 🔧 Installation
1. Clone this repository:
git clone https://github.com/lets_order_some_fries/pdf-qa-gemini.git

2. Navigate to the folder:
cd pdf-qa-gemini

3. Install dependencies:
pip install -r requirements.txt

## 🏃‍♂️ How to Run
1. Open `main.ipynb` in **Jupyter Notebook**.
2. Run the notebook step by step.
3. Upload a PDF file and ask questions interactively!

## 📜 Dependencies
- `PyMuPDF` for PDF text extraction
- `LangChain` for chunking and retrieval
- `FAISS` for vector search
- `Google Generative AI` for embeddings & question answering

## 📬 Contact
If you have any issues or suggestions, feel free to **open an issue** or reach out to me!
