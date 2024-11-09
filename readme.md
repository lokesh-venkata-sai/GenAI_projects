## GenAI_Projects

## Tech Stack:
- Python
- LangChain
- LangSmith - for LLM tracking purpose
- Streamlit
- Groq
- LangServe --> To create Rest APIs (integrated with Fast API)

## Prerequisites
- Setup Open AI account and load some money from https://platform.openai.com/
- Setup Langchain account and create API key from https://www.langchain.com/
- Setup Hugginface account and create access key from https://huggingface.co/
- Download and install Ollama from https://ollama.com/
- Setup groq API keys from https://console.groq.com/playground

## Projects
- `1-Chatbot_with_openAI`: Streamlit Chatbot using Open AI API
- `2-Chatbot_with_Ollama`: Streamlit Chatbot using Ollama


### Some Commands used
- Create Python Virtual Environment
    ```sh
    python -m venv venv
    ```
- To activate Virtual Environment
    ```sh
    .\venv\Scripts\activate
    ```
- Install required packages
    ```sh
    pip install -r requirements.txt
    ```
- To run streamlit application
    ```sh
    streamlit run app.py --server.port 8502
    ```