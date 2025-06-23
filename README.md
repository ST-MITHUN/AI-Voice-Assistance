
# Voice Activated AI Assistant using GPT-3.5 Turbo

This project is a **Voice-Controlled AI Assistant** built with **Python**, integrating:
- OpenAI's GPT-3.5-Turbo for intelligent conversation
- Speech Recognition for listening
- Text-to-Speech (TTS) for speaking back responses  
The assistant listens for a wake word (“Hey”), then engages in conversation with natural voice responses.

---

##  Features

-  **Wake word activation** ("Hey")
-  **Speech-to-Text** using Google Speech Recognition
-  **AI-generated responses** from OpenAI's GPT-3.5 Turbo
-  **Text-to-Speech** response using `pyttsx3` and `espeak` or `gTTS`
-  Continuous listening and interaction loop
-  Fun greetings and dynamic interaction personality

---

## Tech Stack

- **Python**
- **OpenAI GPT-3.5 Turbo API**
- **SpeechRecognition** (Google API)
- **pyttsx3** for text-to-speech
- **gTTS** (optional)
- **dotenv** for API key management
- **NumPy**
- **Matplotlib** (not used in this version but imported)

---

## How to Run

1. **Clone the Repository**

```bash
git clone https://github.com/yourusername/voice-ai-assistant.git
cd voice-ai-assistant
```

2. **Install Dependencies**

```bash
pip install openai python-dotenv SpeechRecognition pyttsx3 gTTS numpy matplotlib
```

3. **Set OpenAI API Key**

- Create a `.env` file in the project directory:

```bash
OPENAI_API_KEY=your_openai_api_key_here
```

4. **Run the Assistant**

```bash
python main.py
```

---

##  Usage

- The assistant waits for the wake word **"Hey"**
- Once activated, you can speak naturally
- The assistant listens, sends input to GPT-3.5, and speaks the response

---

##  Notes

- The project currently uses `espeak` on Linux or can be adapted with `gTTS` for cross-platform TTS
- Microphone access is required
- You must have an OpenAI API key

---

##  Example

```
Assistant: Listening for 'Hey'...
You: Hey
Assistant: "Well, hello there, Master of Puns and Jokes - how's it going today?"
You: What's the weather today?
Assistant: "I'm not connected to live weather services, but I hope it's sunny where you are!"
```

---

##  Credits

- OpenAI GPT-3.5 Turbo
- Google Speech Recognition
- pyttsx3
- gTTS

---
