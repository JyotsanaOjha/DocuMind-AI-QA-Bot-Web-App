This project is a Retrieval-Augmented Generation (RAG) web application designed to turn static PDF documents into interactive knowledge bases. 
It allows users to upload a file and ask natural language questions, which the system answers by "reading" the document in real-time.

The application is built using a modern AI stack that includes:
•	Backend Framework: LangChain for orchestrating the document loading, text splitting, and retrieval chain.
•	Large Language Model (LLM): Powered by IBM Watsonx.ai (specifically using the granite-3-2-8b-instruct model).
•	Vector Database: ChromaDB is used to store and search through document embeddings created by the slate-125m-english model.
•	Frontend: A clean, functional user interface built with Gradio, enabling drag-and-drop PDF uploads and a chat-like query box.
