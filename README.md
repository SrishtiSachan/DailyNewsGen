# DailyNewsGen

DailyNewsGen is a personal automation project that fetches the top news headlines of the day and transforms them into engaging short videos, complete with narration and visuals. Perfect for social media or quick news updates! 


https://github.com/user-attachments/assets/2d460217-c871-495c-a4b7-e43bca70923c


The above is a sample video generated from this framework.

## 🚀 Features

📥 Fetches real-time top headlines using NewsAPI.<br/>

🧠 Summarizes news content using LangChain and LLaMA3, powered by the Kokoro LLM.<br/>

🎙️ Generates dynamic scripts and voiceover-ready narration.<br/>

🎬 Creates visually appealing videos using MoviePy and FFmpeg.<br/>

💻 Terminal-based interaction and automation via xterm.<br/>

## 📦 Getting Started

To get started with DailyNewsGen, clone the repo and run the Jupyter notebook to generate a news video for the day. I ran this on Google colab so i would recommend you test it out there too.

🗂️ Project Structure

```DailyNewsGen.ipynb```: Main notebook containing the automation workflow.

```images/```: Folder for the saved images for the given news. I am extracting them from the output of news api.<br/>

```audios/```: This folder contains the audio created for specific news item. I refined the narration for this one with llama3.<br/>

```videos/```: Videos created using the above images and audios.<br/>

```output.mp4```: This is the final video file created by concatenating all files in videos folder.<br/>

## ✅ Prerequisites

Ensure you have the following installed:

### Python Packages
Install dependencies via pip:
```
pip install newsapi-python langchain moviepy ffmpeg-python
```
### External Requirements

- FFmpeg must be installed and available in your system path<br/>
- API Key for NewsAPI<br/>
- Access to the kokoro LLM (used via LangChain and LLaMA3)<br/>

## 🗺️ Roadmap

 - [X] Fetch and summarize daily news headlines<br/>
 - [X] Generate script/narration using LLM<br/>
 - [X] Compile video with visuals and transitions
 - [X] Add voice narration using text-to-speech
 - [ ] Integrate background music
 - [ ] Schedule and automate daily runs
 - [ ] Upload output to social platforms (YouTube Shorts, TikTok, etc.)

## 📄 License

This is a personal project and currently not licensed for redistribution. Feel free to fork and customize for educational or personal use.
