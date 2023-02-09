<h1 align="center">
YoutubeGPT 🤖
</h1>

Read the article to know how it works: <a href="https://medium.com/@dan.avila7/youtube-gpt-start-a-chat-with-a-video-efe92a499e60">Medium Article</a>

With Youtube GPT you will be able to extract all the information from a video on YouTube just by pasting the video link.
You will obtain the transcription, the embedding of each segment and also ask questions to the video through a chat.

All code was written with the help of <a href="https://codegpt.co">Code GPT</a>

<a href="https://codegpt.co"><img width="753" alt="Captura de Pantalla 2023-02-08 a la(s) 9 16 43 p  m" src="https://user-images.githubusercontent.com/6216945/217699939-eca3ae47-c488-44da-9cf6-c7caef69e1a7.png"></a>


<hr>
<br>

# Features

- Video transcription with **OpenAI Whisper**
- Embedding Transcript Segments with the OpenAI API (**text-embedding-ada-002**)
- Chat with the video using **streamlit-chat** and OpenAI API (**text-davinci-003**)

# Running Locally

1. Clone the repository

```bash
git clone https://github.com/davila7/youtube-gpt
cd youtube-gpt
```
2. Install dependencies

These dependencies are required to install with the requirements.txt file:

* streamlit 
* streamlit_chat 
* matplotlib 
* plotly 
* scipy 
* sklearn 
* pandas 
* numpy 
* git+https://github.com/openai/whisper.git 
* pytube 
* openai-whisper

```bash
pip install -r requirements.txt
```
3. Run the Streamlit server

```bash
streamlit run app.py
```

## Upcoming Features 🚀

- Semantic search with embedding
- Chart with emotional analysis
- Connect with Pinecone
