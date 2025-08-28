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
├── app.py # Streamlit app for OpenAI GPT models
├── main.py # Streamlit app for Mistral (open-source model)
├── requirements.txt # Python dependencies
├── .env # API keys (gitignored)
└── README.md # This file

---

##  How to Use This Project

### Option 1: Run Locally (Clone & Setup)

1. Clone the repo:
   ```bash
   git clone https://github.com/SnehalSolawala/End-to-End-AI-Chatbot-with-LangChain-openAI-Mistral-.git
   cd End-to-End-AI-Chatbot-with-LangChain-openAI-Mistral-
2. Create and activate a virtual environment:
   python -m venv venv
# On Mac/Linux
source venv/bin/activate
# On Windows (PowerShell)
venv\Scripts\Activate.ps1

3. Install dependencies:
   pip install -r requirements.txt

4. Run the app:
   For OpenAI GPT models:
   ---streamlit run app.py

   For Mistral (no API key needed):    //Ensure you locally download the mistral model from ollama, so first install ollama and then run cmd "ollama run mistral" it will locally download the entire mistral model in your sytem,
                                       //so when we run the code it direct go to the local mistral model for now, also we can use groq api if we don't wamt to download the entire model locally.
   ---streamlit run main.py



