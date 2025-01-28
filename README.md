# AI-Powered Chatbot with Document Processing and Retrieval

## Problem Statement:
Develop an AI-powered chatbot that assists users by answering domain-specific queries using advanced NLP techniques. The chatbot should retrieve and summarize documents, provide sentiment insights, and highlight key entities in its responses.

## Objective:
Create a chatbot that retrieves relevant documents based on user queries, summarizes them, analyzes sentiment, and extracts key entities. The system uses Retrieval-Augmented Generation (RAG), a pre-trained language model (e.g., GPT), and several NLP techniques.

## Features:
- **Document Retrieval:** Uses a search backend (FAISS) to retrieve relevant documents based on user queries.
- **Summarization:** Summarizes retrieved documents for concise user responses.
- **Sentiment Analysis:** Provides sentiment insights (positive, negative, neutral) from retrieved documents.
- **Entity Extraction:** Extracts and highlights domain-specific entities (e.g., dates, organizations, etc.) in the chatbot’s responses.
- **Interaction Logging:** Logs all interactions for evaluation and analysis.

## Task Breakdown:
1. **Data Ingestion:** 
   - Use a domain-relevant dataset (e.g., customer complaints or FAQs).
   - Preprocess the dataset for clean and structured input.
2. **Chatbot Implementation:**
   - Retrieval-Augmented Generation (RAG) for fetching context.
   - Pre-trained language models (e.g., GPT) for generating responses.
3. **Core Functionalities:**
   - Search and Retrieval using FAISS.
   - Document Summarization using BART.
   - Sentiment Analysis using a pre-trained sentiment analysis pipeline.
   - Entity Extraction using spaCy.
4. **Interaction Logging:**
   - Log all queries, responses, sentiment, and extracted entities.
   - Analyze logs to identify trends and evaluate performance.
5. **Explainability:**
   - Provide explanations for responses, showing why specific documents were retrieved and sentiment assigned.

## Requirements:
To run this project, you need to install the following Python packages:

1. `sentence-transformers` for sentence embeddings.
2. `transformers` for NLP models (BART, sentiment-analysis).
3. `faiss-cpu` for document retrieval.
4. `spacy` for named entity recognition.
5. `pandas` for dataset handling.
6. `numpy` for numerical operations.

## How to Run:
1. Clone this repository:
   ```bash
   git clone https://github.com/Udit11/2025-Smart-Document-Assistant-for-Financial-Domain.git
   cd 2025-Smart-Document-Assistant-for-Financial-Domain

2. Install the dependencies:
   pip install -r requirements.txt

3. Run the chatbot:
   Run each section of the notebook 

4. Interact with the chatbot through the terminal, and type 'exit' to quit.

## Deliverables:
1. Functional chatbot that answers queries using document retrieval.
2. Summarizes documents, provides sentiment analysis, and highlights entities.
3. Interaction log and performance metrics (retrieval accuracy, sentiment F1-score).
4. Report detailing challenges and future improvements.

## Future Improvements:
1. Implementing advanced explainability features for response generation.
2. Using domain-specific models to improve sentiment analysis and entity recognition.
3. Integrating a user interface (UI) for better user interaction.

