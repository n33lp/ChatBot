# **AI Chatbot**

This is a simple AI chatbot built using Python, LangChain, and Chainlit. The chatbot is powered by the Phi-3-Mini-4K-Instruct model, which is exposed through the Hugging Face framework. This chatbot maintains context during a user session making it a stateful conversational AI agent.

## Tech Stack
- Backend: Python, LangChain
- Frontend: Chainlit
- AI Model: Phi-3-Mini-4K-Instruct via Hugging Face
   - Connecting Langchain and Huggingface: [ChatHuggingface class](https://python.langchain.com/api_reference/huggingface/chat_models/langchain_huggingface.chat_models.huggingface.ChatHuggingFace.html)


## Getting Started
Follow the steps below to install dependencies and run the chatbot.

### Installation
1. Clone the repository:  
   `git clone https://github.com/n33lp/ChatBot`
2. Navigate into it
   `cd ChatBot`

3. Install dependencies:  
   Run the following command to install all necessary dependencies:  
   `pip3 install -r requirements.txt`

### Run the chatbot
After installing dependencies, start the chatbot by running:  
`python3 chat.py`

## Acknowledgements
1. Model used: [Phi-3-Mini-4K-Instruct](https://huggingface.co/microsoft/Phi-3-mini-4k-instruct)
2. Learning and Reference resources
   - [Langchain](https://api.python.langchain.com/en/latest/langchain_api_reference.html)
   - [ChatHuggingFace](https://python.langchain.com/api_reference/huggingface/chat_models/langchain_huggingface.chat_models.huggingface.ChatHuggingFace.html)
   - [Chainlit](https://docs.chainlit.io/get-started/overview)
