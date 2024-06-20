#  **Project Name**        - News-Research-Tool
##### **Domain**              - Finance
##### **Project Type**        - 
##### **Contribution**        - Individual
##### **Tools used**          - 

  - LangChain
  - embedding vector using OpenAI
  - FAISS
  - Streamlit application : 


<!-- PROJECT DESCRIPTION -->
# Project description
To built a Bot, easy-to-use news search tool, that makes it simple to retrieve information. To get pertinent insights from the financial and stock market domains. Users can enter the URLs of the articles and can ask queries.

# Features
  - Load URLs or upload text files containing URLs to fetch article content.
  - Process article content through LangChain's UnstructuredURL Loader
  - Construct an embedding vector using OpenAI's embeddings and leverage FAISS, a powerful similarity search library, to enable swift and effective retrieval of relevant information
  - Interact with the LLM's (Chatgpt) by inputting queries and receiving answers along with source URLs.

# Project Structure
  - main.py: The main Streamlit application script.
  - vectorEmbedding.pkl: A pickle file to store the FAISS index.
  - .env: Configuration file for storing your OpenAI API key.

