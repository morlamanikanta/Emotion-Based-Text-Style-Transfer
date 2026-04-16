# Emotion-Based-Text-Style-Transfer

A powerful **AI-driven tone transformation web application** built using **Gradio** and **OpenRouter API**.  
This tool allows users to **rewrite text in different tones and languages**, while preserving structure from files like **PDF, DOCX, and TXT**.

---

## 🚀 Features

- 🌍 **Multilingual Support**
  - Supports 100+ languages including Telugu, Hindi, Tamil, Arabic, Chinese, etc.

- 🎭 **Advanced Tone Engine**
  - 60+ tones (happy, sad, motivational, poetic, formal, angry, etc.)
  - Intelligent tone mapping with synonym support

- 📄 **File Upload Support**
  - Upload and process:
    - PDF
    - DOCX
    - TXT
  - Maintains **document structure (headings, paragraphs)**

- 🧠 **Language-Aware Tone Generation**
  - Custom vocabulary injection per language
  - Script detection (Indic, Arabic, CJK, Cyrillic, etc.)

- ⚡ **Efficient Chunk Processing**
  - Smart chunking for large documents
  - Batch API processing with retry mechanism

- ⏱️ **Rate Limit Tracking UI**
  - Per-minute and daily usage tracking
  - Visual indicators with progress bars

- 🎨 **Modern UI**
  - Clean, responsive Gradio interface
  - Custom CSS styling for better UX

---

## 🛠️ Tech Stack

- **Frontend/UI**: Gradio  
- **Backend**: Python  
- **API**: OpenRouter AI  

---

## 📂 Project Structure

.
├── openrouter_web_tonegenerator.py
├── requirements.txt
├── .env
└── README.md

---

## ⚙️ Installation

### 1. Clone the Repository
git clone https://github.com/your-username/tone-generator.git
cd tone-generator

### 2. Create Virtual Environment
python -m venv venv

### 3. Activate Environment

Windows:
venv\Scripts\activate

Mac/Linux:
source venv/bin/activate

### 4. Install Dependencies
pip install -r requirements.txt

---

## 🔑 Environment Setup

Create a `.env` file in the root directory:

OPENROUTER_API_KEY=your_api_key_here

---

## ▶️ Run the Application

python openrouter_web_tonegenerator.py

Then open:
http://127.0.0.1:7860

---

## 📌 Usage

1. Enter text or upload a file (PDF/DOCX/TXT)
2. Select input language, output language, and tone
3. Click Generate
4. Copy or download output

---

## ⚠️ Limitations

- API rate limits apply
- Large files may take longer
- Output depends on model quality

---

## 🔮 Future Improvements

🎚️ Emotion Intensity Control
💬 Real-time Chat Integration
🎤 Voice-based Emotion Conversion
🧠 Advanced Emotion Detection using Deep Learning
📊 Dataset Expansion for Better Accuracy
🤖 Integration with Chatbots & Virtual Assistants

## 👨‍💻 Author

- P.Mounika(Y22ACS540)
- P.Divya(L23ACS611)
- N.Venkata Manideep(Y22ACS515)
- M.Manikanta(Y22ACS508)
