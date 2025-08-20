# PuruAI-Agent
AI Agent for my own
PuruAI/Medini

PuruAI/Medini is a versatile AI assistant deployed on Hugging Face Spaces, designed to assist with various tasks such as summarization, sentiment analysis, translation, and general Q&A. Built using Streamlit and LangChain, Medini offers a user-friendly interface for seamless interaction.

🚀 Features

Summarization: Condense long texts into concise summaries.

Sentiment Analysis: Determine the sentiment (positive/negative/neutral) of a given text.

Translation: Translate text between multiple languages.

General Q&A: Engage in open-ended conversations and retrieve information.

Short-Term Memory: Retain context within a session for coherent interactions.

🛠️ Technologies

Frontend: Streamlit

Backend: LangChain, Hugging Face Transformers

APIs: OpenAI API, Hugging Face Model Hub

📦 Installation

To run PuruAI/Medini locally:

Clone the repository:

git clone https://huggingface.co/PuruAI/Medini
cd Medini


Install dependencies:

pip install -r requirements.txt


Set up your environment variables:

export OPENAI_API_KEY="your_openai_api_key"
export SERPAPI_API_KEY="your_serpapi_api_key"  # Optional


Run the application:

streamlit run app.py

🌐 Usage

Once the application is running, open your browser and navigate to http://localhost:8501 to interact with Medini. Select your desired task from the sidebar and begin interacting with the AI assistant.

🔧 Configuration

The application is configured through the app.py file, where you can modify settings such as:

API Keys: Set your OpenAI and SerpAPI keys.

Model Selection: Choose different models for various tasks.

Memory Settings: Adjust the short-term memory parameters.

📄 License

This project is licensed under the Apache 2.0 License. See the LICENSE
 file for more details.
