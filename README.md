# 📚 Book Quest – Your Smart PDF Companion

**Book Quest** is an AI-integrated conversational tool that makes working with PDF documents interactive and intuitive. With this app, users can upload any PDF, ask natural language questions, and receive accurate, AI-generated answers alongside visually highlighted responses within the document.

---

## ✨ Core Features

- 📂 **PDF Upload Support** – Easily upload any PDF document for content exploration.  
- 🤖 **AI-Driven Question Answering** – Powered by OpenAI's GPT models to extract meaningful answers from documents.  
- 🖼 **Visual PDF Display** – Shows the page with the answer, including highlighted sections for better clarity.  
- 💬 **Interactive Chat UI** – Talk to your PDF like a chatbot—real-time Q&A right on screen.  
- 🔐 **OpenAI API Integration** – Requires a valid OpenAI key for processing.  
- 🧹 **Chat Reset Option** – Clear previous questions and start fresh anytime.

---

## 🛠 Tech Stack & Libraries

- **Frontend & Interface**:  
  - `gradio` – For building a clean, user-friendly UI  
  - Custom `CSS` – Enhances the visual layout

- **Backend & Logic**:  
  - `langchain` – For managing AI conversations and document context  
  - `PyPDFLoader` – Efficient PDF parsing and content extraction  
  - `Chroma` – Enables embedding and semantic search  
  - `fitz (PyMuPDF)` – Renders pages into images  
  - `Pillow` – Used to draw highlights and manipulate images

- **AI Engine**:  
  - **OpenAI GPT Models** – Generates intelligent responses based on PDF content

---

## ⚙️ Getting Started

### 🔁 Clone the Repository
```bash
git clone <your-repo-url>
cd book-quest
```

### 📦 Install Requirements
Ensure Python 3.8+ is installed, then install the dependencies:
```bash
pip install -r requirements.txt
```

### 🔑 Add Your OpenAI API Key
Sign up at [OpenAI](https://openai.com/) and get your API key.

### 🖌 Optional UI Customization
Place the `gradio.css` file in the project directory for customized styling.

### 🚀 Run the App
```bash
python app.py
```

### 🌐 Access Locally
Open `http://127.0.0.1:7860` in your browser.  
Use `share=True` in the `launch()` method if you want to share access with others.

---

## 🧭 How It Works

1. **Input your OpenAI API key** in the provided field.  
2. **Upload a PDF file** through the interface.  
3. **Ask any question** related to the document content.  
4. **Get an answer** along with the corresponding page image and highlighted text.  
5. **Clear the conversation** to reset and ask new questions.

---

## 📁 Project Directory

```
📂 book-quest/
├── app.py             # Core logic and app configuration
├── requirements.txt   # List of dependencies
├── gradio.css         # Optional: UI styling file
├── logo.jpg           # App branding image
└── README.md          # Project documentation
```

---

## 🔮 Upcoming Features

- 🔦 Inline text highlighting directly on page image  
- 📁 Multi-file support for handling more than one document at a time  
- 🔍 Smart filters (by keyword, date, metadata)  
- 🌐 Multilingual query support  
- 🔐 Secure user login and API key storage

---

## 🤝 Contribute

We’re open to improvements and feature ideas!  
Feel free to fork, raise issues, or submit pull requests to help enhance Book Quest.

---

## 🌍 Live Application

Experience the tool in action:  
👉 [Try Book Quest Now](https://book-quest-6c2f.onrender.com/)

---

## 👩‍💻 Team & Contributors

- Vaishnavi Sanjay Mane  
- Durva Darshan Desai  
- Disha Hemant Joshi  
- Purva Deepak Agine
