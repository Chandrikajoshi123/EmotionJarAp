# EmotionJarAp

# 🫙 Emotion Jar – Your Daily Emotional Check-In

**Emotion Jar** is a friendly AI-powered web app that helps you name your emotions, reflect on them, and grow.  
Just type how you're feeling, and the app gives you an emoji, a matching color, a motivational quote, and a journaling prompt.  
It’s like putting a message in your own digital jar — one emotion at a time. 💌

---

## ✨ Features

- 🧠 AI-based **emotion detection** using a pre-trained transformer model
- 🎨 Beautiful interface with **emoji mood cards** and **pastel colors**
- 💬 Personalized **motivational quotes** and **journaling prompts**
- 📈 Optional **confidence score breakdown** from the model
- 💖 Designed for **emotional awareness**, **mental health reflection**, and **self-care**

---

## 🛠️ Built With

| Tool            | Purpose                              |
|-----------------|--------------------------------------|
| `Streamlit`     | Fast & interactive web app framework |
| `Transformers`  | Emotion classification via Hugging Face |
| `DistilRoBERTa` | Pre-trained model for emotion labels |
| `Python`        | Backend and app logic                |

---

## 🤖 Emotion Model

- **Model**: `j-hartmann/emotion-english-distilroberta-base`
- **Labels**: Joy, Sadness, Fear, Anger, Love, Surprise, Disgust, Neutral
- **Platform**: Hugging Face 🤗

---

## 📸 App Preview

![screenshot](screenshot.png)

---

## 🚀 Getting Started

### 1. Clone this repo

```bash
git clone https://github.com/yourusername/emotion-jar.git
cd emotion-jar
