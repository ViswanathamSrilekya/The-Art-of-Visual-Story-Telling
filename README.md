🌟 Art of Visual Storytelling 🎨📸

Welcome to the Art of Visual Storytelling project! This application uses deep learning models to analyze images, detect objects, generate captions, and create engaging stories based on the detected scene.

✨ Features

🛠️ Object Detection using Faster R-CNN

💡 Gender Classification for people in images

📸 BLIP & CLIP Models for caption generation

📚 AI Story Generation with Google's Gemini API

🎧 Text-to-Speech conversion for generated stories

💻 Streamlit Web Interface for easy interaction

🌐 Public Web Access via Ngrok

⚡ Installation

To set up the project, run the following commands:

!pip install -q -U google-generativeai
!pip install git+https://github.com/openai/CLIP.git
!pip install deepface gtts streamlit pyngrok Pillow
!apt install cloudflared

🛠️ Setup Instructions


Set up Google Gemini API Key in your environment variables:

import os
os.environ['api_key'] = "your-gemini-api-key"

Run the Streamlit application:

streamlit run app.py

Use Ngrok to make it accessible online:

!cloudflared tunnel --url http://localhost:8501 &>/dev/null &

🎉 Usage

Upload an image.

Select the story genre (horror, adventure, fantasy, etc.).

Click Generate Story to get an AI-generated narrative.

Click Generate Audio to convert the story into speech.

📝 Technologies Used

Python 🔬

Streamlit 🌐

Google Gemini API 🌟

DeepFace 🤖

Faster R-CNN 📝

BLIP & CLIP Models 📸

gTTS (Google Text-to-Speech) 🎤

💡 Contributing

We welcome contributions! Feel free to fork the repo and submit a pull request.
