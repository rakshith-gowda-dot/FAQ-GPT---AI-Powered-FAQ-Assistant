# FAQ-GPT---AI-Powered-FAQ-Assistant
An AI-powered question-answering system that provides instant, intelligent responses to course-related FAQs using advanced natural language processing and semantic search capabilities.

---

# 🌟 Demo
[![Live Demo](https://img.shields.io/badge/🚀-Live_Demo-blue)](your_demo_link_here)  
*Insert GIF/video showing the app in action*

---

# 📦 Installation

## 1. Clone the repository
```bash
git clone https://github.com/your-username/[project-name].git
cd [project-name]
2. Create virtual environment
bash
Copy
Edit
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
3. Install dependencies
bash
Copy
Edit
pip install -r requirements.txt
4. Set up environment variables
bash
Copy
Edit
echo "GOOGLE_API_KEY=your_google_api_key_here" > .env
5. Run the application
bash
Copy
Edit
streamlit run main.py
🎯 Usage
Create Knowledge Base: Click "Create Knowledgebase" to process your FAQ CSV

Ask Questions: Type your question in the input field

Get Answers: Receive AI-powered, context-aware responses instantly

🛠️ Tech Stack
Framework: Streamlit

AI/ML: LangChain, Google Palm API

Vector Database: FAISS

Embeddings: HuggingFace Instructor Embeddings

Data Processing: CSV Loader

Environment: Python, dotenv

🏗️ Architecture
📁 Project Structure
bash
Copy
Edit
│
├── 📄 main.py              # Streamlit web application
├── 📄 langchain_helper.py  # Core AI functionality
├── 📄 codebasics_faqs.csv  # FAQ dataset
├── 📄 requirements.txt     # Dependencies
└── 📄 .env                 # Environment variables
🔧 Configuration
Environment Variables
GOOGLE_API_KEY: Your Google Palm API key

CSV Format
Your FAQ CSV should contain:

prompt: The question

response: The corresponding answer

🚀 Features
✅ Natural Language Understanding
✅ Semantic Similarity Search
✅ Real-time Processing
✅ Easy CSV Integration
✅ Beautiful Web Interface
✅ Error Handling & Validation
