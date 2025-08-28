#Q&A Chatbot with OpenAI, LangChain, and Streamlit

An end-to-end interactive chatbot powered by [OpenAI](https://platform.openai.com/), [Mistral](Opensource: https://ollama.com/library/mistral), [LangChain](https://www.langchain.com/), and [Streamlit](https://streamlit.io/).  
This app allows users to ask any question, and the chatbot generates intelligent responses using GPT models.  

---

## Features
- AI-powered Q&A with OpenAI GPT models (`gpt-4o`, `gpt-4-turbo`, `gpt-4`)  and Mistral Opensouce Ollama model.
- LangChain integration for prompt templates and structured pipelines  
- Adjustable temperature and max tokens from the sidebar  
- Secure API key input through sidebar for use GPT model and no api require for use Mistral model because it is opensouce model.
- LangSmith tracing enabled for debugging and monitoring  
- Streamlit UIfor easy interaction  

---

## Tech Stack
- Python 3.9+
- [Streamlit](https://streamlit.io/) – User interface  
- [LangChain](https://www.langchain.com/) – LLM orchestration  
- [OpenAI](https://platform.openai.com/) – GPT models
- [Mistral]( https://ollama.com/library/mistral) - Mistral model
- [python-dotenv](https://pypi.org/project/python-dotenv/) – Environment variable management  

---

## Project Structure
.
├── app.py # Main Streamlit app for OpenAI GPT model
├── main.py # Main Streamlit app for Mistral model ( Opensource LLM)
├── requirements.txt # Project dependencies
├── .env # Store your API keys (not committed to Git)
└── README.md # Project documentation

