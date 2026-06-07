# 🏥 MedAssist AI

MedAssist AI is an AI-powered post-discharge healthcare assistant designed to support patients during their recovery after hospital discharge. The system combines Large Language Models (LLMs), Retrieval Augmented Generation (RAG), and a multi-agent architecture to provide reliable medical guidance, answer healthcare-related queries, and improve patient engagement.

## 🚀 Features

* 🤖 AI-powered healthcare assistance
* 📚 Retrieval Augmented Generation (RAG)
* 👨‍⚕️ Multi-Agent Architecture (Receptionist & Clinical Agents)
* 🔍 Medical Knowledge Retrieval
* 🌐 Real-time Web Search Integration
* 💊 Medication & Follow-up Reminders
* 📊 Risk Assessment and Patient Monitoring
* 💬 Interactive Chat-Based Interface
* 🔒 Secure Patient Data Management

## 🏗️ System Architecture

The system follows a multi-agent workflow:

1. Patient submits a healthcare query.
2. Receptionist Agent receives and routes the request.
3. Clinical Agent analyzes medical queries.
4. RAG retrieves relevant information from the medical knowledge base.
5. OpenAI GPT generates context-aware responses.
6. The patient receives personalized guidance and recommendations.

## 🛠️ Technology Stack

### Frontend

* Streamlit

### Backend

* Python
* LangChain

### AI & Machine Learning

* OpenAI GPT
* Retrieval Augmented Generation (RAG)
* Sentence Transformers

### Database & Storage

* SQLite
* Pinecone Vector Database

### External Services

* Tavily Search API

### Development Tools

* Visual Studio Code
* GitHub
* Postman

## 📂 Project Structure

```bash
MedAssist-AI/
│
├── app.py
├── agents/
├── knowledge_base/
├── database/
├── embeddings/
├── utils/
├── requirements.txt
├── README.md
└── assets/
```

## ⚙️ Installation

1. Clone the repository

```bash
git clone https://github.com/your-username/MedAssist-AI.git
```

2. Navigate to the project directory

```bash
cd MedAssist-AI
```

3. Install dependencies

```bash
pip install -r requirements.txt
```

4. Configure environment variables

```bash
OPENAI_API_KEY=your_api_key
PINECONE_API_KEY=your_api_key
TAVILY_API_KEY=your_api_key
```

5. Run the application

```bash
streamlit run app.py
```

## 🎯 Objectives

* Improve post-discharge patient support.
* Provide reliable healthcare information.
* Encourage medication adherence.
* Assist patients with follow-up care.
* Enhance patient engagement through conversational AI.

## 🔮 Future Enhancements

* Integration with Electronic Health Records (EHR)
* Advanced Readmission Risk Prediction
* Voice-Based Healthcare Assistance
* Mobile Application Support
* Doctor and Caregiver Dashboard

## 👨‍💻 Author

Developed as a healthcare-focused AI project to improve patient recovery and post-discharge care through intelligent assistance and medical knowledge retrieval.
