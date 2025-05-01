# ai_chatbot_ManasPatni

**Project Overview**
This project implements an AI chatbot interface based on the personality of Manas Patni. The chatbot leverages advanced natural language processing (NLP) techniques to interact with users, providing responses based on pre-trained language models and a knowledge base.

**Features**

1.Interactive Chat Interface: Users can interact with the AI chatbot by entering text queries.
2.Chat History Display: Session-based chat history is displayed to users, showing both user inputs and AI responses.
3.AI Personality: The chatbot's responses are tailored to emulate the personality traits associated with Manas Patni.
4.Integration with External Databases: Utilizes ChromaDB for storing and querying vector representations of chatbot interactions.

**Setup Instructions**

-> Prerequisites
        1.Python 3.6+
        2.pip (Python package installer)

**Installation**

**1.Clone the repository:**
git clone [https://github.com/your/repository.git](https://github.com/ManasPatni/ai_chatbot_ManasPatni)
cd repository

**2.Install dependencies from requirements.txt:**
pip install -r requirements.txt

**Running the Application**
streamlit run app.py

**Chosen Chunking Method**
The project utilizes the LangChain library for its chunking method, which segments input text into meaningful chunks or segments. This facilitates better understanding and processing of user queries by the AI chatbot.

**Embedding Model**
The embedding model chosen for this project is sentence-transformers/all-MiniLM-L6-v2. 
This model is used to convert text inputs into dense vector representations, which are essential for comparing and understanding semantic similarity between user queries and stored knowledge.

**Vector Database (ChromaDB)**
ChromaDB is integrated as the vector database for storing and retrieving vector representations of chatbot interactions. It provides a persistent storage solution that supports efficient querying based on vector similarities.



