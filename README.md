# YouTube Video Q&A and Summarization with RAG


This project leverages Python, LangChain, ChromaDB, and the Gemini API to build a Retrieval-Augmented Generation (RAG) system. It enables efficient question answering and summarization of YouTube video transcripts by integrating advanced language models and database retrieval techniques.

![Project Overview](/youtubeRag.png)

# Process

- User Inputs a topic | API call to fetch 3-5 Youtube Videos related to the topic
- User Chooses a Video (Youtube)
- Fetch Video Transcript
- Summarize the Video using LLM (Gemini)
- Feed the Transcript Data into the Vector DB (Chroma DB) | Apply Data embedding using Langchain
- During Q&A | Feed the LLM the question and correct context fromt the vector DB
