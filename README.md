# Text-Summarization-
Summarizes the text from any website or Youtube video transcript.

🚀 Just built a Streamlit app leveraging LangChain and Groq’s Gemma 2 model to summarize content from YouTube videos and websites! 📄🎥

Users can simply input a URL (either a website or a YouTube video link) and the app fetches the content — using YouTubeTranscriptAPI for video transcripts or UnstructuredURLLoader for web pages. The content is then summarized using a custom prompt and LangChain’s summarization chain powered by Gemma 2 via Groq API. ⚡️

## Key highlights:

Summarizes YouTube videos without needing to watch them 📺➡️📝

Fetches and summarizes any website content 🌐

Seamless Streamlit UI with sidebar API key input and live status updates

Uses LangChain's flexible prompt templating and summarization chains

## Installation

1. Clone this repository:
   ```
   git clone https://github.com/P-RajaRamesh/Text-Summarization-.git
   cd Text-Summarization-
   ```
2. Create a virtual environment and install dependencies:
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   pip install -r requirements.txt
   ```
3. Run the Application: ```streamlit run app.py```

## Application
Enter the api key and try pasting any youtube video url or any website url and start using the application to summarize the content from it!
