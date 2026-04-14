# estudeporvoz
Iniciação de dialogo por voz
# 🎙️ Voice Chat Multilingual (Whisper + ChatGPT + gTTS)

Sistema de conversação por voz multi-idiomas que utiliza:

- 🎧 Speech-to-Text com Whisper (OpenAI)
- 🧠 Processamento com ChatGPT
- 🔊 Text-to-Speech com gTTS (Google)

## 🚀 Objetivo

Permitir que o usuário fale em qualquer idioma e receba uma resposta inteligente também em voz.

---

## 🧠 Arquitetura

1. Usuário fala (áudio)
2. Whisper transcreve → texto
3. ChatGPT processa → resposta
4. gTTS converte → áudio
5. Sistema reproduz resposta

---

## 📁 Estrutura do Projeto
app/
├── main.py
├── config.py
├── services/
├── audio/
└── utils/

data/
├── input/
└── output/
