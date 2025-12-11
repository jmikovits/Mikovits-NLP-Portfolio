# Mikovits-NLP-Portfolio
Welcome to my Natural Language Processing (NLP) Portfolio! This repository is a collection of NLP projects and examples of my work and in-class learning, showcasing my skills in **Retrieval-Augmented Generation (RAG)**, **AI Agent design**, **Large Language Models (LLMs)**, and **Streamlit** application development.

## Repository Structure

This portfolio is organized into folders based on their category. For example:

#### Weekly In-Class Coding Work [[Link to Folder](https://github.com/jmikovits/Mikovits-NLP-Portfolio/tree/main/NLP%20In-Class%20Coding%20Notebooks)]
A collection of notebooks showcasing various topics I've learned and applied in my NLP class, with demonstrated mastery through completed exercises.

#### NBA RAG Assistant [[Link to NBA RAG Repository](https://github.com/jmikovits/Mikovits-NLP-Portfolio/tree/main/Mikovits_LPP_Rag)]

---

## NBA RAG Assistant [[Link to NBA RAG Repository](https://github.com/jmikovits/Mikovits-NLP-Portfolio/tree/main/Mikovits_LPP_Rag)]

### Overview
In this project, I developed an advanced **Retrieval-Augmented Generation (RAG)** application that serves as an intelligent assistant for NBA knowledge. Unlike a standard chatbot, this agent references a curated vector database of NBA video transcripts, player statistics, and articles to provide fact-based answers.

Built using **Python**, **CrewAI**, **Streamlit**, **DuckDB**, and **OpenAI**, this app allows users to:

* **Ask complex questions** about the past two NBA seasons and receive sourced, accurate answers.
* **Interact with a customized AI Agent** that uses specific "persona" guidelines to maintain a professional and knowledgeable tone.
* **Visualize the sources** the AI used to generate its answer, ensuring transparency and trust.
* **Configure the Agent** dynamically via a sidebar, adjusting parameters like the number of search results (`top_k`) or the specific LLM model used.

### Project Significance
This project is a cornerstone of my NLP portfolio because it demonstrates the ability to build **end-to-end AI pipelines**. It goes beyond simple API calls by implementing a full RAG architecture, from data ingestion and chunking to vector storage and retrieval.

It highlights my proficiency in:

* **Vector Databases:** Managing and querying high-dimensional data using DuckDB.
* **Agentic workflows:** Using CrewAI to create agents that can use tools (like database search) to solve problems autonomously.
* **User Experience (UX) for AI:** Designing a clean, intuitive Streamlit interface that makes complex AI accessible to non-technical users.
* **Prompt Engineering:** Crafting robust system prompts and backstories to control Agent behavior and reduce hallucinations.

### Example Screenshot
<img width="1919" height="945" alt="image" src="https://github.com/user-attachments/assets/27418605-10c0-4a6b-921d-4af4ad03059a" />
