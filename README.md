# Me-Ai
A twin chatbot for all
Me.Ai is a personalized AI chatbot designed to reflect my personality, communication style, moods, interests, and knowledge base. It learns from structured inputs I provide, remembers past interactions, and engages in thoughtful, context-aware conversations.

The project combines LLM intelligence with a custom knowledge base, enabling responses that sound like me — both in tone and in substance.

🚀 Features
Personalized Identity – AI mirrors my own communication style, interests, and worldview.
Custom Knowledge Base – Stores my curated knowledge: Islamic teachings (Qur’an + Sahih Hadith), CS/Data Science concepts, photography, football, personal reflections, scientific insights, and more.
Persistent Memory – Each user’s sessions are stored in Firebase Firestore, allowing seamless continuation after logout.
Context Retrieval – Uses FAISS + Sentence Transformers to find relevant knowledge base entries.
Groq API Integration – Ultra-fast, high-quality responses using the Mixtral model.
Multi-Persona Support (v2.0) – Build different AI “twins” (Personal Me, Professional Me, etc.).
Document Uploads – PDF/DOCX ingestion to auto-fill the knowledge base.

🛠️ Tech Stack
Frontend: React.js
Backend: FastAPI (Python)
Database: Firebase Firestore
Embeddings: Hugging Face Sentence Transformers
Vector Search: FAISS
LLM API: Groq (Mixtral)
Authentication: Firebase Auth

📂 Project Structure

me.ai/
│
├── frontend/           # React-based UI
├── backend/            # FastAPI backend
├── profile.json        # Personality profile
├── knowledge_base.jsonl # Custom knowledge base
├── requirements.txt    # Python dependencies
└── README.md           # Project documentation

⚙️ Installation & Setup

Clone the repository

git clone https://github.com/your-username/me.ai.git
cd me.ai

Backend Setup

cd backend
pip install -r requirements.txt
Add your Groq API Key in .env

Configure Firebase credentials

Frontend Setup
cd frontend
npm install
npm start

📌 Roadmap
 Persona Editing UI – Adjust humor, formality, tone sliders.
 Offline Mode – Run locally without internet.
 Image Recognition – Respond to and analyze images.
 User KB Editing – Rich interface for managing knowledge base.
 Multi-Language Support.

🧠 Vision
“Me.Ai is not just a chatbot — it’s my digital twin, a living knowledge archive, and a conversational companion that thinks, speaks, and reasons like me.”

By combining personalization, long-term memory, and fast LLMs, Me.Ai aims to make AI feel truly human-aligned — unique to its creator.

