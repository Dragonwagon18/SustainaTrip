# Sustainatrip 🌿✈️  
*AI-Powered Sustainable Travel Recommendations for Southeast Asia*

Sustainatrip is an intelligent travel assistant designed to help users explore Southeast Asia responsibly. Leveraging cutting-edge AI, it recommends eco-friendly destinations, experiences, and accommodations, all through an intuitive chat-based interface.

## 🌍 What It Does

Sustainatrip provides users with personalized and sustainable travel suggestions based on natural language queries. Ask it questions like:

> *“What are eco-friendly things to do in Bali?”*

And receive curated answers that emphasize:

- Green accommodations  
- Ethical and cultural experiences  
- Low-impact transport  
- Community-based tourism options  

## 🧠 Core Features

- **Document-Based Knowledge**: Uses WikiVoyage and other travel documents as the knowledge base.
- **Hybrid Retrieval-Augmented Generation (RAG)**: Combines text search with vector similarity to find the most relevant content before generating a response.
- **Sustainability-Driven Prompts**: Special care is taken to ensure responses promote responsible tourism.
- **Interactive UI**: Built with Streamlit for easy use and real-time feedback collection.

## ⚙️ Technologies Used

- **PDF to Markdown Conversion**: Via `marker` for processing travel guides  
- **Document Chunking & Metadata Tagging**: Uses recursive text splitters to preserve context  
- **Vector Database**: Built on `PostgreSQL` with `PGVector` for hybrid search  
- **Embeddings**: HuggingFace model `BAAI/bge-large-en-v1.5` for semantic understanding  
- **LLM Integration**: OpenAI’s GPT models for generating thoughtful, contextual answers  
- **Frontend**: Streamlit app for clean UX and live feedback  
- **Evaluation Tools**: Ground-truth generation and retrieval performance measurement (MRR, Hit Rate)

## 🔁 Typical Workflow

1. **Initialization**:
   - Processes PDF documents into searchable chunks
   - Embeds content into vector DB using HuggingFace models

2. **User Query**:
   - Retrieves relevant travel information from indexed documents
   - Uses GPT model to generate an eco-conscious response

3. **Evaluation**:
   - Runs experiments on different RAG configurations
   - Compares embedding models and retrieval strategies

## 🚀 Future Plans

- Expand beyond WikiVoyage content  
- Add user profiles for personalized recommendations  
- Include real-time data (e.g., flight emissions, availability)  
- Support multi-language queries  
- Improve sustainability feedback loop

---

Sustainatrip is a step toward smarter, more conscious tourism – powered by AI, grounded in sustainability.
