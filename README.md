# Text-Summarization-
Summarizes the text from any website or Youtube video transcript.

🚀 Just built a Streamlit app leveraging LangChain and Groq’s Gemma 2 model to summarize content from YouTube videos and websites! 📄🎥

Users can simply input a URL (either a website or a YouTube video link) and the app fetches the content — using YouTubeTranscriptAPI for video transcripts or UnstructuredURLLoader for web pages. The content is then summarized using a custom prompt and LangChain’s summarization chain powered by Gemma 2 via Groq API. ⚡️

Key highlights:

Summarizes YouTube videos without needing to watch them 📺➡️📝

Fetches and summarizes any website content 🌐

Seamless Streamlit UI with sidebar API key input and live status updates

Uses LangChain's flexible prompt templating and summarization chains
