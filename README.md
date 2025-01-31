# Utah Tech Week - AI Hackathon 2025 (YouClip - Extract the Moments that Matter)

ai_heckathon_tw_25

## Goal

A system that processes YouTube videos by transcribing their content and generating video clips based on a user-defined query.

### **Key Features**  
- 🎙️ **Transcription**: Extracts spoken content from YouTube videos.  
- 🔍 **Query-Based Clipping**: Finds relevant segments based on a text query.  
- ✂️ **Automated Video Snippets**: Generates short clips based on keyword matches.

### **How It Works**  
1. 📥 **Fetch**: Download & process a YouTube video.  
2. 🎧 **Transcribe**: Convert speech to text using AI.  
3. 🔎 **Query & Search**: Find relevant moments based on keywords.  
4. ✂️ **Clip & Export**: Generate short clips from key segments.  

### **Potential Use Cases**  
✅ Educational content extraction  
✅ Research & fact-checking  
✅ Content summarization  
✅ Generating highlight reels  

## **Tech Stack**  
- **Python** – Language of choice
- **Whisper** – For transcription  
- **FFmpeg** – For video clipping  
- **pytubefix** – For fetching video content
- **pydub** - For converting audio to mp3
- **transformers** - HuggingFace transfomers for semantic search

## **Pre-trained ML Models Used**
- **[OpenAI Whisper (medium.en)](https://github.com/openai/whisper)**
- **[Semantic Search (intfloat/e5-large-v2)](https://huggingface.co/intfloat/e5-large-v2)**

## Demo

[Watch the demo video](https://youtu.be/N5yK6_4aynY)

[![Watch the demo video](https://img.youtube.com/vi/N5yK6_4aynY/0.jpg)](https://www.youtube.com/watch?v=N5yK6_4aynY)


### Possible Enhancements 🚀
-	🔹 Add AI summarization for more refined query results.
-	🔹 Support multi-language transcription.
-	🔹 UI for interactive search & playback.



