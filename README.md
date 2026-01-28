# AI Doctor App with Vision and Voice (Multimodal LLM)

Imagine a doctor who can **see, listen, and talk** — all through AI! This project is exactly that. The AI Doctor can take your **voice input**, analyze **medical images**, and give back **spoken medical advice** in real-time.

It's like having a virtual doctor assistant on your computer, powered by the latest in **Vision-enabled LLMs** and **speech AI**.

---

## 🔹 What This Project Does
- Listens to the **patient's voice** and understands their problem.
- Analyzes **medical images** to detect possible conditions.
- Uses a **multimodal AI brain** (Vision + LLM) to reason about the problem.
- Speaks back the **diagnosis or advice** in natural voice.
- Fully interactive through a **voice-based UI**.

---

## 🔹 Project Layout

**Phase 1 – Setup the brain of the Doctor**
- Setup **GROQ API key**
- Convert medical images into required format
- Setup **Multimodal LLM** for reasoning

**Phase 2 – Patient Voice Input**
- Setup **Audio Recorder** (FFmpeg + PortAudio)
- Use **STT (Speech-to-Text)** model for transcription

**Phase 3 – Doctor Voice Output**
- Setup **TTS (Text-to-Speech)** with gTTS & ElevenLabs
- Convert AI text responses to **voice output**

**Phase 4 – VoiceBot UI**
- Build a **Gradio interface** for real-time interaction

---

## 🔹 Tools & Technologies
- **Groq** (AI inference)  
- **LLaMA 3 Vision** (vision-enabled LLM)  
- **OpenAI Whisper** (speech-to-text)  
- **gTTS & ElevenLabs** (text-to-speech)  
- **Gradio** (UI)  
- **Python** + **VS Code**  

---

## 🔹 Potential Improvements / Next Steps
- Fine-tune **Vision model on medical datasets**
- Add **multilingual support** for global users
- Integrate **paid state-of-the-art LLMs** for more accurate diagnosis
- Extend functionality to **mobile apps**  

---

## 🔹 One-Line Resume Version
> Built a real-time **Multimodal AI Doctor Assistant** integrating Vision LLMs, Speech Recognition, and Voice Synthesis for intelligent medical interaction.
