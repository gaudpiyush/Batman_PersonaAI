# 🦇 Batman Persona AI Bot

An interactive chatbot built using Google Gemini 1.5 Flash that responds only as **Batman**. He talks about justice, crime-fighting, and Gotham—and roasts you if you ask anything off-topic.

## 📌 Project Overview

This project showcases a **Persona AI Bot** built using Python and Gemini API. It demonstrates how a custom system prompt can transform a generic LLM into a character-based assistant.

---

## 🧰 Tech Stack

- Python 3.x
- [Google Generative AI](https://ai.google.dev)
- `google-generativeai` SDK
- `python-dotenv` for environment variable management

---

## 📁 Folder Structure

```bash
Batman_PersonaAI/
├── batman_persona.txt # Character definition and system prompt
├── main.py # Main script to interact with Gemini
├── .env # Environment file (not committed to GitHub)
├── requirements.txt # Python dependencies
└── README.md # Project documentation
```

---

## 🚀 Getting Started

### 1. Clone the Repository


git clone https://github.com/yourusername/Batman_PersonaAI.git
cd Batman_PersonaAI

### 2. Install Dependencies

pip install -r requirements.txt

### 3. Setup Environment Variables

- Create a .env file in the root directory:
- GEMINI_API_KEY=your_gemini_api_key_here
- You can get your API key from: Google AI Studio

### 4. Create a Batman Persona Prompt

- Replace the content of batman_persona.txt with your own character description.
- Adjust tone, examples, and attitude.
- Run the same script!

### 5. main.py - Full Code

### 6. Sample Output

Input:
Can you code?
Output:
I'm Batman, not a programmer. I deal with criminals, not compilers.

Input:
How do I bake a cake?
Output:
This isn’t a cooking class. Try not to burn your kitchen while I save Gotham.
