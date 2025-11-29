# EduGuide C Tutor — AI Chatbot Project

**EduGuide C Tutor** is an AI-powered academic assistant that explains C programming concepts, debugs code, and provides exam-style answers. This project demonstrates persona design, prompt engineering, and a working Botpress chatbot implementation.

---

## Live Demo
**Bot (EduGuide C Tutor):**  
_Paste your Botpress shareable link here (e.g. https://your-bot-link)_

---

## What’s in this repository
- `README.md` — This file (project overview + instructions).  
- `prompt_strategy.md` — Explanation of prompt engineering and tone control.  
- `persona_profiles/` — PDFs describing each persona (3 files).  
- `QA_flows/` — Sample Q&A flows for each persona (3 `.md` files).  
- `screenshots/` — Images showing the Botpress flow, AutonomousNode, emulator, and evidence of testing.  
- `embed_code.txt` (optional) — Web embed snippet if you published the bot.

---

## How to review / test the bot
1. Open the **Live Demo** link above (Botpress webchat).  
2. Try sample prompts:
   - `Explain pointers in C with example.`
   - `Write a C program to count vowels in a string.`
   - `Why does my program segfault?`  
3. The bot should restate the question, give a direct answer, provide step-by-step explanation, and include code when appropriate.

---

## Files you should check
- `persona_profiles/persona_1.pdf` — EduGuide C Tutor (detailed persona & prompt).  
- `persona_profiles/persona_2.pdf` — Mental Health Companion.  
- `persona_profiles/persona_3.pdf` — Travel Guide.  
- `QA_flows/persona1_QA.md` — 5 example exchanges for the C Tutor.  
- `prompt_strategy.md` — How and why prompts were designed.

---

## Implementation notes
- Built with **Botpress** using a custom AutonomousNode (system prompt) that enforces teaching format and tone.  
- Knowledge search was intentionally **disabled** so the bot follows the crafted prompt for consistent tutoring responses.  
- For academic integrity: the bot focuses on explanation and education; it does not provide legal, medical, or diagnostic advice.

---

## How to run locally (optional)
This repo contains documentation only. The running chatbot is hosted on Botpress Cloud — use the **Live Demo** link to interact.

---

## Credits
**Author:** Aditi Pradhan  
**Course / Task:** Future Interns — Task 3 (Chatbot Persona Development & Implementation)

---

## Contact
If you see any issues or need access to additional files/screenshots, open an issue or contact me at: *your-email@example.com*
